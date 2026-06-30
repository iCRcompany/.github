# .github

This repository contains default GitHub issue templates for the organization.

Templates defined here are automatically used as defaults across all repositories in the organization that do not define their own issue templates.

## Issue Templates

| Template | Description |
|----------|-------------|
| [Bug Report](.github/ISSUE_TEMPLATE/bug_report.yml) | Report a software issue or unexpected behavior |
| [Feature Request](.github/ISSUE_TEMPLATE/feature_request.yml) | Request a new feature or enhancement |
| [Task](.github/ISSUE_TEMPLATE/task.yml) | Internal development or maintenance task |
| [Technical Support Issue](.github/ISSUE_TEMPLATE/technical_support.yml) | Track a customer, machine, installation, or field support issue |
| [F-314 Rev B](.github/ISSUE_TEMPLATE/software_validation_record.yml) | Document software validation, tester profile, test location, usability goals, validation results, and approval |
| [F-316 Rev B Software Risk Analysis](.github/ISSUE_TEMPLATE/software_risk_analysis.yml) | Document software risk analysis, hazards, probability, severity, mitigations, and approval |

## Overriding Templates

Individual repositories can override these defaults by adding their own templates under `.github/ISSUE_TEMPLATE/` within that repository. Repository-level templates take precedence over the organization defaults.
