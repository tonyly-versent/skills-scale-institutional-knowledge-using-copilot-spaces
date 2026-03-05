# OctoAcme — Cross-functional RACI & Handoffs Checklist

## Purpose
Provide a concise, actionable reference for who is Responsible, Accountable, Consulted, and Informed (RACI) at each phase of the OctoAcme project lifecycle. Use this checklist to reduce handoff ambiguity, clarify ownership, and ensure nothing falls through the cracks when work moves between roles.

> **Key:** R = Responsible · A = Accountable · C = Consulted · I = Informed
>
> **Roles:** PM = Project Manager · PdM = Product Manager · Dev = Developer · UX = UX/UI Designer · QA = QA Lead · RM = Release Manager · SL = Support Lead · BA = Business Analyst

---

## Phase 1 — Initiation

| Activity | PM | PdM | Dev | UX | QA | RM | SL | BA |
|---|---|---|---|---|---|---|---|---|
| Define problem statement & goals | C | A/R | I | I | I | I | I | R |
| Identify stakeholders & sponsors | A/R | C | I | I | I | I | C | C |
| Draft project one-pager / charter | A/R | C | I | I | I | I | I | C |
| Assess support & operational impact | C | C | I | I | I | I | A/R | I |
| Go / no-go decision for planning | A | C | I | I | I | I | I | C |

### Initiation Handoff Checklist
- [ ] Problem statement agreed and documented
- [ ] Stakeholder list shared with all roles
- [ ] Support Lead briefed on project scope
- [ ] Business Analyst assigned and requirements kick-off scheduled
- [ ] Project one-pager stored in the project repo

---

## Phase 2 — Planning

| Activity | PM | PdM | Dev | UX | QA | RM | SL | BA |
|---|---|---|---|---|---|---|---|---|
| Define scope & acceptance criteria | C | A/R | C | C | C | I | I | R |
| Create release plan & schedule | A/R | C | C | I | C | C | I | I |
| Produce wireframes / design specs | I | C | C | A/R | I | I | I | C |
| Develop test plan & QA approach | C | C | C | I | A/R | C | I | I |
| Identify risks & dependencies | A/R | C | C | C | C | C | C | C |
| Estimate effort & allocate resources | A/R | C | R | C | C | I | I | I |

### Planning Handoff Checklist
- [ ] Acceptance criteria documented for each planned feature
- [ ] UX design specs or wireframes linked in backlog items before development starts
- [ ] QA test plan reviewed and approved
- [ ] Release schedule confirmed with Release Manager
- [ ] Business Analyst has signed off on requirements before sprint begins
- [ ] Risk register updated and shared with all roles

---

## Phase 3 — Execution

| Activity | PM | PdM | Dev | UX | QA | RM | SL | BA |
|---|---|---|---|---|---|---|---|---|
| Implement features to acceptance criteria | I | C | A/R | C | C | I | I | I |
| UI implementation review vs. design | I | I | R | A/R | C | I | I | I |
| Run automated & manual tests | I | I | C | I | A/R | I | I | I |
| Defect triage & resolution | C | C | R | C | A/R | I | I | I |
| Sprint progress tracking & reporting | A/R | I | C | I | C | I | I | I |
| Requirements clarification | C | C | R | C | I | I | I | A/R |

### Execution Handoff Checklist
- [ ] Designs handed off to Developers before sprint start (Figma / design spec link in ticket)
- [ ] QA test cases prepared before feature development completes
- [ ] Defects logged and linked to the relevant tickets
- [ ] Business Analyst available to clarify requirements during the sprint
- [ ] PM notified of any scope or timeline risks as soon as identified

---

## Phase 4 — Release

| Activity | PM | PdM | Dev | UX | QA | RM | SL | BA |
|---|---|---|---|---|---|---|---|---|
| Release readiness review | C | C | C | I | C | A/R | C | I |
| Test sign-off (go/no-go) | C | C | I | I | A/R | C | I | I |
| Deployment execution | I | I | C | I | I | A/R | I | I |
| Post-deploy verification | I | I | R | I | C | A/R | I | I |
| Release communication to stakeholders | C | C | I | I | I | R | C | I |
| Support team briefing & handoff | C | I | I | I | C | R | A/R | I |

### Release Handoff Checklist
- [ ] QA sign-off received before deployment proceeds
- [ ] Rollback plan documented and reviewed by Release Manager and Developers
- [ ] Support Lead has received release notes and support runbook
- [ ] Release Manager has confirmed deployment window with PM
- [ ] Post-deploy smoke tests completed and results shared
- [ ] Stakeholder announcement sent after successful deployment
- [ ] Known issues documented and shared with Support Lead

---

## Phase 5 — Retrospective & Close

| Activity | PM | PdM | Dev | UX | QA | RM | SL | BA |
|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | A/R | C | C | C | C | C | C | C |
| Capture action items | A/R | C | C | C | C | C | C | C |
| Collect customer / support feedback | I | C | I | I | I | I | A/R | C |
| Update process docs | R | C | C | I | C | C | I | I |
| Feed learnings into next planning cycle | C | A/R | C | C | C | C | C | C |

### Retrospective Handoff Checklist
- [ ] Retrospective action items logged and owners assigned
- [ ] Support Lead feedback reviewed by Product Manager
- [ ] Process or documentation improvements actioned before next project starts
- [ ] Learnings shared across relevant teams

---

## General Handoff Principles

1. **Explicit over implicit** — never assume a role knows about a transition. Send a direct notification or tag in the relevant ticket or channel.
2. **Document before handing off** — the handing-off role is responsible for ensuring artefacts (specs, test plans, runbooks, release notes) are complete before passing ownership.
3. **Confirm receipt** — the receiving role acknowledges the handoff and raises any gaps immediately, not at the next ceremony.
4. **Single owner per activity** — every activity should have one Accountable role. Ambiguity in ownership is a process risk; surface it early.

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md) — full descriptions of every role referenced in this checklist
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — detailed release process and deployment checklist
- [Risks & Communication](octoacme-risks-and-communication.md) — risk register and escalation process
- [Project Initiation Guide](octoacme-project-initiation.md) — initiation checklist and one-pager template
