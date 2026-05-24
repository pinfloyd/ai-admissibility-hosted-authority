# Admission Record Model

Public-safe conceptual fields:

- record_id
- tenant_id
- project_id
- policy_id
- intent_hash
- decision
- timestamp_utc
- signature
- public_key_id

Immutable fields:

- intent_hash
- decision
- timestamp_utc
- signature
- record_id

Secret values are never included in public records.
