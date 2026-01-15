# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. The Release Manager coordinates all release activities and ensures this process is followed.

## Roles & Responsibilities
- **Release Manager**: Coordinates release planning, execution, and communications
- **QA Lead**: Validates quality gates and test completion
- **Change Control Coordinator**: Ensures change approvals and governance compliance
- **Project Manager**: Aligns releases with project milestones
- **Product Manager**: Validates feature readiness and messaging

_See [Roles & Personas](octoacme-roles-and-personas.md) for detailed role definitions._

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA Lead sign-off on quality gates
- Change Control Coordinator approval obtained
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

_For detailed pre-release checklist, see [Release Checklist](octoacme-release-checklist.md)_

## Deployment Checklist
The Release Manager coordinates execution of the deployment checklist. For the complete checklist template, see [Release Checklist](octoacme-release-checklist.md).

**Key Steps:**
- [ ] Deployment window scheduled (if needed)
- [ ] Change approval obtained from Change Control Coordinator
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] QA Lead confirms quality gates met
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

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
