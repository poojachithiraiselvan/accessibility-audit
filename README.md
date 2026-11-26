# Accessibility Audit – Passport Seva Website

## Project Overview
This repository contains accessibility audit findings identified during the evaluation of the Passport Seva website using Google Lighthouse.

## Audit Objectives
- Identify website accessibility issues.
- Evaluate findings based on WCAG guidelines.
- Document evidence and user impact.
- Recommend improvements to enhance accessibility.

## Tools Used
- Google Lighthouse
- Chrome DevTools
- GitHub
- Microsoft Excel

## Audit Summary

A total of 5 accessibility findings were documented.

| Issue ID | WCAG Reference | Severity | Status |
|---|---|---|---|
| WEB-001 | 4.1.2 | Medium | Open |
| WEB-002 | 4.1.2 | Medium | Open |
| WEB-003 | 1.1.1 | Medium | Open |
| WEB-004 | 1.3.1 | Medium | Open |
| WEB-005 | 1.3.1 | Medium | Open |

Note: Severity levels are initial assessments and are not assigned by Lighthouse.

## Files Included
- `accessibility-audit-template.csv` – CSV version of audit findings.
- `accessibility-audit-template.xlsx` – Excel version of audit findings.

## Audit Scope
- Main navigation
- Navigation menu button
- Informative images
- Navigation and footer lists
- Navigation menu structure

## Expected Outcome
Improve website accessibility, support screen reader users, and encourage better WCAG compliance.

## Status
Documentation completed. Accessibility fixes are pending.
## Repository Architecture

This project follows a monorepo-style structure.

- Client: Frontend interface and user interactions.
- Server: Backend logic and API services.
- Docs: Architecture documentation and audit screenshots.
- Tests: Testing resources.

## Local Setup

### Prerequisites
- Git
- Visual Studio Code
- Google Chrome

### Clone Repository

git clone https://github.com/poojachithiraiselvan/accessibility-audit.git

### Open Project

cd accessibility-audit

## First Vertical Feature Slice

The first planned feature is an Accessibility Issue Reporting workflow.

1. Identify an accessibility issue.
2. Record the affected component.
3. Store issue details and evidence.
4. Assign severity and priority.
5. Display the issue for review.

This feature will connect the client, server, and testing layers as implementation progresses.

## Project Documentation

- docs/architecture.md - Architecture documentation.
- docs/screenshots/ - Audit evidence screenshots.
- accessibility-audit-template.csv - Audit findings.
- accessibility-audit-template.xlsx - Audit findings in Excel format.
