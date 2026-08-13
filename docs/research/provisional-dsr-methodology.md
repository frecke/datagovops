# Provisional Design Science Research methodology

## Methodological position

Design Science Research (DSR) is the provisional methodology because the intended contribution is a designed and evaluated artifact addressing a relevant information-systems problem. The process follows Peffers et al. while using Hevner et al. to maintain rigor and relevance and Venable et al. to plan evaluation.

This design requires supervisor approval before it becomes the formal thesis method.

## DSR process

### 1. Problem identification and motivation

Establish the practical and academic problem through:

- structured literature review;
- analysis of public open standards;
- analysis of authoritative Swedish public-sector sources;
- anonymized contextual evidence only if approved for formal use.

**Output:** evidence-backed problem statement and delimited research gap.

### 2. Define objectives of a solution

Convert verified needs into measurable design objectives. Candidate objectives include:

- machine readability;
- source and interpretation traceability;
- compatibility with parent standards;
- explicit representation of semantic, accountability and archival-readiness metadata;
- deterministic static validation;
- visible boundaries for non-automatable judgments;
- vendor neutrality and portability.

**Output:** evaluated design-requirements catalogue.

### 3. Design and development

Develop the minimum viable artifact iteratively:

- profile rules and extension strategy;
- YAML and/or JSON Schema;
- controlled vocabularies and reference mechanisms;
- synthetic examples;
- traceability matrix;
- validation tests;
- design-decision records.

**Output:** versioned artifact and design rationale.

### 4. Demonstration

Apply the artifact to one or more synthetic or anonymized scenarios representing a realistic Swedish government-agency context.

Demonstration should show:

- authoring a conforming data-product description;
- detecting defined omissions or invalid representations;
- tracing fields to public sources and design interpretations;
- exporting or mapping selected catalogue metadata where in scope;
- identifying questions the artifact deliberately cannot decide.

**Output:** reproducible demonstration with no customer-identifiable data.

### 5. Evaluation

A feasible Bachelor-level strategy combines artificial and naturalistic elements.

| Evaluation episode | Purpose | Candidate method | Evidence |
|---|---|---|---|
| Schema and fixture tests | Formative and summative | Automated conformance and negative tests | Reproducible test results |
| Requirements coverage | Formative and summative | Traceability and coverage analysis | Requirement-to-artifact matrix |
| Standards compatibility | Formative | Parent-schema validation and mapping review | Compatibility results and exceptions |
| Scenario evaluation | Formative | Application to synthetic or approved anonymized case | Observed fit, gaps and ambiguity |
| Expert review | Primarily summative | Structured review by relevant experts | Ratings, comments and revision log |

Candidate expert perspectives include data governance, enterprise or information architecture, archives/records management and public-sector data-platform engineering. Legal expertise may be needed for legal interpretations but must not be simulated by technical reviewers.

Evaluation properties may include:

- expressiveness;
- traceability;
- internal consistency;
- standards compatibility;
- comprehensibility;
- machine testability;
- usefulness for early governance review;
- explicit treatment of uncertainty and non-automatable judgment.

The evaluation must not claim that reviewers or tests certify legal compliance.

### 6. Communication

Communicate through:

- the academic thesis;
- the public reference artifact and documentation;
- conference or practitioner material that does not overstate findings;
- private delivery methods kept separate from the academic contribution.

## Data and evidence plan

### Can begin before enrolment

- literature searching and bibliographic annotation;
- public-source review;
- provisional requirements mapping;
- synthetic artifact experiments;
- methodological planning and research journal.

### Wait for approval

- recruitment or interviewing of participants;
- collection of expert-evaluation responses;
- processing of personal data;
- formal use of client observations or documents;
- case-organization claims;
- summative evaluation presented as thesis evidence.

## Validity and rigor

Planned safeguards:

- reproducible search log and explicit screening criteria;
- source register with version and verification state;
- separation of source statements, interpretations and design proposals;
- decision records for extensions and mandatory fields;
- positive and negative test fixtures;
- triangulation across literature, authoritative sources and expert review;
- negative-case analysis;
- transparent limitations and alternative explanations;
- versioned artifact and evaluation protocol.

## Feasibility guardrail

The study should evaluate a narrow static artifact. Runtime policy enforcement with OPA/Rego, platform integration and operational control effectiveness are better treated as future Master/Magister work unless the Bachelor scope proves substantially smaller than expected.
