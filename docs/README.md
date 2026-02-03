# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a customer-first, iterative, and data-informed approach to project delivery. Our core principles—clear ownership, small shippable increments, risk-aware decision making, and regular stakeholder communication—help teams deliver predictable, measurable outcomes while minimizing single-person dependencies. These docs serve as the canonical, living source for our project management processes, designed to accelerate onboarding, reduce knowledge fragmentation, enable consistent project execution, and feed validated improvements back into documentation through collaborative updates.

**Key Workflows:** OctoAcme projects follow a structured lifecycle from **initiation** (creating a Project One-pager with problem statement, goals, success metrics, stakeholders, and initial risks) through **planning** (running kickoff meetings, breaking work into shippable backlog items with acceptance criteria, estimating scope, defining Definition of Done, and capturing dependencies in the Risk Register). During **execution and tracking**, teams work in small increments following branching and PR conventions, running CI and tests, using project boards to track flow from Backlog → In Progress → In Review → QA → Done, and surfacing blockers through daily standups and weekly delivery syncs. The **release and deployment** phase ensures all pre-release requirements are met (passing tests, security scans, release notes), staged deployments with smoke checks are executed, and rollback playbooks are ready for incidents. Finally, **retrospective and continuous improvement** sessions after sprints or releases capture learnings, create prioritized action items, and track improvements in the backlog.

**Personas and Roles:** OctoAcme projects involve clearly defined roles with distinct responsibilities. **Project Managers (PM)** coordinate delivery activities, manage schedules, risks, dependencies, and communications, facilitating meetings like kickoffs, planning sessions, and retrospectives while ensuring consistent documentation and status reporting. **Product Managers (PdM)** define what should be built to deliver customer and business value, owning the product vision, prioritizing the roadmap and backlog, collaborating on trade-offs, and validating solutions through user research and metrics. **Developers** design, build, test, and deliver software components, implementing features that meet acceptance criteria, writing tests and documentation, participating in design and code reviews, and helping identify technical risks. **QA/Testing** validates quality and acceptance criteria, ensuring features meet standards before release. **Stakeholders** provide inputs, approvals, and receive regular updates on project progress and outcomes.

**Communication Strategies and Quality Assurance:** Communication follows structured cadences including daily standups (15-minute focus on progress, blockers, dependencies), twice-weekly delivery team syncs, weekly PM-PdM alignment meetings, monthly stakeholder updates, and ad-hoc escalations as needed. Teams maintain a single source of truth through project READMEs and release docs, use weekly status templates (progress, next steps, risks/blockers, decisions needed), and follow defined escalation paths (team-level → PM → Product Lead → Sponsor). Quality assurance is built into every stage through comprehensive PR workflows requiring small PRs (≤400 lines when possible) with linked issues and acceptance criteria, automated CI tests and linting before review, and at least one approval before merging. Testing includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and continuous security scanning in CI. Release checklists ensure all acceptance criteria are met, passing CI and security scans are verified, release notes are drafted, rollback plans are documented, and staged deployments with smoke tests and post-deploy verifications are completed before announcing to stakeholders.

## Docs Reference

Detailed guidance for each phase of the OctoAcme project management process:

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles, roles, artifacts, lifecycle, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, create Project One-pager, align stakeholders, define success criteria and timeline
- [Project Planning](octoacme-project-planning.md) — Run kickoff, create prioritized backlog with acceptance criteria, estimate scope, define Definition of Done, identify dependencies and risks
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, PR workflow, quality and testing practices, reporting metrics, blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Maintain Risk Register, stakeholder communication templates, escalation paths, incident communication
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback and incident playbook, release notes template
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, run retrospectives, create action items, track improvements
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed definitions of Developer, Product Manager, Project Manager roles with responsibilities, goals, and typical communication patterns

## How to Use These Docs

- Link or copy relevant templates (e.g., Project One-pager, release notes template) into your project repo
- Keep the project README current with status and links to artifacts (one-pager, risk register, release notes)
- Propose doc changes via the repository process (use the "Add Content to Project Management Process Docs" issue template)
- For Copilot Spaces context, add process-specific artifacts into `.copilot/` if you want them available as Space context

## Quick Start Checklist

- [ ] One-pager exists and is linked from the project README
- [ ] Risk Register initialized and assigned
- [ ] Backlog has prioritized items with acceptance criteria
- [ ] CI and PR conventions are documented in the repo
- [ ] Definition of Done is clearly defined and shared with the team

For detailed guidance, see each document above or contact the Project Manager / Product Lead.