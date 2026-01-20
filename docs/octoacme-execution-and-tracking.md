# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - Tag UX/UI Designer for review on UI changes
  - Notify Technical Writer for documentation updates
- QA workflow:
  - QA Lead triages and assigns test cases
  - Manual testing performed on items in QA column
  - Defects tracked and linked to original work items
  - QA sign-off required before moving to Done

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- QA Lead coordinates regression testing and sign-off
- UX/UI Designer validates design implementation and accessibility
- DevOps Engineer ensures CI/CD pipeline health and automated test integration
- Technical Writer reviews in-product help text and error messages

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] QA testing process and quality gates established (QA Lead)
- [ ] Design review process in place for UI changes (UX/UI Designer)
- [ ] Documentation updated with each feature release (Technical Writer)
