# Tenant, API Key, and Record Layer

Conceptual objects:

- tenant_id
- project_id
- api_key_id
- policy_id
- admission_record_id
- public_key_id
- usage_counter
- billing_state

Rules:

- Tenant separation is mandatory.
- API key values must never be printed.
- Admission records must be immutable after creation.
- DENY, invalid, missing, or expired admission must fail closed.
