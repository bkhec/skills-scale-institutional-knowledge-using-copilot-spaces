# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Scrum Master if applicable)
- Weekly delivery sync — show progress, updates, and flagged risks
- Design reviews with UX Designer (as needed for UI work)
- Demo/Review at the end of each sprint or milestone (include all stakeholders and Customer Success)
- Data review sessions with Data Analyst to track success metrics

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - UX Designer reviews UI/UX changes
  - Run automated tests and linting in CI before requesting review (managed by DevOps Engineer)
  - Require at least one approval before merging (or team-defined policy)
  - DevOps Engineer monitors deployment pipeline and infrastructure

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown (Scrum Master if applicable)
- Monitor success metrics identified in the Project One-pager (Data Analyst)
- Use dashboards for key signals (errors, latency, usage) - maintained by DevOps Engineer
- Customer feedback and satisfaction scores (Customer Success)
- UX metrics (task completion, user satisfaction) - tracked by UX Designer and Data Analyst

## Blocker Escalation
- Level 1: Team-level triage in daily standup (facilitated by Scrum Master if applicable)
- Level 2: PM escalates to Product Lead and dependent teams (with support from relevant role owners)
- Level 3: Sponsor-level escalation for business-impacting issues
- Infrastructure/deployment blockers: DevOps Engineer escalates to infrastructure team
- Customer-impacting issues: Customer Success escalates with urgency context

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Monitoring and alerting configured (DevOps Engineer)
- [ ] Design system/components available (UX Designer)
- [ ] Analytics instrumentation implemented (Data Analyst)
- [ ] Regular demos scheduled (include Customer Success)
- [ ] Risk register updated weekly
- [ ] Cross-functional collaboration touchpoints established
