# Provisional research framing

## Practical problem

Swedish public-sector information governance is expressed across legislation, regulations, official guidance, organizational policy, standards and human interpretation. Data-platform delivery, meanwhile, increasingly uses version-controlled schemas, data contracts, data products and automated CI/CD checks.

The practical problem is not an absence of governance principles. It is the difficulty of translating heterogeneous governance meaning into explicit, traceable and testable representations without falsely claiming that schema validation proves legal, archival or organizational compliance.

## Academic problem

Research has addressed Design Science Research methods, metadata interoperability and automated data governance. Open standards now provide machine-readable descriptions of data contracts, data products and catalogue metadata. However, it remains to be established how these bodies of knowledge connect, and whether existing artifacts sufficiently represent Swedish public-sector requirements concerning semantics, accountability, provenance, public records, retention, disposition, preservation and long-term accessibility.

## Provisional research gap

**Working hypothesis, not yet a finding:** Existing research and open standards may address parts of automated data governance, public-sector metadata interoperability and records management separately, while leaving insufficient guidance for a coherent, evaluated and machine-readable profile for Swedish public-sector data products.

The gap must be tested through:

- a documented literature review;
- field-level analysis of ODCS, ODPS and DCAT-AP-SE;
- authoritative-source review of DIGG, eSam, Riksarkivet and applicable RA-FS;
- explicit comparison of existing coverage, genuine extension needs and matters that cannot responsibly be encoded as schema requirements.

## Provisional purpose

The study aims to design and evaluate a machine-readable reference profile that adapts open data-contract and data-product standards to selected Swedish public-sector governance and archival-readiness needs, while preserving traceability to source, interpretation and evidence.

The artifact is intended to support consistent representation, review and static validation. It is not intended to determine legal compliance automatically.

## Candidate research questions

### Recommended main question

**RQ1:** How can an open, machine-readable profile of data-contract and data-product standards represent selected Swedish public-sector requirements for semantic interoperability, accountability, provenance and archival readiness?

### Evaluation question

**RQ2:** To what extent does the proposed profile satisfy defined requirements for expressiveness, traceability, standards compatibility, comprehensibility and machine validation in a realistic public-sector scenario?

### Boundary question

**RQ3:** Which identified governance and archival requirements can be represented and statically validated in the artifact, and which require organizational judgment, legal interpretation or runtime evidence?

## Alternative narrower formulation

For a 15 ECTS thesis, a narrower main question may be safer:

> How can ODCS and/or ODPS be profiled to represent and statically validate selected archival-readiness and accountability metadata for data products in Swedish government agencies?

This formulation sacrifices breadth but improves the feasibility of implementation and evaluation.

## Unit of design

A candidate unit of design is a technology-independent **information product** realized through one or more technical data products and contracts. This remains a design hypothesis to evaluate, not a settled definition in the referenced standards.

## Candidate artifact

The minimum viable artifact may contain:

- a documented Swedish public-sector profile of ODCS and/or ODPS;
- a YAML or JSON Schema representation;
- controlled vocabularies or external references where appropriate;
- a source-to-requirement-to-field traceability matrix;
- synthetic examples;
- deterministic validation tests;
- explicit non-automatable and out-of-scope classifications.

## Required conceptual separations

The study must not conflate:

- data quality with metadata quality;
- semantic interoperability with syntactic validity;
- public-document or record status with archival selection;
- retention with disposition decisions;
- provenance with proof of authenticity;
- preservation readiness with completed preservation;
- schema conformance with legal or regulatory compliance.

## Contributions

### Contribution to research

An evaluated design artifact and design knowledge about the opportunities and limits of profiling open data-product standards for a national public-sector information-governance context.

### Contribution to practice

A reusable, vendor-neutral reference model that can improve explicitness, traceability and early validation of governance metadata.

### Public thought-leadership contribution

An open reference profile, synthetic examples and evidence-backed design rationale.

### Private commercial boundary

Detailed assessment scoring, workshops, delivery processes, customer mappings and implementation accelerators remain outside the public artifact.

## Open decisions for supervisor review

- Whether the primary baseline should be ODCS, ODPS or a deliberately bounded combination.
- Whether DCAT-AP-SE is part of the artifact or only an external publication mapping.
- Which RA-FS instruments and requirements are applicable to the selected scope.
- Whether expert review, scenario evaluation or a combination is feasible.
- Whether the information-product abstraction is necessary or over-expands the Bachelor thesis.
