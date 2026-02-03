# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer)
- UX validation completed for user-facing changes
- Release notes drafted
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared
- Customer Success notified of upcoming changes
- Data tracking validated for new features (Data Analyst)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - coordinated by DevOps Engineer
- [ ] Backup or snapshot (if applicable) - managed by DevOps Engineer
- [ ] Deploy to staging and run smoke tests
- [ ] UX Designer verifies UI changes in staging
- [ ] Deploy to production (automated pipeline preferred) - executed by DevOps Engineer
- [ ] Run post-deploy verifications and monitoring checks
- [ ] Data Analyst validates tracking and metrics collection
- [ ] Announce release to stakeholders and support (PM + Customer Success)
- [ ] Customer Success prepares support team for changes

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads technical response)
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Customer Success communicates with affected customers
  - Triage root cause and capture action items
  - Data Analyst monitors impact metrics during incident
  - Conduct blameless post-incident retrospective with all involved roles

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
