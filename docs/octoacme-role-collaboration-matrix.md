# OctoAcme Role Collaboration Matrix

This document maps key project lifecycle activities to team roles using a RACI-style framework.

---

## How to use this matrix

- **R – Responsible**: The role(s) doing the work for this activity.
- **A – Accountable**: The single role ultimately answerable for the outcome (the decision-maker / sign-off owner).
- **C – Consulted**: Roles whose input is sought before or during the activity (two-way communication).
- **I – Informed**: Roles kept up to date on progress or outcomes (one-way communication).

> When a cell is blank, the role has no formal involvement in that activity.

Use this matrix when onboarding new team members, planning a project kick-off, or clarifying ownership during a retrospective.

---

## Lifecycle Activity Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | Security Lead | Business Analyst | Stakeholders |
|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | |
| Define problem statement | C | A/R | I | C | C | C | C |
| Identify stakeholders | A/R | C | I | I | I | C | I |
| Draft project charter | A/R | C | I | I | I | C | I |
| **Planning** | | | | | | | |
| Prioritize backlog | C | A/R | C | C | C | R | I |
| Define acceptance criteria | C | A | C | C | C | R | C |
| Create project plan & timeline | A/R | C | C | C | C | C | I |
| Schedule design & security reviews | A/R | C | I | C | C | I | I |
| **Execution** | | | | | | | |
| Implement features | I | C | A/R | C | C | C | I |
| UX design & prototype review | C | C | C | A/R | I | I | I |
| Security threat modeling | C | C | C | C | A/R | I | I |
| Requirements clarification | C | C | C | I | I | A/R | C |
| Code & design review | C | I | A/R | C | C | I | I |
| **Release** | | | | | | | |
| Release readiness review | A/R | C | C | C | C | C | I |
| Security sign-off | C | C | I | I | A/R | I | I |
| UX sign-off | C | C | I | A/R | I | I | I |
| Deploy & verify | C | C | A/R | I | C | I | I |
| Release announcement | C | A/R | I | I | I | I | I |
| **Retrospective** | | | | | | | |
| Facilitate retrospective | A/R | C | C | C | C | C | I |
| Capture learnings & action items | A/R | C | C | C | C | C | I |
| Update process documentation | C | C | C | C | C | C | I |

---

## Related Documents

- [Roles and Personas](./octoacme-roles-and-personas.md) – Full role descriptions and interaction patterns.
- [Cross-Functional Handoff Checklist](./octoacme-cross-functional-handoff-checklist.md) – Readiness criteria at key handoff points.
- [Project Management Overview](./octoacme-project-management-overview.md) – High-level lifecycle and principles.
