# Contributing to Source Engineering

Source Engineering is an open engineering discipline. Contributions are welcome from anyone willing to engage with the discipline's change process.

## Where to start

- **Read the foundational essays.** They establish the intellectual direction.
- **Read the organisation profile.** The five-layer reference architecture is the visual centrepiece of the discipline.
- **Identify the authoritative repository for the artefact you want to change.** Each repository has one authoritative responsibility.

## The change process

Source Engineering distinguishes three classes of change.

1. **Routine changes** -- bug fixes, documentation, refactors that do not alter the discipline's contracts. Open a pull request against the authoritative repository. The standard PR flow is sufficient.

2. **Specification and architecture changes** -- any change that affects a normative contract, the reference architecture, the COTS spec, or the four-layer stack. File an RFC first. Use the RFC proposal issue template. The RFC is reviewed in the authoritative repository and, once accepted, graduates to a release-candidate.

3. **Foundational changes** -- changes to the discipline's pillars, principles, scope, or non-goals. File an RFC and route it through the governance repository. Foundational changes require a two-week review window.

## Cardinal rules

All contributions must honour the discipline's cardinal rules.

- **No en-dashes (U+2013) or em-dashes (U+2014) in any committed file.** Use ASCII hyphens.
- **No triple-semicolons (;;;) in prose.** The `;;` divider is preserved.
- **Authored by the discipline owner.** No agent identity in any committed surface.
- **No AGENT-DOCTRINE.md or per-repo doctrine file.**
- **No creation-decision narratives in committed files.** Repo READMEs describe the artefact, not the decision to create the repo.

## Conformance and quality

- The discipline's conformance suite is the standard. Implementations and tests evolve against versioned specifications.
- All PRs are reviewed against the discipline's quality gate.
- Proposed work uses the `research-proposal` or `draft-spec` label. Accepted work moves to `release-candidate`, then `stable`. Deprecated work uses the `deprecated` label.

## Channels

- **GitHub Issues** -- bug reports, RFCs, pillar critiques, and discussions.
- **Discord** -- the discipline's Discord channel tracks work via Kanban board 13.
- **GitHub Project** -- the discipline's roadmap lives at https://github.com/orgs/Source-Engineering/projects/1.

## Code of conduct

The discipline follows the source-engineering-governance code of conduct. See [CODE_OF_CONDUCT.md](../source-engineering-governance/blob/main/CODE_OF_CONDUCT.md).
