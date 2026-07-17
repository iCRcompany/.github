# 15 – Problem Resolution

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

This section documents the problem resolution activities for [Product Name]. It covers software anomalies, bug reports, customer complaints, corrective and preventive actions (CAPA), deviations, and unresolved issues and their impact on the product release.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## Problem Record Table

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Record ID | Problem Description | Source | Severity | Risk Impact | Resolution | Verification | Release Version | Closure Status |
|---|---|---|---|---|---|---|---|---|
| PR-001 | [Problem description] | [Source: bug report / complaint / internal discovery / anomaly] | [Severity: Critical / Major / Minor] | [Risk impact assessment] | [Resolution description] | [Verification record reference] | [Release version where resolved] | [Open / Closed / Deferred] |

---

## Software Anomalies

List software anomalies (defects) discovered during development, testing, or post-release operation.

| Anomaly ID | Description | Severity | Discovered During | GitHub Issue | Resolution | Verification Record | Status |
|---|---|---|---|---|---|---|---|
| AN-001 | [Anomaly description] | [Severity] | [Testing phase or operation] | [Issue Number] | [Resolution description] | [Verification record reference] | [Open / Closed / Deferred] |

---

## Bug Reports

List bug reports submitted through the product's issue tracking system.

| Bug ID | Title | GitHub Issue | Severity | Risk Impact | Status | Resolution | Release Version |
|---|---|---|---|---|---|---|---|
| BUG-001 | [Bug title] | [Issue Number] | [Severity] | [Risk impact] | [Open / Closed / Deferred] | [Resolution description] | [Version] |

---

## Complaints

List customer or user complaints relevant to this DHF. Include the complaint reference, severity, and regulatory reporting status.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Complaint ID | Description | Source | Date Received | Severity | Regulatory Report Required | CAPA Reference | Status |
|---|---|---|---|---|---|---|---|
| CMP-001 | [Complaint description] | [Source] | [YYYY-MM-DD] | [Severity] | [Yes / No] | [CAPA reference] | [Open / Closed] |

---

## CAPA References

List corrective and preventive actions (CAPA) initiated in response to problems identified for this product.

| CAPA ID | Related Problem ID | Description | Type | Status | Closure Evidence |
|---|---|---|---|---|---|
| CAPA-001 | [PR-xxx / AN-xxx / CMP-xxx] | [CAPA description] | [Corrective / Preventive] | [Open / Closed] | [Closure record reference] |

---

## Deviations

List any deviations from design controls, procedures, or specifications identified during development or release.

| Deviation ID | Description | Impact | Disposition | Approval Reference |
|---|---|---|---|---|
| DEV-001 | [Deviation description] | [Impact assessment] | [Accepted / Resolved] | [Approval reference] |

---

## Unresolved Anomalies

List anomalies that have been identified but not resolved at the time of this document revision.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Anomaly ID | Description | Severity | Risk Impact | Disposition Decision | Approver | Approval Date |
|---|---|---|---|---|---|---|
| AN-001 | [Anomaly description] | [Severity] | [Risk impact] | [Accepted / Deferred — with justification] | [Name or Role] | [YYYY-MM-DD] |

---

## Release Impact

Describe how unresolved problems and anomalies were evaluated for their impact on the product release.

| Release Version | Unresolved Items | Risk Assessment | Release Decision | Approver | Approval Date |
|---|---|---|---|---|---|
| [Version] | [List of unresolved item IDs] | [Risk assessment summary] | [Released with known issues / Held pending resolution] | [Name or Role] | [YYYY-MM-DD] |

---

## Corrective Actions

Describe corrective actions taken to address identified problems and prevent recurrence.

| Action ID | Related Problem ID | Corrective Action | Owner | Target Date | Closure Evidence | Status |
|---|---|---|---|---|---|---|
| CA-001 | [PR-xxx / AN-xxx] | [Corrective action description] | [Owner role] | [YYYY-MM-DD] | [Closure record reference] | [Open / Closed] |

---

## Closure Evidence

Describe how closed problems are verified and documented.

| Record ID | Closure Evidence | Verification Date | Verified By | Notes |
|---|---|---|---|---|
| [PR-xxx / AN-xxx] | [Closure evidence reference] | [YYYY-MM-DD] | [Role] | [Notes] |

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
