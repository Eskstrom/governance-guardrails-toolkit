# Governance Guardrails Toolkit

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=tools-play#library)

## Product brief

A lightweight launch-readiness tool for AI features. Teams answer questions about data sensitivity, human oversight, auditability, model risk, and affected users; the tool returns required controls and open launch gates.

## Design focus

Connect AI launch risks to specific controls and evidence requirements.

## Proposed scope

- Assessment questionnaire for a proposed AI feature.
- Rule-based guardrail recommendations.
- Launch checklist and evidence tracker.
- Decision log recording approver, rationale, and unresolved risks.

## Validation targets

- A reviewer can see why each control is required.
- The demo includes low-, medium-, and high-risk use cases.

## Potential implementation

Next.js, TypeScript, SQLite/Supabase.

## Guardrails

State that the app is educational and not legal or regulatory advice.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Recommend consolidation before further standalone development.

Preserve launch gates, control rationale and evidence requirements within Enterprise LLM Model Hub or AI Deployment Command Center.

### Next scope

- [ ] Inventory unique requirements and planning notes before moving anything.
- [ ] Use Enterprise LLM Model Hub or AI Deployment Command Center as the proposed destination; record the destination and retained source history after an actual migration.
- [ ] Update incoming portfolio links before considering archive status. No consolidation or archival is implied by this planning note.

### Validation and decision criteria

Trace each required control to a specific risk and an accountable decision owner. Reopen a standalone PRD only if user discovery establishes a distinct problem that the retained project cannot cover.
<!-- portfolio-future-plans:end -->
