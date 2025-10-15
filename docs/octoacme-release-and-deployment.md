# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Ownership & Coordination
- **Release Manager** (if assigned): Owns release schedule, coordinates go/no-go decisions, manages deployment execution
- **Project Manager**: Aligns release timing with project milestones, communicates to stakeholders
- **Developers**: Ensure code is release-ready, support deployment validation
- **QA/Testing**: Validate release candidates, execute smoke tests
- **Product Manager**: Approves feature completeness, prioritizes hotfixes

For projects without a dedicated Release Manager, the Project Manager coordinates releases with engineering leads.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Release Manager or PM
- [ ] Backup or snapshot (if applicable) — Engineering/DevOps
- [ ] Deploy to staging and run smoke tests — QA/Testing
- [ ] Deploy to production (automated pipeline preferred) — Release Manager or designated Developer
- [ ] Run post-deploy verifications — QA/Testing + Developers
- [ ] Announce release to stakeholders and support — Project Manager or Release Manager

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
