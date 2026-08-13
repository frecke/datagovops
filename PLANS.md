# ExecPlans

Use an ExecPlan for work that spans multiple concerns, is likely to take more than an hour, changes public semantics or
requires coordinated source, schema, example and test updates.

An ExecPlan is a living document. Keep it understandable without chat history.

## Required sections

1. Purpose and user-visible outcome
2. Scope and explicit exclusions
3. Facts, assumptions and questions to verify
4. Authoritative sources and versions
5. Public/private and confidentiality assessment
6. Design decisions and alternatives
7. Implementation milestones
8. Validation and evaluation plan
9. Compatibility and migration impact
10. Progress, discoveries and decision log

Store active plans under `.agents/plans/` using `YYYY-MM-DD-short-name.md`. Remove no decision history when updating
a plan; mark superseded decisions explicitly.
