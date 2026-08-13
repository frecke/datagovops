---
name: add-authoritative-reference
description: Add or update an authoritative DataGovOps source and its traceability metadata. Use for standards, Swedish
  legislation, RA-FS, DIGG, eSam, DCAT, ODCS, ODPS or research-method references. Do not use for unsupported claims.
---

1. Open and inspect the primary or authoritative source.
2. Verify the exact title, issuer, version or publication date, URL and normative status.
3. Decide whether the source is legislation, regulation, official guidance, standard, research or contextual material.
4. Add or update the entry in `docs/references/source-register.yaml`.
5. Update the appropriate thematic reference page.
6. Keep derived requirements separate from source metadata.
7. Mark interpretation, applicability and current-version questions explicitly.
8. Run `python scripts/validate.py`.
9. Summarize the source added, what it supports and what it does not establish.
