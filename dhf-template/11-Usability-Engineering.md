# 11 – Usability Engineering

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

This section documents the usability engineering activities for [Product Name] in accordance with IEC 62366-1. It covers the identification of intended users, use environments, user interface characteristics, use-related hazards, formative evaluations, and summative validation.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## User Profiles

Describe the profiles of the intended users, including their characteristics relevant to usability and use-related risk.

| User Profile ID | User Role | Education and Training | Physical Characteristics | Cognitive Characteristics | Notes |
|---|---|---|---|---|---|
| UP-001 | [User role] | [Education and training level] | [Relevant physical characteristics] | [Relevant cognitive characteristics] | [Notes] |

---

## Use Environments

Describe the intended use environments, including characteristics that may affect usability and use-related risk.

| Environment ID | Environment Description | Lighting | Noise | Distractions | Time Pressure | Notes |
|---|---|---|---|---|---|---|
| UE-001 | [Environment description] | [Lighting conditions] | [Noise conditions] | [Distraction level] | [Time pressure level] | [Notes] |

---

## User Interface Characteristics

Describe the user interface characteristics of the product relevant to usability engineering.

- **Interface Type:** [GUI / Command-line / Web / Mobile / Embedded / Other]
- **Display Technology:** [Describe display characteristics]
- **Input Devices:** [Describe input devices, e.g., keyboard, mouse, touchscreen]
- **Notification Methods:** [Describe how the system alerts users]
- **Internationalization / Localization:** [Describe language and locale support]
- **Accessibility:** [Describe accessibility features or constraints]

---

## Known Use Problems

List any known use problems identified from prior product versions, complaints, post-market surveillance, or literature review.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Problem ID | Description | Source | User Profile | Risk Impact | Status | Notes |
|---|---|---|---|---|---|---|
| UP-001 | [Use problem description] | [Source: complaint / prior version / literature] | [User profile ID] | [Risk impact] | [Open / Resolved] | [Notes] |

---

## Use-Related Hazards

List use-related hazards identified during usability engineering activities, including those that may lead to harm.

| Hazard ID | Use-Related Hazard | User Profile | Sequence of Events | Potential Harm | Risk Control | Notes |
|---|---|---|---|---|---|---|
| URH-001 | [Use-related hazard description] | [User profile ID] | [Sequence of events] | [Potential harm] | [Risk control reference] | [Notes] |

---

## Critical Tasks

Identify the critical tasks — tasks for which use error could result in serious harm.

| Task ID | Task Description | User Profile | Criteria for Criticality | Notes |
|---|---|---|---|---|
| CT-001 | [Critical task description] | [User profile ID] | [Why this task is critical] | [Notes] |

---

## Formative Evaluations

Describe the formative usability evaluations conducted during development.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Evaluation ID | Type | Date | Scope | Participants | Findings | Actions | Record Reference |
|---|---|---|---|---|---|---|---|
| FE-001 | [Expert review / User test / Heuristic evaluation] | [YYYY-MM-DD — enter only if evaluation was conducted] | [Scope] | [Participants — enter only if evaluation was conducted] | [Findings — enter only if evaluation was conducted] | [Action items] | [Record reference] |

---

## Summative Validation

Describe the summative usability validation conducted with representative users performing critical tasks in a representative environment.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

- **Summative Validation Plan Reference:** [Document Number and Revision]
- **Software Version Used:** [Version or Tag]
- **Test Environment:** [Describe test environment]
- **Representative Users:** [Describe participant selection — enter only if validation was conducted]
- **Critical Tasks Tested:** [List CT-xxx IDs]
- **Results Summary:** [Summarize results — enter only if validation was conducted]
- **Record Reference:** [Validation report reference — enter only if validation was conducted]

| Task ID | Critical Task | Pass Count | Fail Count | Close Call Count | Acceptance Criterion | Status |
|---|---|---|---|---|---|---|
| CT-001 | [Task description] | [Count] | [Count] | [Count] | [Criterion] | [Pass / Fail / Not Executed] |

---

## Residual Use-Related Risk

Describe the residual use-related risk after implementation of risk controls and usability mitigations.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Hazard ID | Risk Control Applied | Residual Risk Level | Acceptable | Notes |
|---|---|---|---|---|
| URH-001 | [Risk control reference] | [Residual risk level] | [Yes / No / Pending] | [Notes] |

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
