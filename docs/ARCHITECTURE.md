# Architecture

AI Admissibility separates execution from final admission authority.

The protected executor prepares an intent. The external authority evaluates whether the intent is admitted before execution can proceed. The response is a signed admission record.

High-level flow:

Customer executor -> admission request -> hosted external authority -> signed ALLOW or DENY -> fail-closed enforcement.

Required properties:

- The executor must not self-authorize.
- Missing admission must fail closed.
- Invalid admission must fail closed.
- DENY must block execution.
- Signed ALLOW is not the same as execution.
- Owner approval may still be required after ALLOW.
