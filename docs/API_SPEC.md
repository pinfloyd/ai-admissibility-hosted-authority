# Public API Specification

Planned public routes:

- GET /v1/pubkey
- GET /v1/health
- POST /v1/admit
- GET /v1/records/{record_id}

The API returns signed admission records.

The API does not execute customer actions.

A missing, invalid, expired, malformed, or denied admission must fail closed.
