---
name: Validate a bank account before an ACH transfer
description: Confirm a US bank account is open and able to accept an ACH credit or debit before you originate a payment, reducing returns and fraud.
api: openapi/nacha-account-validation.json
operations:
  - validateDebtorAccount
  - validateCreditorAccount
---

# Validate a bank account (Afinis Account Validation API)

Use this before originating ACH to cut return/fraud risk.

## Auth
- Pass your Afinis application key on the `apikey` query parameter (register at afinis.org).
- Optionally send a `Request_Id` (uuid) header so the call is traceable in provider logs.

## Steps
1. **Validate the debtor (paying) account** — `POST /accounts/validate/achPaymentDebitAcceptance` (`validateDebtorAccount`). Send the account/routing details in the ISO 20022 body; the response confirms the account can accept an ACH debit.
2. **Validate the creditor (receiving) account** — `POST /accounts/validate/achPaymentCreditAcceptance` (`validateCreditorAccount`) for the account that will receive the credit.
3. Only proceed to payment initiation when both validations pass.

## Error handling
- `401` errorcode `1000/1001` — API key/token missing or expired; re-register/re-auth.
- `400` errorcode `2000-2003` — malformed JSON, missing/invalid field, or bad date/combination; fix the body.
- `422` errorcode `4001` — business-rule failure; read `detail[].message`.
See `errors/nacha-problem-types.yml`. No idempotency key exists — do not blind-retry writes (see `conventions/nacha-conventions.yml`).
