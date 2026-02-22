# OctoAcme Cross-Functional Handoff Checklist

Use this checklist to confirm team readiness before handing off work between key lifecycle phases. Each section should be reviewed by the relevant role before the handoff is considered complete.

---

## Design Readiness (UX → Development)

Before UX hands off designs to the development team, confirm:

- [ ] All screens/flows in scope have finalized, annotated designs (e.g., in Figma or equivalent).
- [ ] Interactive prototype reviewed with Product Manager and key stakeholders.
- [ ] Accessibility requirements documented (WCAG level, color contrast, keyboard navigation).
- [ ] Edge cases and error states are designed and included.
- [ ] Component mapping to design system is complete; any new components are flagged.
- [ ] Open design questions are resolved or tracked in the backlog with agreed-upon owners.
- [ ] Developer walkthrough session scheduled or completed.

---

## Security Readiness (Security Lead → Development / Release)

Before development begins work on a security-sensitive feature, and again before release, confirm:

- [ ] Threat model for the feature/change has been completed or updated.
- [ ] Security acceptance criteria are documented and linked to relevant stories.
- [ ] Authentication and authorization requirements are specified.
- [ ] Data handling requirements (encryption, retention, PII) are documented.
- [ ] Known vulnerabilities or dependencies flagged for review are tracked.
- [ ] Security review of designs completed (for features with significant security impact).
- [ ] Pre-release security sign-off completed and recorded.

---

## Requirements Readiness (Business Analyst → Development)

Before development begins a sprint, confirm:

- [ ] User stories are written with clear acceptance criteria (Given/When/Then or equivalent).
- [ ] Business context and rationale for each story are documented.
- [ ] All dependencies (upstream/downstream) are identified and communicated.
- [ ] Stakeholder sign-off on requirements obtained (document who approved and when).
- [ ] Out-of-scope items are explicitly stated to prevent scope creep.
- [ ] Open requirements questions are resolved or have a named owner and target date.
- [ ] Stories are sized and reviewed with the development team.

---

## Release Readiness (Cross-functional)

Before release, confirm all functional areas have signed off:

- [ ] UX: Final UI reviewed against approved designs; accessibility spot-checked.
- [ ] Security: Security sign-off completed; no unresolved critical/high vulnerabilities.
- [ ] BA: Acceptance criteria verified; stakeholder demo completed if required.
- [ ] QA/Testing: All acceptance criteria validated; regression suite passed.
- [ ] Project Manager: Release plan, communication, and rollback plan in place.
- [ ] Product Manager: Release announcement drafted; metrics tracking confirmed.

---

## Related Documents

- [Roles and Personas](./octoacme-roles-and-personas.md) – Full role descriptions and interaction patterns.
- [Role Collaboration Matrix](./octoacme-role-collaboration-matrix.md) – RACI overview across lifecycle phases.
- [Project Management Overview](./octoacme-project-management-overview.md) – High-level lifecycle and principles.
