# Nacha (nacha)

Nacha (formerly the National Automated Clearing House Association) is the nonprofit, member-governed steward of the ACH Network — the batch account-to-account payment rail that moves consumer and business direct deposits, direct payments, bill pay, and B2B transfers across the United States, totaling more than 30 billion payments and over $80 trillion in value annually. Nacha writes and enforces the Nacha Operating Rules that bind participating depository financial institutions, but it is not itself an ACH Operator — the Federal Reserve (FedACH) and The Clearing House clear and settle the files. Nacha does not run a public self-serve payments API of its own; its API posture is delivered through **Afinis Interoperability Standards**, the Nacha-stewarded group that publishes royalty-free standardized financial-services API specifications, and through **Phixius**, its payment-information exchange platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nacha/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nacha/refs/heads/main/apis.yml)

## Tags

- Payments
- United States
- ACH
- Account-to-Account
- Real-Time Payments
- Account Validation
- Payment Rails
- ISO 20022
- Standards
- Afinis

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## API Posture

Nacha is a **rulebook- and documentation-first scheme steward**, not a self-serve PSP. There is no Nacha-hosted production payments API. What is real and public is the Afinis API Catalog: 24 standardized Swagger 2.0 (OpenAPI) specifications hosted on SwaggerHub under the ASIG organization, catalogued at [nacha.org/content/apis-development](https://www.nacha.org/content/apis-development). These are interoperability standards intended for financial institutions and their vendors to implement; each declares an API-key (`apikey` query parameter) security scheme and requires developer registration with Afinis. All 24 specs are harvested verbatim into [`openapi/`](openapi/).

## APIs (Afinis Interoperability Standards)

**Payment initiation**

- **Afinis Initiate ACH Payment API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Initiate_Payment/1.0.7) · [`openapi/nacha-initiate-payment.json`](openapi/nacha-initiate-payment.json)
- **Afinis Initiate Payment API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Initiate_Payment_API/1.0.2) · [`openapi/nacha-initiate-payment-api.json`](openapi/nacha-initiate-payment-api.json)
- **Afinis Pay Me API** (request-for-payment) — [Swagger](https://app.swaggerhub.com/apis/ASIG/Pay_Me_API/1.0.11) · [`openapi/nacha-pay-me.json`](openapi/nacha-pay-me.json)
- **Afinis Authorize to Pay (Debit Authorizations) API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Authorize_To_Pay/1.0.6) · [`openapi/nacha-authorize-to-pay.json`](openapi/nacha-authorize-to-pay.json)

**Instant & wire payments**

- **Afinis Initiate Instant Payment API (IIP)** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Initiate_Instant_Payment_API/1.0.6) · [`openapi/nacha-initiate-instant-payment.json`](openapi/nacha-initiate-instant-payment.json)
- **Afinis Instant Payment Transfer API (IPT)** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Instant_Payment_Transfer/1.0.1) · [`openapi/nacha-instant-payment-transfer.json`](openapi/nacha-instant-payment-transfer.json)
- **Afinis Initiate Wire Payment API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Initiate_Wire_Payment_API/1.0.3) · [`openapi/nacha-initiate-wire-payment.json`](openapi/nacha-initiate-wire-payment.json)
- **Afinis Get Wire Status API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Get_Wire_Status_API/1.0.0) · [`openapi/nacha-get-wire-status.json`](openapi/nacha-get-wire-status.json)

**Cross-border (International ACH Remittance)**

- **Afinis International ACH Remittance (IAR) API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/IAR/1.0.1) · [`openapi/nacha-iar.json`](openapi/nacha-iar.json)
- **Afinis IAR Plus API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/IAR_Plus/1.0.1) · [`openapi/nacha-iar-plus.json`](openapi/nacha-iar-plus.json)

**Status, returns & disputes**

- **Afinis Transaction Status API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/transaction_status/1.0.14) · [`openapi/nacha-transaction-status.json`](openapi/nacha-transaction-status.json)
- **Afinis Reporting ACH Return (RET) API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/RET_API/1.0.3) · [`openapi/nacha-ret.json`](openapi/nacha-ret.json)
- **Afinis Written Statement of Unauthorized Debit (WSUD) API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Written_Statement_of_Unauthorized_Debit/1.0.8) · [`openapi/nacha-wsud.json`](openapi/nacha-wsud.json)
- **Afinis Proof of Authorization API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Proof_of_Authorization/1.0.6) · [`openapi/nacha-proof-of-authorization.json`](openapi/nacha-proof-of-authorization.json)

**Account validation & fraud**

- **Afinis Account Validation API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/account_validation/1.0.2) · [`openapi/nacha-account-validation.json`](openapi/nacha-account-validation.json)
- **Afinis Account Validation Plus Ownership (Name) API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Account_Validation_Plus_Ownership_API/1.1.0) · [`openapi/nacha-account-validation-plus-name.json`](openapi/nacha-account-validation-plus-name.json)
- **Afinis Account Validation Plus Name Plus Return API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Account_Validation_Plus_Name_and_RET/1.0.4) · [`openapi/nacha-account-validation-plus-name-ret.json`](openapi/nacha-account-validation-plus-name-ret.json)
- **Afinis Real-Time Billing Account Validation API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/RealTimeBillingAccountValidation/1.0.7) · [`openapi/nacha-realtime-billing-account-validation.json`](openapi/nacha-realtime-billing-account-validation.json)

**Corporate cash management**

- **Afinis Get Corporate Account Balances API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Get_Corporate_Account_Balances_API/1.0.3) · [`openapi/nacha-corporate-account-balances.json`](openapi/nacha-corporate-account-balances.json)
- **Afinis Get Corporate Transaction History API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Get_Corporate_Transaction_History_API/1.0.5) · [`openapi/nacha-corporate-transaction-history.json`](openapi/nacha-corporate-transaction-history.json)
- **Afinis Get Transaction Detail API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Get_Transaction_Detail_API/1.0.4) · [`openapi/nacha-corporate-transaction-detail.json`](openapi/nacha-corporate-transaction-detail.json)

**Directory services**

- **Afinis Payee Profile API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Payee_Profile_API/2.1.3) · [`openapi/nacha-payee-profile.json`](openapi/nacha-payee-profile.json)
- **Afinis Bank Contacts API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/bank_contacts/1.0.5) · [`openapi/nacha-bank-contacts.json`](openapi/nacha-bank-contacts.json)
- **Afinis Bank Contact V2 API** — [Swagger](https://app.swaggerhub.com/apis/ASIG/Bank_Contact_V2/1.0.9) · [`openapi/nacha-bank-contact-v2.json`](openapi/nacha-bank-contact-v2.json)

## Common Properties

- [Website](https://www.nacha.org/)
- [About](https://www.nacha.org/content/about-us)
- [Developer Portal — Afinis API Catalog](https://www.nacha.org/content/apis-development)
- [API Reference — Afinis API Catalog](https://www.nacha.org/content/afinis-api-catalog)
- [Documentation — Afinis Interoperability Standards](https://www.nacha.org/content/afinis-interoperability-standards)
- [Getting Started — ACH Guide for Developers](https://achdevguide.nacha.org/)
- [Nacha Operating Rules](https://www.nacha.org/rules)
- [News / Blog](https://www.nacha.org/news)
- [LinkedIn](https://www.linkedin.com/company/nacha)
- [Terms / Legal Information](https://www.nacha.org/content/legal-information)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
