# Document Studio

Documents, PDF, reports, contracts

Create and edit rich documents, PDFs, and Markdown. Draft contracts, resumes, proposals, invoices, and certificates, publish eBooks, magazines, and newsletters, and generate HR documents like offer letters and job descriptions.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (8):**

| Service | Status |
|---|---|
| `document-service` | Core |
| `publishing-service` | Core |
| `media-service` | New (Tier-1) |
| `workflow-service` | Core |
| `knowledge-service` | Core |
| `verification-service` | New (Tier-1) |
| `collaboration-service` | Suggested — not yet built |
| `asset-service` | Suggested — not yet built |
