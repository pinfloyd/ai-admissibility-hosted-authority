# AI Admissibility Hosted Authority — candidate/reference package

This repository contains engineering candidate and reference material for the Hosted Authority line.

It is **not** the canonical installed runtime and should not be used as the authoritative statement of current live product status.

Official product surface:

https://ai-admissibility.com/

## Current public status

The project has a canonical installed boundary behind a controlled public access path. Anonymous public rejection is expected behavior for protected routes.

The current public GitHub Marketplace Action remains a bounded evaluation surface; it is not, by itself, a customer-specific production no-bypass integration.

## What this repository contains

This repository preserves candidate/reference material including:
- hosted-authority components;
- GitHub Actions admission-gate material;
- SDK/reference material;
- tenant-record-layer material;
- demo and publication-gate artifacts.

Some files may represent earlier candidate stages. Their presence does not supersede the canonical status published on the official site.

## Product rule

**No Admission = No Execution.**

A signed ALLOW is an authority decision, not execution itself. Protected execution must remain bound to the agreed workflow and customer-specific controls.

## Current paths

- Product and documentation: https://ai-admissibility.com/
- Boundary architecture / proof: https://github.com/pinfloyd/ai-admissibility-boundary
- Marketplace evaluation Action: https://github.com/pinfloyd/ai-admissibility-action
- Request access: https://ai-admissibility.com/request
