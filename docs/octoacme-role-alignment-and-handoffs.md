# OctoAcme — Role Alignment and Handoff Checklist

## Purpose
Standardize role ownership and cross-role handoffs at project kickoff and before each release milestone.

## When to Use
- During project kickoff (initial role/accountability alignment)
- During major scope changes (reconfirm ownership and dependencies)
- Before release (handoff and readiness confirmation)

## Role Alignment Template (RACI-lite)
Use this table for key project decisions and deliverables.

| Work Item / Decision | PM | PdM | Tech Lead | UX Designer | QA Lead | Release Manager | Support/Ops |
|---|---|---|---|---|---|---|---|
| Project charter and timeline | A | C | C | I | I | I | I |
| Scope and acceptance criteria | C | A | C | C | C | I | I |
| Architecture and integration approach | I | C | A | C | C | I | I |
| Test strategy and quality gates | C | I | C | I | A | C | C |
| Release runbook and deployment plan | C | I | C | I | C | A | C |
| Post-release monitoring and incident follow-up | C | C | C | I | C | C | A |

Legend: **A** = Accountable, **C** = Consulted, **I** = Informed

## Kickoff Alignment Checklist
- [ ] Named owners confirmed for PM, PdM, Tech Lead, QA Lead, and Release Manager (if applicable)
- [ ] Decision ownership (RACI-lite table) agreed and documented
- [ ] Escalation path confirmed (Team -> PM -> Product Lead -> Sponsor)
- [ ] Communication cadence confirmed (standups, weekly syncs, stakeholder updates)
- [ ] Dependency owners identified (internal and cross-team)

## Milestone Handoff Checklist
- [ ] Scope and acceptance criteria are current and approved by PdM
- [ ] Technical approach and implementation risks reviewed by Tech Lead
- [ ] Test strategy and open defect status reviewed by QA Lead
- [ ] Release readiness checks and rollback plan confirmed by Release Manager
- [ ] Monitoring and support readiness confirmed by Support/Ops
- [ ] PM confirms unresolved risks and mitigation owners are tracked
