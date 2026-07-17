# 10 – Design Validation

> **Template Notice:** This document is an organization-level template. It is not a completed Design History File record until it has been copied into a product-specific controlled location, completed with accurate evidence, reviewed, and approved.

| Field | Value |
|---|---|
| Product | [Product Name] |
| Software Version | [Software Version or Version Range] |
| Repository | [Repository Name] |
| Document Status | Draft |
| Document Owner | [Name or Role] |
| Revision | A |
| Effective Date | [YYYY-MM-DD] |
| Approved By | [Name or Role] |
| Approval Date | [YYYY-MM-DD] |

## Purpose

This section documents the design validation activities for [Product Name]. Validation provides objective evidence that the product meets the needs of the intended users and fulfills the intended use under simulated or actual conditions of use.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## Important Notice Regarding Validation Records

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

Validation results, participant information, and approval records must reflect actual activities. Do not fabricate validation outcomes, participant lists, or approval signatures.

---

## Validation Plan

Describe the validation plan, including the validation approach, scope, and planned activities.

- **Validation Plan Reference:** [Document Number and Revision]
- **Validation Approach:** [Describe the validation approach]
- **Production-Equivalent Software Version:** [Version or Tag used for validation]
- **Validation Environment:** [Describe the validation environment]

---

## Intended-Use Validation

Describe how validation activities confirm that the product fulfills its intended use.

- **Intended Use Statement:** [Reference intended use from Section 01]
- **Validation Activities:** [Describe activities performed to validate intended use]
- **Record Reference:** [Reference validation records]

---

## User-Needs Validation

Describe how each user need has been addressed by validation activities.

| User Need ID | User Need | Validation Activity ID | Validation Record | Status |
|---|---|---|---|---|
| UN-001 | [User need description] | VAL-001 | [Record reference] | Draft |

---

## Validation Table

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Validation ID | User Need IDs | Validation Activity | Environment | Participants | Expected Result | Actual Result | Evidence | Approval | Status |
|---|---|---|---|---|---|---|---|---|---|
| VAL-001 | [UN-xxx] | [Validation activity description] | [Environment description] | [Participant roles — enter only if activity was conducted] | [Expected result] | [Actual result — enter only if activity was conducted] | [Evidence reference] | [Approval record — enter only if approval was obtained] | Draft |

---

## Production-Equivalent Software

Describe the software version used for validation and confirm it is equivalent to the production release.

- **Software Version Used:** [Software Version or Tag]
- **Commit SHA:** [Commit SHA]
- **Repository:** [Repository Name]
- **Equivalence Justification:** [Describe why this version is equivalent to the production release]

---

## Representative Users

Describe the representative users who participated in validation activities.

> Do not enter participant information unless validation activities were actually conducted with identified participants.

| Participant ID | Role | Training and Experience | Notes |
|---|---|---|---|
| P-001 | [User role] | [Training and experience description] | [Notes] |

---

## Representative Hardware

Describe the hardware used during validation and confirm it is representative of the intended use hardware.

| Hardware ID | Description | Configuration | Representative of Use | Notes |
|---|---|---|---|---|
| HW-001 | [Hardware description] | [Configuration details] | [Yes / No — with justification] | [Notes] |

---

## Representative Use Environment

Describe the use environment in which validation was conducted and confirm it is representative of the intended use environment.

| Environment ID | Description | Location | Representative of Use | Notes |
|---|---|---|---|---|
| ENV-001 | [Environment description] | [Location] | [Yes / No — with justification] | [Notes] |

---

## Deviations

Document any deviations from the validation plan and their impact on the validity of the results.

| Deviation ID | Description | Impact | Resolution | Approval |
|---|---|---|---|---|
| DEV-001 | [Deviation description] | [Impact assessment] | [Resolution] | [Approval reference] |

---

## Unresolved Anomalies

List any unresolved anomalies identified during validation and their disposition for release.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Anomaly ID | Description | Severity | Risk Impact | Disposition | Approval Reference |
|---|---|---|---|---|---|
| AN-001 | [Anomaly description] | [Severity] | [Risk impact] | [Disposition: deferred / accepted / resolved] | [Approval reference] |

---

## Validation Approval

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Approver Role | Approval Statement | Approval Date | Record Reference |
|---|---|---|---|
| [Name or Role] | Validation is complete and the product meets intended use | [YYYY-MM-DD] | [Reference] |

---

## Records and Supporting Evidence

| Evidence Type | Record Title | Repository or Location | Issue/PR Number | Version/Tag/Commit | Revision | Approval Date | Status | Notes |
|---|---|---|---|---|---|---|---|---|
| [Type] | [Title] | [Location] | [Reference] | [Identifier] | [Revision] | [YYYY-MM-DD] | [Status] | [Notes] |

---

## Identified Gaps or Required Actions

Describe any gaps or required actions identified during preparation of this section.

---

## Revision History

| Revision | Date | Description of Change | Prepared By | Approved By |
|---|---|---|---|---|
| A | [YYYY-MM-DD] | Initial document | [Name or Role] | [Name or Role] |
