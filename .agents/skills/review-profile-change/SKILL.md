---
name: review-profile-change
description: Review a DataGovOps schema or profile change for traceability, semantics, compatibility, archival readiness
  and public/private boundaries. Use before accepting changes to schemas, required fields or governance meaning.
---

1. Read the nearest `AGENTS.md`, relevant ADRs, schema, examples and source entries.
2. Identify the proposed semantic change and affected consumers.
3. Verify every normative or legal claim against an authoritative source.
4. Check separation of data quality, metadata quality, interoperability, compliance, archival readiness and operations.
5. Check compatibility, versioning and migration impact.
6. Check public/private IP and confidentiality boundaries.
7. Validate schema and examples with `python scripts/validate.py`.
8. Lead with concrete findings ordered by risk.
9. Do not approve solely because YAML is valid.
