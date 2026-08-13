# ADR 0002: Separate semantic, contract and snapshot version identities

- Status: proposed
- Date: 2026-08-13

## Context

An information product can retain its governed meaning while a technical
interface changes. Conversely, meaning can change without producing a new data
snapshot. Using one version field for all three changes would make compatibility,
provenance and reproducibility ambiguous.

## Decision

The experimental model uses separate identities for:

1. the semantic version of an information product;
2. the version of each data contract or interface;
3. the identity of a dataset release or reproducible snapshot.

This ADR does not yet prescribe one universal syntax for contract or snapshot
identifiers. References must be stable identifiers; exact mappings to ODPS, ODCS,
DCAT-AP-SE and provenance standards remain to be evaluated.

## Consequences

- Compatibility decisions can name the layer that changed.
- A reproducible snapshot need not imply a semantic or interface change.
- Implementations must maintain explicit links among the three identities.
- Cross-artifact consistency requires validation beyond a single JSON Schema.
- Migration rules and mapping profiles remain future work.

## Alternatives considered

### One version for the whole product

Rejected as the default hypothesis because it conflates meaning, interface and
data-state changes.

### Encode all identities in one compound version

Not selected because it couples independent lifecycles and makes compatibility
rules harder to reason about.

