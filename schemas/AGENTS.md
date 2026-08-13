# Schema instructions

- Use JSON Schema Draft 2020-12 expressed as YAML unless an ADR changes the choice.
- Experimental identifiers use `v0alpha1`.
- Do not make a field required without a source-backed or explicitly proposed rationale.
- Describe legal or archival concepts conservatively. Representation is not proof of compliance.
- Preserve semantic compatibility or document and version the breaking change.
- Update a fictional example and conformance fixture when schema semantics change.
- Use stable identifiers and avoid vendor-specific platform fields in the public core.
- Run `python scripts/validate.py` after every schema change.
