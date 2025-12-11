# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Business Analyst confirms UAT sign-off
- UX Designer validates design implementation (if applicable)
- Data Analyst confirms tracking and metrics are in place
- Passing CI and security scans
- Deployment Engineer reviews and approves deployment plan
- Release notes drafted
- Rollback / mitigation plan documented by Deployment Engineer
- Smoke tests prepared
- Support Lead briefed on changes and customer impact

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - coordinated by PM and Deployment Engineer
- [ ] Support Lead and team prepared with release documentation and known issues
- [ ] Backup or snapshot (if applicable) - managed by Deployment Engineer
- [ ] Deploy to staging and run smoke tests - led by Deployment Engineer
- [ ] UX Designer performs final usability check in staging
- [ ] Data Analyst validates metrics collection in staging
- [ ] Deploy to production (automated pipeline preferred) - executed by Deployment Engineer
- [ ] Run post-deploy verifications - Deployment Engineer and QA
- [ ] Data Analyst confirms metrics flowing correctly in production
- [ ] Support Lead monitors initial customer feedback and issues
- [ ] Announce release to stakeholders and support - PM coordinates with Support Lead

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Deployment Engineer triggers incident response and notifies on-call
  - Support Lead communicates with affected customers and escalates urgent issues
  - Deployment Engineer executes rollback to last known-good release if necessary
  - Data Analyst monitors metrics to assess impact
  - Cross-functional team triages root cause and captures action items
  - Scrum Master facilitates post-incident retrospective

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
