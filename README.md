<!-- OctoAcme Project Management Docs README -->
# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains the core project management processes, templates, and checklists we use to plan, execute, and continuously improve cross-functional projects. The goal is to make project practices discoverable, repeatable, and easy to use for both new and existing team members.

OctoAcme follows an iterative, outcome-oriented approach. Projects move through initiation (problem definition and a Project One‑pager), planning (backlog, estimates, milestones), execution (short, testable increments with PR and CI gates), release (validated deployment and post‑deploy verification), and close (retrospective and continuous improvement). We emphasize clear ownership (named Project Manager and Product Lead), incremental delivery, and data‑informed decisions.

Core roles include Project Managers (coordinate delivery and risk), Product Managers (own outcomes and prioritization), Developers (implement and test), QA/Testing (validate acceptance), and Stakeholders (provide approvals and context). Our communication cadence combines daily standups for the delivery team, weekly PM+PdM syncs, milestone demos, and monthly stakeholder updates. Escalation follows team → PM → Product Lead → Sponsor as needed.

Quality practices combine automated testing and security scanning in CI, small pull requests with required reviews, explicit acceptance criteria and a Definition of Done (DoD), manual QA when necessary, and post‑release verification. We keep a living Risk Register and run retrospectives after major milestones to convert learnings into backlog action items.

## Docs Directory Index
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

Refer to each linked doc for detailed steps, checklists, templates, and examples.

## How to use these docs
- Start at the Project Management Overview for a high‑level view.
- For a new project, follow the Project Initiation Guide and create the Project One‑pager.
- During planning use the Project Planning doc to build a prioritized backlog and release plan.
- During execution follow the Execution & Tracking conventions (PRs, CI, standups, metrics).
- Maintain the Risk Register and use the Risks & Communication doc for stakeholder updates.
- Use the Release & Deployment checklist for releases and run a Retrospective after milestones.

## Contributing & change process
- Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ to propose changes.
- Create a branch named docs/<short-description>, add or update files under docs/, and open a pull request.
- In your PR description reference the related issue (for example "Addresses #2") so the PR is linked to the originating request.
- Request at least one reviewer and ensure CI checks pass before merging.

## Acceptance checklist for docs PRs
- [ ] Links to all docs in docs/ are present and valid
- [ ] README contains a concise summary of processes, roles, communication, and quality practices
- [ ] PR references the related issue and requests reviewers (e.g., @dvparth)
- [ ] CI checks (if applicable) pass

If something in these docs conflicts with team practice, open an issue or PR to propose a correction — these are living documents intended to evolve with the team.
```
