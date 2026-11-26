# Agent instructions

This repository is a public, independent engineering portfolio project. These instructions apply to all work in this repository.

## Engineering decisions

- Human-led engineering: a human owner defines goals, scope, acceptance criteria, and final decisions.
- AI-assisted implementation is permitted only within the stated task scope. AI output is a proposal, not evidence of correctness.
- State explicit acceptance criteria before implementing a change. Keep changes traceable to those criteria.
- Validate with reproducible evidence. Record commands, observed results, and limitations; never fabricate test results or claim checks that were not run.
- Use test-driven verification where applicable: identify expected behavior, add or update meaningful tests, and run them before requesting review.
- Require independent human review of AI-generated changes, including security, provenance, and correctness. The authoring assistant cannot approve its own work.
- Never merge without explicit human authorization.

## Security and independence

- Never access, copy, or reuse proprietary RQS Studio source code or the the private commercial RQS workspace directory for this project.
- Never use production credentials, real customer data, or commercial RQS infrastructure. Do not make production connections.
- Use synthetic datasets and independent implementations. Confirm that external assets and dependencies may be redistributed before adding them.
- Keep environment files, credentials, dependencies, and generated artifacts out of Git. Scan proposed changes for secret exposure before submission.
- Do not introduce a license or claim third-party program eligibility without verified requirements and explicit owner authorization.

## Gate decision

For every proposed change, report one decision with evidence:

- **PASS:** acceptance criteria are met, applicable checks pass, the security scan is clear, and human review is ready.
- **HOLD:** evidence, authorization, or a required check is missing; identify the blocker and next action.
- **FAIL:** a confirmed security boundary violation or failed acceptance criterion remains unresolved.

A PASS assessment does not authorize merge. Only the human owner may authorize merging.

## Technical isolation

Repository instructions do not constitute filesystem, network, or credential isolation. External agents must receive only the permissions required for this repository.
