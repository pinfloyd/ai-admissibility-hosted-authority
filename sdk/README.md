# SDK Surface

Planned SDKs:

- Python
- Node.js
- CLI

SDK responsibilities:

- build canonical intent
- submit admission request
- verify signed response
- fail closed on DENY, missing, invalid, or expired admission
- never execute the protected action itself
