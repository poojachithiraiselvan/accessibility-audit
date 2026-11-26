# Project Architecture

## 1. Project Overview

The Accessibility Baseline & Repository Architecture Audit project evaluates the accessibility of a public-facing website and establishes a maintainable full-stack project foundation.

The project focuses on identifying accessibility issues, documenting evidence, and recommending improvements based on accessibility standards.

## 2. Project Structure

```text
accessibility-audit/
├── client/
├── server/
├── docs/
│   ├── screenshots/
│   └── architecture.md
├── tests/
├── README.md
├── accessibility-audit-template.csv
└── accessibility-audit-template.xlsx
```

## 3. Directory Responsibilities

### Client
Contains the frontend application and user interface components.

### Server
Reserved for backend application logic and API development.

### Docs
Stores architecture documentation and accessibility audit screenshots.

### Tests
Reserved for automated testing and validation.

## 4. Tools and Technologies

- Lighthouse – Website accessibility evaluation.
- Browser Developer Tools – Inspecting website elements and accessibility issues.
- Keyboard Navigation – Testing website usability without a mouse.
- GitHub – Source code management and project documentation.
- CSV and Excel – Recording accessibility audit findings.

## 5. Accessibility Audit Workflow

1. Select a public-facing website.
2. Perform a Lighthouse accessibility audit.
3. Conduct keyboard-only navigation testing.
4. Identify accessibility problems.
5. Record evidence and affected components.
6. Assign severity and remediation priorities.
7. Capture screenshots as supporting evidence.
8. Document findings in the audit worksheet.

## 6. Client and Server Architecture

The project follows a modular architecture.

- Client: Responsible for
