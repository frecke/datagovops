# DataGovOps

Open reference models and standards profiles for machine-readable, automatable and auditable data governance.

This repository explores how open data-contract and data-product standards can be profiled for Swedish public-sector needs, including semantic interoperability, accountability, provenance, archival readiness and long-term accessibility.

> Status: early-stage research and reference implementation. Nothing here should yet be treated as authoritative legal guidance or a finalized standard.

## Scope

- Machine-readable governance metadata
- Data contracts and data-product specifications
- Swedish public-sector interoperability and open-data concerns
- Archival status, retention and disposition metadata
- Provenance, authenticity, integrity and audit evidence
- Static validation suitable for CI/CD governance gates

## Public boundary

This repository contains concepts, open profiles, schemas, examples and selected reference implementations. Detailed assessment methods, scoring models, customer mappings, workshop playbooks and delivery accelerators remain private.

In short: **publish the model, retain the method**.

## Repository layout

- `schemas/` machine-readable profiles and schemas
- `examples/` fictional, non-customer examples
- `docs/` architecture notes and decisions
- `scripts/` validation tooling
- `tests/` validation fixtures and test guidance

## Related standards and authorities

Expected reference points include ODCS, ODPS, DCAT-AP-SE, DIGG and eSam guidance, and applicable Swedish archival legislation and Riksarkivet regulations. References will be versioned and mapped explicitly as the work matures.

## Academic context

The repository may support Design Science Research into a Swedish public-sector DataGovOps artifact. Research claims, evaluations and legal interpretations must remain traceable and clearly separated from proposals and assumptions.

## AI-assisted contribution

Repository instructions, reusable skills and read-only specialist agents live in `AGENTS.md`, `.agents/` and `.codex/`. See `docs/ai/README.md`.

## Licensing

Code and schemas are licensed under Apache License 2.0. Documentation is licensed under CC BY 4.0 unless a file states otherwise. See `LICENSING.md`, `LICENSE` and `LICENSES/CC-BY-4.0.txt`.

## Contributing

See `CONTRIBUTING.md`, `GOVERNANCE.md` and `SECURITY.md`.
