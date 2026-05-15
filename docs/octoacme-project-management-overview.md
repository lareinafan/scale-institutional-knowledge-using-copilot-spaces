# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders: provide inputs and approvals.
- Additional cross-functional personas (engineering management, design/UX, architecture, release operations, support readiness, security/compliance) are defined in [Roles and Personas](./octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Lifecycle handoff checkpoints
- **Initiation -> Planning**
  - Handoff owner: Product Manager + Project Manager
  - Required outputs: approved one-pager, stakeholder list, initial risks, target timeline
- **Planning -> Execution**
  - Handoff owner: Project Manager + Delivery Leads
  - Required outputs: prioritized backlog, Definition of Done, milestone plan, dependency map
- **Execution -> Release**
  - Handoff owner: Project Manager + Release/Operations Coordinator
  - Required outputs: completed acceptance criteria, release notes draft, rollback plan, smoke test scope
- **Release -> Retrospective**
  - Handoff owner: Project Manager + Product Manager
  - Required outputs: release outcome summary, open issues/known risks, metrics snapshot, retrospective date
- **Retrospective -> Next Cycle**
  - Handoff owner: Project Manager
  - Required outputs: prioritized improvement actions with owners and due dates added to backlog/issues

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
