# Historical/reference API specification

**Status: earlier planned API shape. Not the current public API contract.**

Earlier design material proposed routes such as:

- `GET /v1/pubkey`
- `GET /v1/health`
- `POST /v1/admit`
- `GET /v1/records/{record_id}`

Those routes are not a claim about the current public deployment.

## Current public contract

The canonical installed boundary is used through controlled integration and demonstration paths.

For the current public surface:

- the public identity endpoint is intentionally protected;
- anonymous admission is intentionally rejected;
- the canonical demonstration is https://ai-admissibility.com/canonical-pilot/;
- the public website does not expose a general-use customer authority API.

The architectural requirement remains unchanged:

A missing, invalid, expired, stale, unverifiable, or denied admission must fail closed.

**No Admission = No Execution.**
