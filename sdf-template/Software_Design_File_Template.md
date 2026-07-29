# [Product Name] — Software Design File Template

> **Document purpose:** Use this file as the controlled product-level software design record for an iCRco software product, software utility, SDK, service, firmware component, or supporting application. Complete each section with objective evidence and links to applicable GitHub records, controlled workbooks, test records, releases, and approved documents.
>
> **Important:** Do not enter an approval, test result, regulatory conclusion, or historical date unless objective evidence exists.

---

## 1. Document Information

| Field | Entry |
|---|---|
| Product Name | [Product name] |
| Product Type | [Medical device software / accessory / component / utility / SDK / service / firmware / other] |
| Repository | [Repository URL or `iCRcompany/<repository>`] |
| Document Owner | [Name and role] |
| Current Software Version | [Version] |
| Current Release Tag | [Tag] |
| Document Revision | [Revision] |
| Revision Date | [YYYY-MM-DD] |
| Status | [Draft / In Review / Approved] |

---

## 2. Product Description

[Provide a concise description of the software product, its primary function, and its relationship to other iCRco products or systems.]

### 2.1 Intended Use

[Describe the intended purpose of the software, who uses it, what it is expected to accomplish, and where it is used.]

Suggested structure:

> The [Product Name] software is intended to [primary intended function] for use by [intended users] in [intended environment]. The software [does / does not] perform clinical interpretation, diagnosis, treatment recommendation, patient monitoring, image processing, or control of medical-device hardware.

### 2.2 Intended Users

- [Software operators]
- [Clinical users]
- [Service personnel]
- [IT personnel]
- [Production personnel]
- [Application specialists]
- [Developers or integrators]
- [Other]

### 2.3 Intended Patient or User Population

[Describe the intended patient population or state `Not applicable` when the software does not directly interact with patients.]

### 2.4 Intended Operating Environment

- Supported operating systems: [Windows versions / Linux / macOS / mobile / embedded]
- Installation environment: [Workstation / server / acquisition system / cloud / embedded controller]
- Network environment: [Standalone / local network / hospital network / internet-connected]
- Required permissions: [User / administrator / service account]
- Supported hardware: [List or reference]
- Required third-party components: [List or N/A]
- Required database or storage: [List or N/A]

### 2.5 Intended Inputs

- [User input]
- [Image or study data]
- [Device data]
- [Configuration settings]
- [Network messages]
- [Files or folders]
- [Database records]
- [Other]

### 2.6 Intended Outputs

- [Displayed information]
- [Images or reconstructed volumes]
- [DICOM objects]
- [Reports or logs]
- [Hardware commands]
- [Configuration changes]
- [Network transmissions]
- [Other]

### 2.7 Limitations and Exclusions

Document functions specifically outside the intended use.

- [Not intended for diagnosis]
- [Not intended for treatment recommendation]
- [Not intended to control exposure]
- [Not intended to modify diagnostic content]
- [Not intended for unsupported hardware]
- [Other limitation]

---

## 3. Regulatory and Product Determination

### 3.1 Regulatory Determination

| Field | Entry |
|---|---|
| Regulatory Classification | [Non-device software function / medical device software / accessory / component / firmware / other] |
| FDA Device Classification | [Class I / Class II / Class III / Not applicable / To be determined] |
| FDA Product Code | [Product code or N/A] |
| Submission Type | [510(k) / De Novo / PMA / Exempt / Not applicable / To be determined] |
| Submission or Clearance Number | [Number or N/A] |
| IEC 62304 Software Safety Class | [Class A / Class B / Class C / Not applicable / To be determined] |
| Determination Date | [YYYY-MM-DD] |
| Determined By | [Name and role] |
| Quality/Regulatory Approval | [Name, date, and evidence location] |
| Applicable Product Family | [Product family or standalone product] |

### 3.2 Determination Rationale

[Explain why the product is treated as a regulated device, accessory, software component, utility, non-device function, or other classification.]

### 3.3 Relationship to Regulated Products

| Product | Relationship | Included in Product Release? | DHF Reference | Notes |
|---|---|---:|---|---|
| [Product] | [Bundled / required / optional / not used] | [Yes / No] | [Link or N/A] | [Notes] |
| [Product] | [Relationship] | [Yes / No] | [Link or N/A] | [Notes] |

### 3.4 Applicable Standards and Guidance

