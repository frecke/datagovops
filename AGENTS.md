# Repository instructions

## Mission

Build vendor-neutral, machine-readable and auditable DataGovOps reference artifacts for Swedish public-sector use.

The repository supports public standards work, academic research and practical reference implementations. It is not
authoritative legal guidance and must not be presented as one.

## Non-negotiable boundaries

- Never add customer-identifiable information, production data, credentials or private commercial methods.
- Public artifacts may contain principles, profiles, schemas, fictional examples and traceable research material.
- Detailed scoring, customer mappings, delivery playbooks and accelerators belong in private repositories.
- Keep legal requirements, regulatory requirements, guidance, standards, interpretations, design proposals and
  hypotheses visibly distinct.
- Do not invent sources, standard capabilities, legal obligations, expert feedback, interviews or evaluation results.

## Source discipline

- Prefer primary and authoritative sources.
- Record exact title, issuer, version or publication date, stable URL, access date and normative status.
- Add verified sources to `docs/references/source-register.yaml`.
- Put requirements derived from a source in a separate traceability artifact. A citation alone is not a requirement.
- Treat living guidance as time-sensitive and re-verify it before making firm claims.
- For Riksarkivet and RA-FS, verify applicability and current consolidated wording before deriving a control.

## Design discipline

Keep these concerns separate:

1. data quality;
2. metadata quality;
3. semantic interoperability;
4. legal and regulatory compliance;
5. archival compliance and preservation readiness;
6. operational platform governance.

A schema validates representation and consistency. It does not prove legal compliance, archival compliance or control
effectiveness.

## Repository map

- `schemas/`: experimental and released machine-readable profiles
- `examples/`: synthetic, fictional examples
- `docs/references/`: source index and machine-readable source register
- `docs/adr/`: significant design decisions
- `.agents/skills/`: reusable project workflows
- `.codex/agents/`: narrow, project-scoped read-only custom agents
- `scripts/`: deterministic validation
- `tests/`: conformance and compatibility fixtures

Read the closest nested `AGENTS.md` before changing a specialized directory.

## Working method

1. Inspect existing sources, ADRs, schemas and examples.
2. State assumptions and identify facts that need verification.
3. For a substantial cross-cutting change, create and maintain an ExecPlan using `PLANS.md`.
4. Make the smallest coherent change.
5. Update source traceability, documentation, examples and tests together when semantics change.
6. Run `python scripts/validate.py`.
7. Report what changed, evidence used, validation performed and remaining uncertainty.

## AI workflow

Use repository skills rather than deprecated custom-prompt files. Invoke a skill explicitly when its workflow matches,
or allow Codex to select it from its description.

Use custom subagents for bounded read-heavy work such as source verification and independent schema review. Parallel
agents must not edit overlapping files. Keep one primary writer responsible for integration and final validation.

## Licensing

- Code, schemas and executable examples: Apache-2.0.
- Documentation and diagrams: CC-BY-4.0 unless a file states otherwise.
- Third-party sources retain their own licenses and are referenced, not copied, unless reuse is explicitly permitted.
- Private or customer material must never be relicensed by moving it here without authorization.

See `LICENSING.md`.

## Code review rules

Flag changes that:

- introduce unverified legal or standards claims;
- collapse distinct governance concerns into a single compliance claim;
- remove source, version or provenance information;
- make a required field without documented rationale and evaluation;
- include real customer or production information;
- create incompatible schema changes without a versioning decision;
- claim that schema validation proves compliance or security;
- weaken the public/private IP boundary.

## Definition of done

A change is done when relevant sources and assumptions are traceable, confidentiality and licensing are safe, schemas
and examples remain consistent, validation passes, and limitations are explicit.
