# Reference index

This directory is the source catalogue for DataGovOps design work. It records what a source is and why it matters.
Derived requirements and profile decisions belong in traceability artifacts, not in the source entry itself.

## Structure

- `source-register.yaml`: machine-readable source identity, authority, version, status and relevance
- `swedish-public-sector.md`: Swedish legislation, Riksarkivet, DIGG and eSam
- `open-standards.md`: ODCS, ODPS, DCAT, DCAT-AP and DCAT-AP-SE
- `research-method.md`: Design Science Research foundations
- `traceability-template.md`: template connecting a source to a requirement and artifact decision

## Source classes

| Class | Meaning |
|---|---|
| Legislation | Binding law in its applicable scope |
| Regulation | Binding regulation in its applicable scope |
| Official guidance | Authoritative guidance, but not automatically a legal obligation |
| Standard | Normative or consensus specification with an identified version |
| Research | Peer-reviewed or otherwise academically traceable work |
| Context | Material that motivates or explains without establishing a requirement |

## Required metadata

Every registered source must include:

- stable identifier;
- exact title and issuer;
- version or publication date;
- canonical URL or DOI;
- access date;
- source class and normative status;
- maturity or lifecycle status when relevant;
- relevance to the artifact;
- explicit limitations or applicability questions.

## Verification states

- `verified`: the source itself was opened and its identity checked;
- `candidate`: relevant but not yet inspected closely enough for derived claims;
- `superseded`: retained for historical traceability with a replacement link;
- `withdrawn`: no longer valid as an active source.

Verification confirms source identity. It does not mean every interpretation or derived requirement is correct.

## Rules

1. Prefer primary and authoritative sources.
2. Pin exact versions for standards and regulations.
3. Re-check living guidance before making firm claims.
4. Keep legislation, regulation, guidance and design interpretation distinct.
5. For RA-FS, verify current wording, scope and applicability to the case organization.
6. Do not copy substantial copyrighted text when a citation and summary are sufficient.
7. Never turn a source into a required schema field without documented reasoning and evaluation.
