# OctoAcme Project Management Docs

## Overview
OctoAcme uses a customer-first, iterative, and data-informed approach to project delivery. Our core principles—clear ownership, small shippable increments, risk-aware decision making, and regular stakeholder communication—help teams deliver predictable, measurable outcomes while minimizing single-person dependencies.

These docs are the canonical, living source for our project management processes. They are intended to:
- Accelerate onboarding by providing easy access to core processes and templates.
- Reduce knowledge fragmentation by centralizing decision rationale and artifacts.
- Enable consistent, repeatable project execution across teams.
- Feed validated improvements back into documentation via collaborative updates.

## Project management processes (brief)
- Initiation: Create a Project One-pager to capture the problem, goals, measurable success criteria, stakeholders, and initial risks. Use the Project Initiation Guide when deciding whether to proceed to planning.
- Planning: Run a kickoff, break work into shippable backlog items with acceptance criteria, estimate scope, define Definition of Done, and capture dependencies and risks in the Risk Register.
- Execution & Tracking: Work in small increments, follow branching and PR conventions, run CI and tests, use the project board to track flow from Backlog → Done, and surface blockers through daily standups and weekly delivery syncs.
- Risk Management & Communication: Maintain a simple, reviewed Risk Register; follow stakeholder-specific communication templates; escalate via defined paths when needed.
- Release & Deployment: Meet pre-release requirements (tests, security scans, release notes), run staged deployments with smoke checks, and have rollback/playbook steps for incidents.
- Retrospective & Continuous Improvement: Run timeboxed retrospectives after sprints/releases, create prioritized action items, and track improvements in the backlog.

## Key docs in this folder
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## How to use these docs
- Link or copy the relevant templates (e.g., Project One-pager, release notes template) into your project repo.
- Keep the project README current with status and links to artifacts (one-pager, risk register, release notes).
- Propose doc changes via the repository process (use the "Add Content to Project Management Process Docs" issue template).
- For Copilot Spaces context, add process-specific artifacts into `.copilot/` if you want them available as Space context.

## Quick check (starter)
- [ ] One-pager exists and is linked from the project README
- [ ] Risk Register initialized and assigned
- [ ] Backlog has prioritized items with acceptance criteria
- [ ] CI and PR conventions are documented in the repo

For detailed guidance see each document above or contact the Project Manager / Product Lead.