# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release Requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Security & Compliance Officer sign-off obtained
- Release notes drafted (PM coordinates; Customer Success/Support Rep reviews customer-facing language)
- Rollback / mitigation plan documented (DevOps/Platform Engineer owns)
- Smoke tests prepared and approved

## Deployment Checklist
- [ ] Deployment window scheduled — agreed between PM, Tech Lead, and DevOps/Platform Engineer
- [ ] Customer Success/Support Rep notified; customer comms drafted if needed
- [ ] Backup or snapshot taken (if applicable) — DevOps/Platform Engineer
- [ ] Deploy to staging and run smoke tests — DevOps/Platform Engineer
- [ ] UX/Design Lead spot-checks user-facing changes in staging (for Minor/Major releases)
- [ ] Security & Compliance Officer final review completed
- [ ] Deploy to production (automated pipeline preferred) — DevOps/Platform Engineer
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support — PM + Customer Success/Support Rep

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - DevOps/Platform Engineer triggers rollback to last known-good release
  - PM initiates incident response and notifies on-call
  - Security & Compliance Officer engaged immediately if the incident has security implications
  - Triage root cause and capture action items
  - Customer Success/Support Rep coordinates customer-facing communication

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Customer communication prepared by: _(Customer Success/Support Rep)_