| Standard or Guidance | Applicability | Evidence or Notes |
|---|---|---|
| ISO 13485 | [Applicable / Not applicable] | [Notes] |
| ISO 14971 | [Applicable / Not applicable] | [Notes] |
| IEC 62304 | [Applicable / Not applicable] | [Notes] |
| IEC 62366-1 | [Applicable / Not applicable] | [Notes] |
| DICOM Standard | [Applicable / Not applicable] | [Notes] |
| FDA software guidance | [Applicable / Not applicable] | [Notes] |
| Cybersecurity guidance | [Applicable / Not applicable] | [Notes] |
| [Other] | [Applicability] | [Notes] |

---

## 4. Software Scope and Architecture

### 4.1 Major Functions

- [Function 1]
- [Function 2]
- [Function 3]
- [Function 4]
- [Other]

### 4.2 Software Components

| Component | Purpose | Repository/Location | Version | Notes |
|---|---|---|---|---|
| Main application | [Purpose] | [Path/project] | [Version] | [Notes] |
| Service or background process | [Purpose] | [Path/project] | [Version] | [Notes] |
| User interface | [Purpose] | [Path/project] | [Version] | [Notes] |
| Shared library | [Purpose] | [Path/project] | [Version] | [Notes] |
| Database | [Purpose] | [Location] | [Version] | [Notes] |
| Third-party library | [Purpose] | [Package/reference] | [Version] | [Notes] |
| Installer | [Purpose] | [Path/project] | [Version] | [Notes] |
| Firmware | [Purpose] | [Location] | [Version] | [Notes] |

### 4.3 System Context

[Describe where the software fits within the overall product, device, network, or workflow.]

### 4.4 Data Flow

Describe the normal data flow:

1. [Input is received.]
2. [Input is validated or transformed.]
3. [The primary software function is performed.]
4. [Results are stored, displayed, transmitted, or used to control another component.]
5. [Errors, warnings, and status are recorded.]

### 4.5 External Interfaces

| Interface | Protocol/Format | Direction | Purpose | Failure Handling |
|---|---|---|---|---|
| [Interface] | [Protocol] | [Input / Output / Bidirectional] | [Purpose] | [Handling] |
| [Interface] | [Protocol] | [Direction] | [Purpose] | [Handling] |

### 4.6 Dependencies

| Dependency | Type | Version | Source | Risk or Impact |
|---|---|---|---|---|
| [Dependency] | [Library / SDK / driver / operating system / service] | [Version] | [Source] | [Impact] |

---

## 5. Software Requirements

Assign each requirement a stable identifier, such as `[PRODUCT]-REQ-001`.

| Requirement ID | Requirement | Source/Rationale | Risk Link | Verification Method | Evidence | Status |
|---|---|---|---|---|---|---|
| [PROD-REQ-001] | [Requirement] | [Source or rationale] | [Risk ID or N/A] | [Test / inspection / analysis / review] | [Link] | [Open / Verified] |
| [PROD-REQ-002] | [Requirement] | [Source or rationale] | [Risk ID or N/A] | [Method] | [Link] | [Status] |

### 5.1 Functional Requirements

[Add functional requirements to the table above or reference a controlled requirements specification.]

### 5.2 Performance Requirements

- [Response time]
- [Throughput]
- [Image-processing time]
- [Maximum data size]
- [Availability or reliability]
- [Other]

### 5.3 Safety Requirements

- [Safety-related requirement]
- [Warning or alarm behavior]
- [Fail-safe behavior]
- [Risk-control requirement]
- [Not applicable with rationale]

### 5.4 Cybersecurity Requirements

- [Authentication]
- [Authorization]
- [Encryption]
- [Audit logging]
- [Secure update]
- [Data integrity]
- [Third-party component management]
- [Not applicable with rationale]

### 5.5 Usability Requirements

- [User workflow]
- [Error prevention]
- [Warning clarity]
- [Accessibility]
- [Training or labeling]
- [Not applicable with rationale]

---

## 6. Product-Specific Technical Requirements

Use or remove the subsections below based on the product.

### 6.1 DICOM Requirements

