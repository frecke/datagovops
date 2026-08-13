# Standards and authority review plan

## Objective

Determine what ODCS, ODPS and DCAT-AP-SE already represent, where a Swedish public-sector profile may be justified, and which governance questions cannot safely be reduced to schema fields or static validation.

## Evidence order

1. Binding Swedish legislation and applicable regulations.
2. Official specifications and release artifacts.
3. Authoritative guidance from DIGG, Riksarkivet and eSam.
4. Peer-reviewed research.
5. Contextual practitioner material, explicitly labelled as such.

## Review matrix

| Source family | Review focus | Expected output | Key caution |
|---|---|---|---|
| ODCS | Contract terms, schema, quality, service levels, roles, extensions and references | Field inventory and extension assessment | Do not rely on release announcements for field semantics |
| ODPS | Product identity, ownership, lifecycle, ports/interfaces, contracts and custom properties | Product-level coverage map | Confirm exact released schema and compatibility rules |
| DCAT-AP-SE | Dataset, distribution, data service, provenance and Swedish catalogue obligations | Publication crosswalk | Catalogue metadata is not complete governance metadata |
| DIGG | Interoperability, information publication and shared/open data guidance | Objectives and candidate evaluation criteria | Guidance is not automatically binding |
| eSam | Agency data-management capabilities and digital preservation problem framing | Capability and problem map | Strategic reports do not create legal obligations |
| Riksarkivet and RA-FS | Electronic records, documentation, preservation, disposition and archival accountability | Applicability-qualified requirements | Verify current consolidated wording and scope |
| Arkivlag and related law | Binding archival purpose and responsibilities | Legal context and questions for qualified review | Do not encode legal conclusions without analysis |

## Field-analysis questions

For every candidate concept:

1. Is it explicitly represented in an existing standard?
2. Is its meaning equivalent, narrower or broader?
3. Can an external identifier or controlled vocabulary solve the need?
4. Is a profile rule sufficient, or is an extension necessary?
5. Is the concept Swedish, organization-specific or broadly reusable?
6. Is it factual metadata, a decision, an assertion, an obligation or evidence?
7. Can it be statically validated?
8. What authority and competence are required to make the value trustworthy?
9. What version, validity period and provenance must be recorded?
10. Does machine representation improve review without implying automated compliance?

## Candidate concern catalogue

The review should inspect, without presuming inclusion:

- information owner and accountable roles;
- system of record;
- public-document or records classification;
- archival status;
- retention and disposition references;
- preservation responsibility and format;
- exportability and long-term accessibility;
- authenticity and integrity assertions and evidence;
- lineage and provenance;
- version and change history;
- documentation requirements;
- arkivredovisning or classification-structure references;
- semantic definitions and controlled vocabularies;
- permitted purposes, authority, validity and evidence for use decisions.

## Deliverables

- version-pinned source register;
- source-to-requirement traceability matrix;
- ODCS/ODPS/DCAT-AP-SE coverage comparison;
- extension decision log;
- list of non-automatable judgments;
- prioritized minimum viable profile.

## Initial status, 2026-08-13

The repository identifies ODCS 3.1.0, ODPS 1.0.0 and DCAT-AP-SE 3.0.1 as current working baselines. Their exact release schemas and field semantics still require systematic, field-level review. Living DIGG, eSam and Riksarkivet material must be re-verified when used for firm claims.
