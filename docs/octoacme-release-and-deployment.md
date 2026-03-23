# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans — **verified by Security Lead**
- Release notes drafted — **owned by Release Manager**, reviewed by Product Manager
- Rollback / mitigation plan documented — **owned by Release Manager** in collaboration with Developers
- Smoke tests prepared — **owned by QA / Developers**
- Go/no-go decision documented — **facilitated by Release Manager**, requires sign-off from Project Manager, Product Manager, and Security Lead

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **Release Manager** triggers incident response and notifies on-call
  - **Release Manager** coordinates rollback to last known-good release if necessary
  - **Security Lead** assesses whether the incident has a security dimension and invokes the security incident runbook if so
  - Triage root cause and capture action items (owned by **Project Manager** post-incident)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Release Readiness Checklist
For the full role-aligned release readiness checklist, see [`octoacme-release-readiness-checklist.md`](octoacme-release-readiness-checklist.md).