| DICOM Service or Feature | Role | Supported? | Notes |
|---|---|---:|---|
| C-ECHO | [SCU / SCP] | [Yes / No] | [Notes] |
| C-STORE | [SCU / SCP] | [Yes / No] | [Notes] |
| Query/Retrieve | [SCU / SCP] | [Yes / No] | [Notes] |
| Modality Worklist | [SCU / SCP] | [Yes / No] | [Notes] |
| Storage Commitment | [SCU / SCP] | [Yes / No] | [Notes] |

### 6.2 Supported SOP Classes and Transfer Syntaxes

| Item | UID | Supported? | Notes |
|---|---|---:|---|
| [SOP Class or transfer syntax] | [UID] | [Yes / No] | [Notes] |

### 6.3 Hardware and Device Interfaces

| Hardware or Device | Interface | Supported Version | Safety Relevance | Notes |
|---|---|---|---|---|
| [Device] | [USB / serial / Ethernet / driver / SDK] | [Version] | [Yes / No] | [Notes] |

### 6.4 Image Processing or Reconstruction

| Function | Inputs | Outputs | Key Parameters | Verification Evidence |
|---|---|---|---|---|
| [Function] | [Inputs] | [Outputs] | [Parameters] | [Link] |

### 6.5 Database and Data Storage

| Data Store | Data Stored | Location | Retention | Backup/Recovery |
|---|---|---|---|---|
| [Database or folder] | [Data] | [Location] | [Retention] | [Method] |

### 6.6 Installer and Update Behavior

- Installer technology: [WiX / Inno Setup / MSI / other]
- Installation scope: [Per-machine / per-user]
- Required privileges: [Administrator / user]
- Upgrade behavior: [Description]
- Rollback behavior: [Description]
- Configuration migration: [Description]
- Uninstall behavior: [Description]
- Code-signing requirements: [Description]

---

## 7. Risk Analysis

Reference the applicable product-specific **Software Risk, Testing, Validation, and Release Workbook**.

| Field | Entry |
|---|---|
| Risk Analysis Required? | [Yes / No] |
| Risk Study Number | [SRA-PRODUCT-YYYY-NNN or N/A] |
| Workbook Location | [Controlled Google Drive link] |
| Related GitHub Issue | [Issue URL] |
| Risk Review Status | [Draft / Ready for review / Approved] |

### 7.1 Risk Areas to Consider

- Patient or operator injury
- Incorrect or delayed diagnosis
- Incorrect image, study, or patient association
- Loss, corruption, or unauthorized disclosure of data
- Incorrect device or hardware control
- Incorrect acquisition or exposure behavior
- Image-processing or reconstruction error
- Communication or network failure
- Installation or upgrade failure
- Cybersecurity vulnerability
- Use error or confusing user interface
- Inadequate warnings or error handling
- Third-party dependency failure
- [Other]

### 7.2 Risk-Control Traceability

| Risk Record ID | Hazard or Hazardous Situation | Risk Control | Requirement ID | Verification Evidence | Residual Risk Status |
|---|---|---|---|---|---|
| [Risk ID] | [Hazard] | [Control] | [Requirement] | [Link] | [Acceptable / Open] |

---

## 8. Cybersecurity and Data Protection

### 8.1 Data Classification

| Data Type | Stored? | Transmitted? | Sensitive? | Protection Method |
|---|---:|---:|---:|---|
| Patient information | [Yes / No] | [Yes / No] | [Yes / No] | [Method] |
| Credentials | [Yes / No] | [Yes / No] | [Yes / No] | [Method] |
| Images or studies | [Yes / No] | [Yes / No] | [Yes / No] | [Method] |
| Logs | [Yes / No] | [Yes / No] | [Yes / No] | [Method] |
| Configuration | [Yes / No] | [Yes / No] | [Yes / No] | [Method] |

### 8.2 Security Controls

- Authentication: [Description]
- Authorization: [Description]
- Least privilege: [Description]
- Encryption at rest: [Description]
- Encryption in transit: [Description]
- Audit logging: [Description]
- Secure configuration: [Description]
- Input validation: [Description]
- Dependency management: [Description]
- Vulnerability monitoring: [Description]
- Secure update and code signing: [Description]

### 8.3 Cybersecurity Review

| Field | Entry |
|---|---|
| Cybersecurity Review Required? | [Yes / No] |
| Review Date | [YYYY-MM-DD] |
| Reviewer | [Name and role] |
| Evidence | [Link] |
| Open Actions | [None or list] |

---

## 9. Verification and Validation

