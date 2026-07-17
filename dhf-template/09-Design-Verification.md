# 09 – Design Verification

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

This section documents the design verification activities for [Product Name]. Verification confirms that the design outputs meet the design inputs through objective evidence such as test execution, analysis, inspection, or review.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## Verification Test Table

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Test ID | Requirement IDs | Test Title | Method | Expected Result | Actual Result | Tester | Date | Evidence Location | Pass/Fail |
|---|---|---|---|---|---|---|---|---|---|
| VT-001 | [DI-xxx] | [Test title] | [Method: test / analysis / inspection / review] | [Expected result] | [Actual result — enter only if test has been executed] | [Tester role] | [YYYY-MM-DD — enter only if test has been executed] | [Repository, CI run, or controlled location] | [Pass / Fail / Not Executed] |

---

## Unit Testing

Describe the unit testing approach, scope, tools, and coverage targets.

- **Testing Framework:** [e.g., pytest, JUnit, NUnit, xUnit]
- **Code Coverage Target:** [e.g., ≥80% line coverage]
- **Automated CI Integration:** [Yes / No — describe if applicable]
- **Test Record Location:** [Repository path, CI system, or controlled location]

| Test ID | Requirement IDs | Test Title | Method | Expected Result | Actual Result | Tester | Date | Evidence Location | Pass/Fail |
|---|---|---|---|---|---|---|---|---|---|
| UT-001 | [DI-xxx] | [Unit test title] | Automated unit test | [Expected result] | [Actual result] | [Tester role] | [YYYY-MM-DD] | [Location] | [Pass / Fail / Not Executed] |

---

## Integration Testing

Describe the integration testing approach, scope, and tools.

- **Scope:** [Describe modules or interfaces under integration test]
- **Test Record Location:** [Repository path, CI system, or controlled location]

| Test ID | Requirement IDs | Test Title | Method | Expected Result | Actual Result | Tester | Date | Evidence Location | Pass/Fail |
|---|---|---|---|---|---|---|---|---|---|
| IT-001 | [DI-xxx] | [Integration test title] | Automated / Manual | [Expected result] | [Actual result] | [Tester role] | [YYYY-MM-DD] | [Location] | [Pass / Fail / Not Executed] |

---

## System Testing

Describe the system testing approach, scope, and tools.

- **Scope:** [Describe end-to-end system test scope]
- **Test Environment:** [Describe test environment, hardware, OS, software versions]
- **Test Record Location:** [Repository path or controlled location]

| Test ID | Requirement IDs | Test Title | Method | Expected Result | Actual Result | Tester | Date | Evidence Location | Pass/Fail |
|---|---|---|---|---|---|---|---|---|---|
| ST-001 | [DI-xxx] | [System test title] | Manual / Automated | [Expected result] | [Actual result] | [Tester role] | [YYYY-MM-DD] | [Location] | [Pass / Fail / Not Executed] |

---

## Requirements-Based Testing

Describe how each design input requirement has been addressed by verification testing.

| Requirement ID | Test IDs | Coverage Status | Notes |
|---|---|---|---|
| DI-001 | [VT-xxx, UT-xxx] | [Fully covered / Partially covered / Not covered] | [Notes] |

---

## Interface Testing

Describe testing of software interfaces, including API testing, DICOM conformance, and communication protocol testing.

| Test ID | Interface | Requirement IDs | Method | Expected Result | Actual Result | Date | Evidence Location | Pass/Fail |
|---|---|---|---|---|---|---|---|---|
| IF-001 | [Interface name] | [DI-xxx] | [Method] | [Expected result] | [Actual result] | [YYYY-MM-DD] | [Location] | [Pass / Fail / Not Executed] |

---

## Installation Testing

Describe testing of the installation process, including supported platforms, configurations, and upgrade scenarios.

| Test ID | Platform | Requirement IDs | Method | Expected Result | Actual Result | Date | Evidence Location | Pass/Fail |
|---|---|---|---|---|---|---|---|---|
| INS-001 | [Platform] | [DI-xxx] | [Method] | [Expected result] | [Actual result] | [YYYY-MM-DD] | [Location] | [Pass / Fail / Not Executed] |

---

## Regression Testing

Describe the regression testing strategy and how it ensures that changes do not introduce new defects.

- **Regression Test Approach:** [Describe regression test approach]
- **Automation Level:** [Fully automated / Partially automated / Manual]
- **Trigger Conditions:** [Describe when regression testing is triggered, e.g., each pull request, each release]
- **Test Record Location:** [Repository path or CI system]

---

## Risk Control Verification

Describe how risk controls have been verified. Every risk control identified in Section 07 must be referenced here.

| Risk Control ID | Risk ID | Verification Method | Test IDs | Result | Notes |
|---|---|---|---|---|---|
| RC-001 | R-001 | [Method] | [VT-xxx] | [Pass / Fail / Not Executed] | [Notes] |

---

## Anomaly Handling

Describe how anomalies (defects, failures, unexpected results) discovered during verification are tracked, evaluated, and resolved.

- **Anomaly Tracking:** [Reference issue tracker, e.g., GitHub Issues]
- **Severity Classification:** [Describe severity classification process]
- **Resolution Process:** [Describe resolution and re-test process]
- **Release Impact Assessment:** [Describe how unresolved anomalies are evaluated for release impact]

| Anomaly ID | Test ID | Description | Severity | Status | Resolution | Release Version |
|---|---|---|---|---|---|---|
| AN-001 | [Test ID] | [Anomaly description] | [Severity] | [Open / Closed] | [Resolution description or issue reference] | [Version] |

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
