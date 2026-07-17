# 07 – Risk Management

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

This section documents the risk management activities for [Product Name] in accordance with ISO 14971 and IEC 62304. It covers hazard identification, risk estimation, risk evaluation, risk control, and residual risk assessment.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## Risk Management Plan

Describe the risk management plan, including the applicable standards, risk acceptability criteria, and the scope of risk management activities.

- **Applicable Standards:** ISO 14971, IEC 62304, [other applicable standards]
- **Risk Management Plan Reference:** [Document Number and Revision]
- **Risk Acceptability Criteria:** [Describe or reference risk acceptability criteria]
- **Probability Scale:** [Describe probability scale, e.g., 1 (Negligible) to 5 (Frequent)]
- **Severity Scale:** [Describe severity scale, e.g., 1 (Negligible) to 5 (Catastrophic)]
- **Risk Matrix Reference:** [Reference risk matrix or risk acceptability table]

---

## Hazard Analysis

Describe the hazard identification process and the sources of hazards considered.

### Hazard Sources Considered

- Foreseeable misuse
- User interface design
- Software algorithm failures
- Data integrity errors
- Communication failures
- Environmental factors
- Third-party software or component failures
- Cybersecurity threats
- [Other hazard sources relevant to this product]

---

## Software Hazards

List software-specific hazards identified during hazard analysis.

| Software Hazard ID | Hazard Description | Related Use Scenario | Notes |
|---|---|---|---|
| SH-001 | [Software hazard description] | [Use scenario] | [Notes] |

---

## Hazardous Situations

Describe hazardous situations derived from the combination of foreseeable sequences of events and identified hazards.

| Hazardous Situation ID | Sequence of Events | Hazardous Situation | Potential Harm | Notes |
|---|---|---|---|---|
| HS-001 | [Sequence of events] | [Hazardous situation description] | [Harm] | [Notes] |

---

## Risk Table

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Risk ID | Hazard | Sequence of Events | Hazardous Situation | Harm | Initial Risk | Risk Control | Verification Record | Residual Risk | Acceptance Status |
|---|---|---|---|---|---|---|---|---|---|
| R-001 | [Hazard] | [Sequence of events] | [Hazardous situation] | [Harm] | [Probability × Severity] | [Risk control description] | [Verification record reference] | [Residual probability × severity] | [Acceptable / Unacceptable / Pending review] |

---

## Risk Controls

Describe the risk controls implemented to reduce identified risks to acceptable levels.

| Risk Control ID | Risk ID | Control Description | Type | Implementation Location | Verification Method | Status |
|---|---|---|---|---|---|---|
| RC-001 | R-001 | [Risk control description] | [Inherently safe design / Protective measure / Information for safety] | [Location in software or documentation] | [Verification method] | Draft |

---

## Verification of Risk Controls

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Risk Control ID | Verification Method | Verification Record | Tester | Test Date | Result | Notes |
|---|---|---|---|---|---|---|
| RC-001 | [Method] | [Record reference] | [Tester role] | [YYYY-MM-DD] | [Pass / Fail / Pending] | [Notes] |

---

## Residual Risk Evaluation

Describe the evaluation of residual risk after implementation of risk controls.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Risk ID | Initial Risk Level | Risk Control Applied | Residual Risk Level | Acceptable | Notes |
|---|---|---|---|---|---|
| R-001 | [Initial level] | RC-001 | [Residual level] | [Yes / No / Pending] | [Notes] |

---

## Benefit-Risk Evaluation

Describe the benefit-risk evaluation performed for risks that cannot be reduced to broadly acceptable levels.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

Summarize the overall benefit-risk determination for the product here.

---

## Risk Acceptability

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Determination | Approver Role | Approval Date | Record Reference |
|---|---|---|---|
| Overall residual risk is acceptable | [Name or Role] | [YYYY-MM-DD] | [Reference] |

---

## Production and Post-Production Information

Describe how post-production information (complaints, adverse events, post-market surveillance data) will be fed back into the risk management process.

- **Post-Market Surveillance Process:** [Reference applicable SOP or process]
- **Complaint Handling Process:** [Reference applicable SOP or process]
- **Risk Management File Update Trigger:** [Describe conditions under which the risk management file is updated]

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
