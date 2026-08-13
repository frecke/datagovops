# Research inception plan

## 1. Purpose and user-visible outcome

Create a public, reproducible pre-thesis research foundation covering literature search, annotated bibliography, standards review, research framing, the provisional research gap and a Design Science Research methodology.

## 2. Scope and explicit exclusions

Included:

- public and peer-reviewed sources;
- provisional academic framing;
- reproducible search and review protocols;
- non-customer-specific artifact planning.

Excluded:

- formal participant recruitment or data collection;
- customer-identifiable information;
- unpublished expert-review data;
- commercial scoring, workshops and accelerators;
- claims of legal compliance;
- runtime policy enforcement.

## 3. Facts, assumptions and questions to verify

### Facts

- The repository is an early-stage public reference implementation.
- ODCS, ODPS and DCAT-AP-SE are current working standards baselines in the source register.
- DSR is supported by established information-systems research.
- Metadata-driven automation of data-governance processes has peer-reviewed precedent.

### Assumptions

- A standards profile is likely to be an appropriate Bachelor-level artifact.
- Static validation can provide useful early governance checks.
- The Swedish public-sector intersection is insufficiently covered by existing open standards and research.

### Questions to verify

- Is the topic accepted by Mid Sweden University and an assigned supervisor?
- Which standards and Swedish requirements fit a 15 ECTS scope?
- Which RA-FS instruments are applicable?
- Which research databases are available through university access?
- Which evaluation design is feasible and ethically appropriate?

## 4. Authoritative sources and versions

Working baselines:

- ODCS 3.1.0;
- ODPS 1.0.0;
- W3C DCAT 3;
- DCAT-AP 3.0.1;
- DCAT-AP-SE 3.0.1;
- current consolidated Arkivlag;
- applicability-qualified RA-FS;
- current DIGG, eSam and Riksarkivet guidance.

Exact schemas, consolidated wording and living guidance must be re-verified before requirements are derived.

## 5. Public/private and confidentiality assessment

The research protocol, public-source bibliography, generic framing and reference artifact belong publicly. Case evidence, personal data, confidential requirements, raw evaluation responses and private delivery methods remain private.

## 6. Design decisions and alternatives

Current decision: start with a public research package before selecting final profile fields.

Alternatives to decide later:

- ODCS-only profile;
- ODPS-only profile;
- bounded ODCS and ODPS combination;
- DCAT-AP-SE as external mapping versus artifact component;
- expert review versus scenario evaluation versus a combination.

## 7. Implementation milestones

1. Establish research protocol and seed bibliography. Completed in initial branch.
2. Run full database searches and maintain screening log.
3. Complete version-pinned standards inventory.
4. Build source-to-requirement matrix.
5. Freeze minimum viable artifact scope with supervisor.
6. Implement schema/profile and synthetic examples.
7. Run formative evaluation and revise.
8. Conduct approved summative evaluation.
9. Communicate results and limitations.

## 8. Validation and evaluation plan

Documentation validation:

- inspect Markdown links and internal navigation;
- validate YAML source register;
- ensure every source has identity, status and limitations;
- check that claims are labelled by evidence state.

Later artifact evaluation:

- automated conformance tests;
- requirements coverage analysis;
- standards compatibility review;
- scenario demonstration;
- structured expert review if approved.

## 9. Compatibility and migration impact

This inception work adds documentation and research sources. It does not change schemas, examples or validation behavior. Future schema changes require explicit versioning and compatibility decisions.

## 10. Progress, discoveries and decision log

### 2026-08-13

- Confirmed public repository as the correct home for reusable academic framing and public-source research.
- Confirmed private repository as the home for case-specific evidence and retained commercial methods.
- Added literature-review protocol, seed annotated bibliography, provisional framing, DSR methodology and standards-review plan.
- Recorded that the Swedish-specific gap is a hypothesis to test, not an established finding.
- Deferred formal data collection and summative evaluation pending enrolment and approval.
