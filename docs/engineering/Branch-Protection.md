# 🔒 Branch Protection

---

## Purpose

This document defines the branch protection rules for all Git repositories at UVISHA.

The goal is to prevent accidental changes, unauthorized modifications, and unstable code from reaching production.

---

## Protected Branches

- main
- development

---

## Rules

- No direct push to the main branch.
- All changes must go through a Pull Request.
- At least one code review is required.
- All automated tests must pass.
- Security scans must pass.
- Force push is disabled.
- Branch deletion is restricted.
- Commit history should remain clean.

---

## Pull Request Checklist

Before merging:

- Code Review Completed
- QA Approved
- Security Review Passed
- Documentation Updated
- Tests Passed
- Rollback Plan Available

---

## Emergency Changes

Emergency fixes require:

- CTO Approval
- QA Verification
- Security Review
- Post-release Documentation

---

## Final Rule

Protecting the main branch protects the stability and reputation of UVISHA.