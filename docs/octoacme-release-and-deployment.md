# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (Technical Writer)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA Lead)
- Final QA sign-off completed (QA Lead)
- Design validation for UI changes (UX/UI Designer)
- Documentation updates published (Technical Writer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (DevOps Engineer + QA Lead)
- [ ] Deploy to production (automated pipeline preferred, managed by DevOps Engineer)
- [ ] Run post-deploy verifications (QA Lead)
- [ ] Announce release to stakeholders and support (Project Manager + Technical Writer)
- [ ] Update user-facing documentation (Technical Writer)
- [ ] Monitor system health and user feedback (DevOps Engineer)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Triage root cause and capture action items
  - Communicate status to stakeholders (Project Manager)
  - Update documentation with known issues (Technical Writer)
  - Conduct post-incident review with all relevant roles

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
