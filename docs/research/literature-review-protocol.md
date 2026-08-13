# Literature review protocol

## Status and purpose

This is a provisional protocol for a structured, reproducible literature review. It is intended to establish the academic problem and research gap before the thesis design is finalized. It is not yet a completed systematic review and must not be reported as one.

## Review objective

Identify and synthesize research relevant to machine-readable, automatable and auditable governance of data products in public-sector settings, with particular attention to semantic interoperability, metadata, data contracts, lifecycle governance, records management and archival readiness.

## Candidate review questions

1. How has research represented and operationalized data-governance requirements in machine-readable artifacts?
2. What roles do metadata, data contracts, data-product specifications and application profiles play in automated governance?
3. How are semantic interoperability, provenance, records management and preservation requirements integrated with data-product governance?
4. Which artifact-design and evaluation approaches have been used for comparable information-systems problems?
5. What evidence exists for a gap at the intersection of open data-product standards and Swedish public-sector information and archival governance?

## Source families

### Peer-reviewed literature

Search at minimum:

- Scopus and Web of Science, subject to university access;
- AIS eLibrary;
- ACM Digital Library;
- IEEE Xplore;
- SpringerLink and relevant publisher indexes;
- Google Scholar and Consensus for discovery and citation chaining, not as the sole evidence base.

### Authoritative and normative sources

Review separately from peer-reviewed literature:

- Bitol ODCS and ODPS specifications, schemas, releases and RFCs;
- W3C DCAT and SEMIC DCAT-AP;
- DCAT-AP-SE and relevant DIGG guidance;
- eSam publications;
- Swedish legislation;
- Riksarkivet regulations and guidance, including applicable RA-FS.

Authoritative-source review and academic literature review answer different questions and must not be collapsed into one evidence class.

## Search concepts

| Concept | Indicative English terms | Indicative Swedish terms |
|---|---|---|
| Governance automation | "automated data governance", "computational governance", "policy as code", "metadata driven governance" | automatiserad datastyrning, maskinläsbar styrning |
| Data artifacts | "data contract", "data product specification", "data product", "metadata as code", "schema governance" | datakontrakt, dataprodukt, metadata som kod |
| Public sector | government, "public administration", "public sector", "open government data" | myndighet, offentlig förvaltning, öppna data |
| Interoperability | "semantic interoperability", "application profile", ontology, provenance | semantisk interoperabilitet, tillämpningsprofil, spårbarhet |
| Records and archives | "records management", archival, preservation, retention, disposition, authenticity, integrity | arkiv, bevarande, gallring, autenticitet, integritet |
| Method | "design science research", artifact, evaluation, schema, reference model | designvetenskap, artefakt, utvärdering, referensmodell |

## Initial query blocks

Queries must be adapted to each database syntax and logged verbatim.

1. (`"data governance"` AND (automat* OR operationali* OR executable OR `"policy as code"` OR `"metadata driven"`))
2. ((`"data contract*"` OR `"data product* specification"` OR `"metadata as code"`) AND govern*)
3. ((government OR `"public sector"` OR `"public administration"`) AND `"semantic interoperability"` AND metadata)
4. ((`"data product*"` OR `"open government data"`) AND (`"records management"` OR archival OR preservation OR retention OR disposition))
5. ((`"design science research"` OR DSR) AND (metadata OR governance OR interoperability) AND (artifact OR schema OR `"reference model"`))

## Inclusion criteria

Include sources that:

- address at least two core concepts in the review objective;
- contribute a model, method, empirical finding, review or evaluated artifact;
- provide traceable bibliographic identity;
- are in English or Swedish;
- are peer reviewed, or are a seminal scholarly work whose status is recorded;
- are sufficiently detailed to assess relevance and limitations.

No publication-year floor is imposed on seminal work. For fast-moving technical topics, emphasize 2018 onward while retaining earlier foundations.

## Exclusion criteria

Exclude sources that:

- only provide vendor marketing without a research contribution;
- use governance merely as a synonym for management with no decision-rights, accountability or control content;
- discuss data quality alone without relevance to the wider research question;
- lack sufficient source identity;
- are duplicates, short summaries of another included work or inaccessible beyond an uninformative snippet.

## Screening process

1. Deduplicate results.
2. Screen titles and abstracts against the criteria.
3. Record inclusion, exclusion and reason.
4. Retrieve and inspect full text where available.
5. Perform backward and forward citation chaining on pivotal sources.
6. Extract evidence into a structured matrix.
7. Re-run core searches before thesis submission.

A second reviewer or supervisor should review a sample of screening decisions if feasible.

## Extraction fields

- bibliographic identity and DOI;
- source type and peer-review status;
- problem and context;
- construct definitions;
- artifact or intervention;
- method and data;
- evaluation approach;
- findings;
- limitations;
- relevance to DataGovOps;
- relevance to Swedish public administration;
- archival or records-management coverage;
- candidate requirements;
- contradictions and follow-up citations.

## Synthesis strategy

Use thematic synthesis across six deliberately separate concerns:

1. data quality;
2. metadata quality;
3. semantic interoperability;
4. legal and regulatory compliance;
5. archival compliance and preservation readiness;
6. operational platform governance.

Map each theme to the practical problem, candidate artifact capabilities and available evaluation evidence. Absence from the reviewed literature may motivate a research gap only after search coverage and screening are documented.

## Search log template

| Date | Database | Exact query | Filters | Results | Screened | Included | Notes |
|---|---|---|---:|---:|---:|---:|---|
| 2026-08-13 | Consensus | Initial exploratory queries across DSR, governance automation, data contracts, interoperability and records management | Discovery search | Not used as final corpus count | Partial | Seed sources only | Full database searches pending |

## Limitations of the current inception search

The initial search used Consensus for rapid discovery and fetched selected paper records. It is not exhaustive, does not replace database searches through university access, and is vulnerable to ranking and coverage effects. The definitive review corpus, flow counts and exclusion log remain future work.
