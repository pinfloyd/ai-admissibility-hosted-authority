# GitHub Actions Admission Gate

Purpose:

Provide a CI/CD gate that fails closed unless an external admission authority returns a valid signed ALLOW.

The GitHub runner must not become the final authority.

No signed ALLOW means no execution.
