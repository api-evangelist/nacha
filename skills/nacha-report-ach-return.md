---
name: Report an ACH return
description: Share ACH return payment data with originators and payment providers to support fraud and risk mitigation, using the Afinis Reporting ACH Return (RET) API.
api: openapi/nacha-ret.json
operations:
  - Reporting ACH Return Payments
---

# Report an ACH return (Afinis RET API)

## Auth
- `apikey` query parameter (Afinis application key). Optional `Request_Id` (uuid) header.

## Steps
1. **Submit the return report** — `POST /ret` (`Reporting ACH Return Payments`). The ISO 20022 body carries the original payment reference plus the ACH return reason so downstream originators and providers can act on fraud/risk signals.
2. Confirm the `200` acknowledgement; on failure inspect the error envelope.

## Notes
- The RET signal also feeds the "Account Validation Plus Name Plus Return" combined check (`openapi/nacha-account-validation-plus-name-ret.json`, `validateAccountWithNameAndRET`).
- Errors: `1000/1001` auth, `2000-2003` request, `3001` server. See `errors/nacha-problem-types.yml`.
