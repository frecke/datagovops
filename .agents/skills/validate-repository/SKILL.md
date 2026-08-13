---
name: validate-datagovops-repository
description: Validate DataGovOps YAML, JSON Schemas and known examples, then diagnose failures. Use after changing schemas,
  examples, source metadata, skills or GitHub workflow YAML.
---

1. If dependencies are unavailable, install them with `python -m pip install -r requirements-dev.txt`.
2. Run `python scripts/validate.py`.
3. Diagnose the first root cause rather than patching symptoms.
4. Re-run validation after the repair.
5. Report the exact command, result and any validation coverage gap.
6. Do not describe a passing syntax check as proof of legal or archival compliance.
