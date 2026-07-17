# 16 – Cybersecurity

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

This section documents the cybersecurity activities for [Product Name] in accordance with applicable guidance such as FDA's Cybersecurity in Medical Devices guidance, AAMI TIR57, and IEC 81001-5-1. It covers threat modeling, security requirements, security controls, and residual security risks.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## Applicability

> Cybersecurity items must be marked as not applicable only when there is an approved justification. The justification must identify the specific item, the basis for non-applicability, and the approver.

| Item | Applicable | Justification if Not Applicable | Approver | Approval Date |
|---|---|---|---|---|
| Threat Modeling | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Authentication | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Authorization | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Data Protection | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Secure Communications | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Logging and Audit Trails | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Software Update Process | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Vulnerability Monitoring | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |
| Penetration or Security Testing | [Yes / No] | [If No, provide justification] | [Name or Role] | [YYYY-MM-DD] |

---

## Cybersecurity Plan

Describe the cybersecurity plan, including applicable standards, risk acceptability criteria, and the scope of cybersecurity activities.

- **Cybersecurity Plan Reference:** [Document Number and Revision]
- **Applicable Standards and Guidance:** [List applicable standards, e.g., FDA Cybersecurity Guidance, IEC 81001-5-1, AAMI TIR57]
- **Risk Acceptability Criteria:** [Describe or reference risk acceptability criteria]

---

## Threat Modeling

Describe the threat modeling approach and the threats identified for this product.

- **Threat Modeling Method:** [e.g., STRIDE, PASTA, DREAD, Attack Tree]
- **Threat Model Reference:** [Document or repository reference]
- **Threat Model Date:** [YYYY-MM-DD — enter only if threat modeling has been completed]

| Threat ID | Threat Description | Attack Vector | Threat Category | Likelihood | Impact | Risk Level | Risk Control | Notes |
|---|---|---|---|---|---|---|---|---|
| TH-001 | [Threat description] | [Network / Local / Physical] | [STRIDE category or other] | [Likelihood] | [Impact] | [Risk level] | [Risk control reference] | [Notes] |

---

## Security Requirements

Describe the security requirements for this product, derived from threat modeling and applicable regulations.

| Requirement ID | Security Requirement | Source | Acceptance Criteria | Verification Method | Status |
|---|---|---|---|---|---|
| SR-001 | [Security requirement] | [Threat ID or regulation] | [Acceptance criterion] | [Verification method] | Draft |

---

## Authentication

Describe the authentication mechanisms implemented in this product.

- **Authentication Method:** [e.g., username/password, multi-factor authentication, certificate-based, SSO]
- **Session Management:** [Describe session management approach]
- **Account Lockout:** [Describe account lockout policy]
- **Default Credentials:** [Describe policy for default credentials — state if none are present]
- **Implementation Reference:** [Repository path or design document reference]

---

## Authorization

Describe the authorization model and access control mechanisms implemented in this product.

- **Authorization Model:** [e.g., role-based access control, attribute-based access control]
- **Roles Defined:** [List roles and their privileges]
- **Privilege Escalation Controls:** [Describe controls to prevent unauthorized privilege escalation]
- **Implementation Reference:** [Repository path or design document reference]

---

## Data Protection

Describe the data protection mechanisms implemented in this product, including encryption at rest and in transit.

- **Encryption at Rest:** [Describe encryption approach or state Not applicable with justification]
- **Encryption in Transit:** [Describe encryption approach, e.g., TLS 1.2 or higher]
- **Key Management:** [Describe key management approach]
- **Sensitive Data Classification:** [Describe what data is considered sensitive and how it is protected]
- **Implementation Reference:** [Repository path or design document reference]

---

## Secure Communications

Describe the secure communication protocols and configurations used in this product.

- **Communication Protocols:** [List communication protocols, e.g., HTTPS, TLS 1.3, DICOM TLS]
- **Certificate Validation:** [Describe certificate validation approach]
- **Network Segmentation:** [Describe network segmentation requirements]
- **Implementation Reference:** [Repository path or design document reference]

---

## Logging

Describe the logging and audit trail capabilities implemented in this product.

- **Events Logged:** [Describe events that are logged, e.g., login, data access, configuration changes]
- **Log Storage:** [Describe log storage location and retention]
- **Log Protection:** [Describe how logs are protected from tampering]
- **Log Review Process:** [Describe how logs are reviewed]
- **Implementation Reference:** [Repository path or design document reference]

---

## Software Update Process

Describe the process for delivering and applying software updates, including security patches.

- **Update Mechanism:** [Describe the update delivery mechanism]
- **Update Verification:** [Describe how updates are verified before installation]
- **Rollback Process:** [Describe the rollback procedure]
- **Customer Notification:** [Describe the customer notification process]
- **Update Record Reference:** [Reference to release management process]

---

## Vulnerability Monitoring

Describe the process for monitoring and responding to security vulnerabilities in the product and its dependencies.

- **Vulnerability Monitoring Process:** [Describe the monitoring process or reference applicable SOP]
- **Third-Party Component Monitoring:** [Describe how third-party component vulnerabilities are tracked, e.g., GitHub Dependabot, NVD monitoring]
- **Vulnerability Response Time:** [Describe target response times by severity]
- **Coordinated Disclosure Policy:** [Reference to responsible disclosure or PSIRT policy]

---

## Third-Party Components

List third-party libraries and components included in the software that have cybersecurity implications.

| Component | Version | Known Vulnerabilities | Mitigation | SBOM Reference |
|---|---|---|---|---|
| [Component name] | [Version] | [CVE references or None known] | [Mitigation or update plan] | [SBOM reference] |

---

## Software Bill of Materials (SBOM)

- **SBOM Reference:** [See Section 12 – Software Configuration]
- **SBOM Format:** [e.g., SPDX, CycloneDX]
- **SBOM Location:** [Repository path or controlled document location]

---

## Penetration and Security Testing

Describe any penetration testing or security assessments performed on this product.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Test ID | Test Type | Scope | Performed By | Date | Findings | Remediation | Record Reference |
|---|---|---|---|---|---|---|---|
| PT-001 | [Penetration test / Vulnerability scan / Code review] | [Scope] | [Tester role or firm] | [YYYY-MM-DD] | [Findings summary] | [Remediation reference] | [Test report reference] |

---

## Residual Security Risks

Describe the residual security risks after implementation of security controls.

> Do not enter an approval, test result, review outcome, or historical date unless objective evidence exists.

| Threat ID | Security Control Applied | Residual Risk Level | Acceptable | Notes |
|---|---|---|---|---|
| TH-001 | [Security control reference] | [Residual risk level] | [Yes / No / Pending] | [Notes] |

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
