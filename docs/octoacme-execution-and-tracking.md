# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - Facilitated by: Scrum Master (if assigned) or Project Manager
  - Participants: Developers, QA, UX Designer (as needed)
- Weekly delivery sync — show progress, updates, and flagged risks
  - Led by: Project Manager
  - Participants: Product Manager, team leads, key stakeholders
- Demo/Review at the end of each sprint or milestone
  - Facilitated by: Scrum Master or Project Manager
  - Presents: Team (Developers, UX Designer)
  - Audience: Product Manager, stakeholders

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer + QA collaboration)
- End-to-end smoke tests for critical flows before release (QA/Testing)
- Security scanning in CI (automated, flagged to Developers)
- Manual QA for feature acceptance when needed (QA/Testing)
- Usability testing for UX-critical features (UX Designer + QA)
- Accessibility validation (UX Designer responsibility, validated by QA)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master or PM facilitates)
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

### Role Clarity in Escalations
- **Developer**: Raises technical blockers (tooling, dependencies, unclear requirements)
- **Scrum Master**: Facilitates resolution of process blockers, shields team from distractions
- **Project Manager**: Escalates cross-team dependencies, resource constraints, timeline risks
- **Product Manager**: Escalates prioritization conflicts, stakeholder alignment issues
- **Business Analyst**: Escalates requirements ambiguity, data access issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
