---
name: Initiate an ACH payment and track its status
description: Originate an ACH credit or debit instruction through the Afinis standard, then poll its status by instruction ID.
api: openapi/nacha-initiate-payment.json
operations:
  - ACH Payments Credit
  - ACH Payments Debit
  - GetTransactionStatusByInstructionId
  - GetTransactionStatusByTransactionId
---

# Initiate an ACH payment and track status (Afinis)

## Auth
- `apikey` query parameter (Afinis application key). Optional `Request_Id` (uuid) header for tracing.

## Steps
1. **(Recommended) Validate the account first** — see the `nacha-validate-account` skill.
2. **Originate the payment**:
   - Credit push: `POST /payments/ach/credit` (`ACH Payments Credit`).
   - Debit pull: `POST /payments/ach/debit` (`ACH Payments Debit`).
   Body carries the ISO 20022 `paymentInformation` object; capture the returned instruction identification.
3. **Check status** via the Transaction Status API (`openapi/nacha-transaction-status.json`):
   - By instruction: `GET /payments/ach/status/instructionId/{instructionIdentification}` (`GetTransactionStatusByInstructionId`).
   - By transaction: `GET /payments/ach/status/transactionId/{transactionIdentification}` (`GetTransactionStatusByTransactionId`).

## Error handling
Custom envelope `{detail:[{errorcode,message}]}` — `1000/1001` auth, `2000-2003` request, `3001` server, `4001` unprocessable. No API idempotency key: track the instruction ID yourself and use status polling rather than re-POSTing. See `errors/nacha-problem-types.yml` and `conventions/nacha-conventions.yml`.
