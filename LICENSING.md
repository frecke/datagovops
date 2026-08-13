# Licensing strategy

This repository deliberately uses two licenses because software-like artifacts and explanatory works have different
reuse patterns.

| Material | License |
|---|---|
| Code, JSON Schemas, validation scripts and executable examples | Apache License 2.0 |
| Documentation, diagrams and explanatory reference material | Creative Commons Attribution 4.0 |
| Third-party material | Its original license |
| Private methods and customer material | Not part of this repository |

## Why Apache License 2.0

Apache-2.0 is a permissive open-source license designed for software and software-like artifacts. It allows use,
modification, distribution and commercial adoption without requiring derivative works to use the same license.

It fits the public DataGovOps model because:

- authorities, vendors and open-source projects can implement the schemas without copyleft uncertainty;
- commercial adoption is explicitly allowed, which supports ecosystem uptake rather than blocking it;
- contributions include an explicit patent grant for claims necessarily infringed by the contribution;
- copyright and attribution notices must be preserved;
- modified works must identify significant changes;
- warranty and liability are disclaimed;
- the SPDX identifier `Apache-2.0` is widely recognized by automated compliance tooling.

The patent language is the main reason to prefer Apache-2.0 over a very short permissive license such as MIT for a
standards-adjacent technical ecosystem.

## Why CC BY 4.0

CC-BY-4.0 is designed for prose, diagrams, teaching material and other copyrightable documentation. It allows copying,
translation, adaptation and commercial reuse as long as attribution is provided and changes are indicated.

It fits the public documentation because:

- conference, academic, public-sector and vendor communities can quote, translate and adapt the material;
- attribution preserves authorship and supports Fredrik's public thought-leadership objective;
- it avoids a non-commercial restriction that would create ambiguity for consultants, vendors and training providers;
- it avoids ShareAlike obligations that could make integration into mixed-license documentation harder;
- it aligns with the license used by DCAT-AP-SE documentation, reducing friction when referencing licensed material;
- the SPDX identifier `CC-BY-4.0` is machine-readable and internationally recognized.

CC licenses are not the preferred tool for software, which is why code and schemas use Apache-2.0 instead.

## What these licenses do not do

Open licenses do not preserve exclusivity over material once it has been published under them. A recipient who complies
with the license may continue using that published version. The commercial protection therefore comes from deciding
what enters the public repository, not from trying to claw it back later.

The public repository should expose models, standards profiles and selected reference implementations. Detailed
assessment methods, scoring, customer mappings, playbooks and accelerators remain private.

In short: **publish the model, retain the method**.

## Contributions

Unless agreed otherwise, contributions are accepted under the license that applies to the destination file. Contributors
must have the right to submit the material. Copying third-party content into this repository does not relicense it.

## Attribution

A reasonable documentation attribution is:

> DataGovOps reference work by Fredrik, licensed under CC BY 4.0. Source:
> https://github.com/frecke/datagovops. Changes were made.

This document explains project intent and is not legal advice.