### 9.1 Testing Requisition

| Field | Entry |
|---|---|
| F-308 Testing Requisition Number | [STR-PRODUCT-YYYY-NNN] |
| Workbook Location | [Controlled Google Drive link] |
| Testing Scope | [Summary] |
| Testing Status | [Draft / In progress / Complete / Approved] |

### 9.2 Verification Activities

| Verification ID | Requirement or Feature | Method | Expected Result | Evidence | Result |
|---|---|---|---|---|---|
| [VER-001] | [Requirement/feature] | [Test / inspection / analysis] | [Expected result] | [Link] | [Pass / Fail / Open] |

### 9.3 Product-Specific Test Forms

| Form | Applicability | Record Location | Status |
|---|---|---|---|
| F-345 iScan NDT Software Release Validation | [Applicable / N/A] | [Google Forms record link] | [Status] |
| F-346 USB Programmer Software Release Validation | [Applicable / N/A] | [Google Forms record link] | [Status] |
| F-347 XCST Software Release Validation | [Applicable / N/A] | [Google Forms record link] | [Status] |
| F-348 XC2 Software Release Validation | [Applicable / N/A] | [Google Forms record link] | [Status] |
| F-349 XC1 Software Release Validation | [Applicable / N/A] | [Google Forms record link] | [Status] |
| F-372 CR API/SDK Software Release Validation | [Applicable / N/A] | [Google Forms record link] | [Status] |
| [Other controlled test form] | [Applicable / N/A] | [Link] | [Status] |

### 9.4 Software Validation

| Field | Entry |
|---|---|
| F-314 Validation Record ID | [VAL-PRODUCT-YYYY-NNN] |
| Validation Required? | [Yes / No] |
| Validation Scope | [Summary] |
| Intended Use Evaluated? | [Yes / No / N/A] |
| Intended Users Evaluated? | [Yes / No / N/A] |
| Intended Environment Evaluated? | [Yes / No / N/A] |
| Validation Evidence | [Controlled link] |
| Validation Decision | [Validated / Validated with conditions / Not validated / N/A] |

### 9.5 Test Environment

| Item | Configuration |
|---|---|
| Operating System | [Version] |
| Hardware | [Configuration] |
| Database | [Version] |
| Network | [Configuration] |
| Device or scanner | [Model/version] |
| Third-party software | [Version] |
| Test data | [Description] |

### 9.6 Deviations and Open Issues

| Issue or Deviation | Reference | Impact | Disposition | Status |
|---|---|---|---|---|
| [Issue] | [GitHub issue or record] | [Impact] | [Resolution or justification] | [Open / Closed] |

---

## 10. Requirements Traceability

| Requirement ID | Design Output or Implementation | Risk Record | Verification Record | Validation Record | Release |
|---|---|---|---|---|---|
| [REQ-001] | [File/class/module/PR] | [Risk ID or N/A] | [Test ID] | [Validation ID or N/A] | [Version/tag] |

---

## 11. Configuration and Release Management

### 11.1 Source Configuration

| Field | Entry |
|---|---|
| Repository | [URL] |
| Default Branch | [Branch] |
| Release Branch | [Branch or N/A] |
| Commit SHA | [SHA] |
| Release Tag | [Tag] |
| Submodules | [List or N/A] |
| Dependency Lock File | [Location or N/A] |

### 11.2 Build Configuration

| Item | Value |
|---|---|
| Development Environment | [Visual Studio/version or other] |
| Framework/Runtime | [.NET / C++ runtime / Java / other] |
| Build Configuration | [Release / Debug / other] |
| Target Platform | [x86 / x64 / ARM / Any CPU] |
| Build Script or Workflow | [Path or link] |
| CI/CD Workflow | [GitHub Action or N/A] |

### 11.3 Software Bill of Materials

| Component | Version | License | Source | Notes |
|---|---|---|---|---|
| [Component] | [Version] | [License] | [Source] | [Notes] |

### 11.4 Release Evidence

| Field | Entry |
|---|---|
| Release Candidate Issue | [GitHub issue URL] |
| F-315 Software Change Notice | [Google Form record link] |
| F-371 Release Approval Number | [REL-PRODUCT-YYYY-NNN] |
| Release Approval Record | [Controlled workbook link] |
| Installer or Package Location | [Location] |
| Installer Filename | [Filename] |
| Checksum | [SHA-256 or N/A] |
| Changelog | [Link] |
| GitHub Release | [Link] |

