# platform-observability-sre
DDD/EDA platform capability (svc-obs-sre) owner:Observability and SRE Squad wave:0

## Strict mTLS Enforcement

This repository includes the Wave 0 strict mTLS policy validator pattern:

- Workflow: `.github/workflows/strict-mtls-enforcement.yml`
- Validator: `scripts/validation/validate-strict-mtls.mjs`

Run locally:

```bash
npm ci
npm test
npm run validate:strict-mtls
```
