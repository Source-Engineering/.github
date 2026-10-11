# Source Engineering

> An engineering discipline for grounding AI-based decisions with integrity.

## The discipline

Source Engineering treats model reasoning as evidence-anchored, not merely produced. It exists to close the hesitation factor in high-stakes AI decisions by making every response auditable end-to-end.

The discipline is grounded in two essays:

- [Source Engineering: Grounding AI-based Decisions with Integrity (December 2025)](https://nuel.otchere.com/posts/2025/12/source-engineering-grounding-ai-based-decisions-with-integrity.html)
- [Reframing the Five Pillars, One Year Later (October 2026)](https://nuel.otchere.com/posts/2026/10/reframing-the-five-pillars-one-year-later.html)

## The four-layer stack

The 2026 reframing composes the five pillars of the 2025 essay into a shippable stack:

```
+--------------------------------------------------+
|  Layer 4  --  Audit Trail                          |
|  (who saw what, when, and with what evidence)     |
+--------------------------------------------------+
|  Layer 3  --  Business Guardrails                  |
|  (policy, compliance, jurisdictional rules)       |
+--------------------------------------------------+
|  Layer 2  --  Runtime Validation                   |
|  (calibration, drift, segment-aware signals)      |
+--------------------------------------------------+
|  Layer 1  --  Typed Model                          |
|  (typed questions, declared answer shapes,        |
|   calibrated probabilities)                       |
+--------------------------------------------------+
```

## The COTS contract

Every Source Engineering response carries a **Chain of Orchestrable and Traceable Sources (COTS)**: a structured bundle of inputs, context, decisions, evidence, and validation. The COTS is the unit of accountability.

## Organisation

The discipline's repositories are scoped by artefact ownership. One authoritative home per artefact; everything else is a link.

| Repo | Owns |
|---|---|
| [source-engineering](https://github.com/Source-Engineering/source-engineering) | Public introduction, navigation, org-level portal |
| [source-engineering-foundations](https://github.com/Source-Engineering/source-engineering-foundations) | Discipline definition, principles, terminology, scope and non-goals |
| [source-engineering-governance](https://github.com/Source-Engineering/source-engineering-governance) | Change process, ADRs, RFCs, maintainer responsibilities, release policy |
| [source-engineering-research](https://github.com/Source-Engineering/source-engineering-research) | Research agenda, hypotheses, experimental protocols, evaluation reports |
| [source-engineering-model](https://github.com/Source-Engineering/source-engineering-model) | Canonical conceptual and data model |
| [source-engineering-specifications](https://github.com/Source-Engineering/source-engineering-specifications) | Normative technical requirements. COTS spec lives under `specifications/cots/` |
| [source-engineering-architecture](https://github.com/Source-Engineering/source-engineering-architecture) | Reference architecture, blueprint stack, per-layer interface contracts |
| [source-engineering-reference-implementation](https://github.com/Source-Engineering/source-engineering-reference-implementation) | Working reference code that demonstrates the spec in action |
| [source-engineering-conformance](https://github.com/Source-Engineering/source-engineering-conformance) | Conformance test suite, validation harness, badge system |
| [source-engineering-tools](https://github.com/Source-Engineering/source-engineering-tools) | Reusable software utilities: CLI, visualizer, model-card-gen, SDKs |
| [source-engineering-case-studies](https://github.com/Source-Engineering/source-engineering-case-studies) | Evaluated demonstrations, case studies |
| [source-engineering-practice](https://github.com/Source-Engineering/source-engineering-practice) | Practitioner guidance, implementation guides |
| [source-engineering-education](https://github.com/Source-Engineering/source-engineering-education) | Curriculum and learning resources |

## How to engage

- **Read the foundations first.** Start at [source-engineering-foundations](https://github.com/Source-Engineering/source-engineering-foundations) for the discipline's intellectual home.
- **Track the work.** The discipline is tracked on a public GitHub Project. Follow the relevant repo's project board to see in-flight work.
- **Propose changes.** Use the RFC process in [source-engineering-governance](https://github.com/Source-Engineering/source-engineering-governance). Foundational changes require a change proposal; routine changes follow the standard PR flow.

## Licence

Apache-2.0 across the discipline. See [LICENSE](LICENSE).