### 11.5 Release History

| Version | Tag | Release Date | Release Candidate | Validation Record | Release Approval | Notes |
|---|---|---|---|---|---|---|
| [Version] | [Tag] | [YYYY-MM-DD] | [Link] | [ID/link] | [ID/link] | [Notes] |

---

## 12. Known Issues and Limitations

| Issue | Reference | Impact | Workaround | Release Decision |
|---|---|---|---|---|
| [Known issue] | [GitHub issue] | [Impact] | [Workaround] | [Accepted / Must fix / Deferred] |

---

## 13. Post-Production Monitoring and Maintenance

### 13.1 Monitoring Sources

- Customer complaints
- Technical-support issues
- Production feedback
- CAPAs
- Field service records
- Cybersecurity advisories
- Dependency vulnerabilities
- Device logs
- GitHub issues
- [Other]

### 13.2 Monitoring Plan

| Monitoring Activity | Responsible Role | Frequency or Trigger | Record Location |
|---|---|---|---|
| [Activity] | [Role] | [Frequency/trigger] | [Location] |

### 13.3 Maintenance and Change Control

[Describe how software changes, bug fixes, enhancements, dependency updates, and emergency changes are controlled. Reference QP-046 and applicable GitHub issue and pull-request processes.]

---

## 14. Design Reviews and Approvals

### 14.1 Design Review Records

| Review | Date | Participants | Decision | Action Items | Record Location |
|---|---|---|---|---|---|
| [Review] | [YYYY-MM-DD] | [Names/roles] | [Approved / conditional / rejected] | [None or list] | [Link] |

### 14.2 Final Document Approval

| Role | Name | Decision | Date | Approval Evidence |
|---|---|---|---|---|
| Software Engineering | [Name] | [Approved / Rejected] | [YYYY-MM-DD] | [Link] |
| Software Manager | [Name] | [Approved / Rejected] | [YYYY-MM-DD] | [Link] |
| Quality Assurance | [Name] | [Approved / Rejected / N/A] | [YYYY-MM-DD] | [Link] |
| Regulatory Affairs | [Name] | [Approved / Rejected / N/A] | [YYYY-MM-DD] | [Link] |

---

## 15. Software Design File Index

| Evidence Type | Record Title | Repository or Location | Issue/PR Number | Version/Tag/Commit | Revision | Approval Date | Status | Notes |
|---|---|---|---|---|---|---|---|---|
| Intended Use | [Record] | [Location] | [Reference] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Requirements | [Record] | [Location] | [Reference] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Architecture | [Record] | [Location] | [Reference] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Risk Analysis | [F-316 Study] | [Workbook link] | [Issue] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Verification | [F-308/Test record] | [Workbook/link] | [Issue] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Validation | [F-314 record] | [Workbook link] | [Issue] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Design Review | [Review record] | [GitHub issue] | [Issue number] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Release Approval | [F-371 record] | [Workbook link] | [RC issue] | [Version] | [Revision] | [Date] | [Status] | [Notes] |
| Release | [GitHub release] | [Link] | [Reference] | [Tag] | [Revision] | [Date] | [Status] | [Notes] |
| Changelog | [Document] | [Location] | [Reference] | [Version range] | [Revision] | [Date] | [Status] | [Notes] |

---

## 16. Revision History

| Revision | Date | Description | Author | Reviewed By | Approved By |
|---|---|---|---|---|---|
| A | [YYYY-MM-DD] | Initial product software design file. | [Name] | [Name] | [Name] |

---

## Completion Checklist

- [ ] Product description and intended use are complete.
- [ ] Regulatory determination is documented and approved.
- [ ] Applicable standards and product relationships are identified.
- [ ] Software architecture and interfaces are documented.
- [ ] Requirements are uniquely identified and traceable.
- [ ] Applicable risk analysis is complete and linked.
- [ ] Cybersecurity and data-protection controls are documented.
- [ ] Verification evidence is complete and linked.
- [ ] Validation evidence is complete or justified as not applicable.
- [ ] Known issues and deviations are documented.
- [ ] Release configuration, tag, installer, checksum, and changelog are recorded.
- [ ] Required design reviews and approvals are complete.
- [ ] The Software Design File Index is current.
