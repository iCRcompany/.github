# 12 – Software Configuration

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

This section documents the software configuration for [Product Name], including the repository, source identification, build environment, third-party components, and software bill of materials. This section provides the information needed to reproduce the software release.

## Scope

Describe the products, versions, components, or activities covered by this section.

## Responsibilities

Identify the roles responsible for preparing, reviewing, approving, and maintaining this section.

---

## Source Control

- **Repository:** [Repository Name]
- **Repository URL:** [Repository URL or controlled location reference]
- **Source Branch:** [Branch Name]
- **Release Tag:** [Release Tag]
- **Commit SHA:** [Commit SHA]
- **Submodules:** [List submodule names, repositories, and pinned commits, or state None]

---

## Build Environment

- **Operating System:** [Build OS name and version, e.g., Ubuntu 22.04, Windows Server 2022]
- **Compiler or Interpreter:** [Compiler or interpreter name and version, e.g., GCC 12.3, Python 3.11.4]
- **IDE or Build Tool:** [IDE or build tool name and version, e.g., Visual Studio 2022, CMake 3.26]
- **Target Framework:** [Target framework name and version, e.g., .NET 8.0, CUDA 12.2]
- **Build Script or Instructions:** [Reference to build instructions in the repository or controlled location]
- **CI/CD System:** [CI/CD system name and version, e.g., GitHub Actions, Jenkins]

---

## Third-Party Libraries and Components

List all third-party libraries, open-source components, and external dependencies included in the software.

| Configuration Item | Name | Version | License | Source or Location | Approved Version | Notes |
|---|---|---|---|---|---|---|
| CI-001 | [Library or component name] | [Version] | [License type] | [Package manager or source URL] | [Approved version] | [Notes] |

---

## Configuration Item Table

| Configuration Item | Name | Version | Source or Location | Approved Version | Notes |
|---|---|---|---|---|---|
| CI-001 | [Configuration item name] | [Version] | [Repository path or package source] | [Approved version] | [Notes] |

---

## Operating System and Platform

- **Target Operating System:** [Target OS name and version(s)]
- **Supported Platforms:** [List of supported platforms, e.g., Windows 10/11, macOS 13+]
- **Hardware Requirements:** [Minimum hardware requirements]

---

## Installer and Packaging

- **Installer Tool:** [Installer tool name and version, e.g., NSIS, Inno Setup, WiX]
- **Installer Version:** [Version of the installer package]
- **Installer Location:** [Release location or controlled document location]

---

## Code Signing

- **Code Signing Process:** [Describe the code signing process or reference the applicable SOP]
- **Certificate Authority:** [Certificate authority name]
- **Certificate Expiry:** [Certificate expiry date — enter only if signing has been performed]
- **Signing Status:** [Signed / Not signed / Pending]

---

## Configuration Files

- **Configuration Files:** [List configuration files, their purpose, and location]
- **Default Configuration:** [Reference to default configuration or documentation]
- **Configuration Management:** [Describe how configuration changes are controlled]

---

## Database Version

- **Database System:** [Database system name and version, e.g., PostgreSQL 15.3, SQLite 3.42]
- **Schema Version:** [Database schema version or migration reference]
- **Migration Instructions:** [Reference to migration instructions or scripts]

---

## Build Instructions

- **Build Instructions Location:** [Repository path or controlled document location]
- **Build Command:** [e.g., `make release` or `dotnet build --configuration Release`]
- **Build Verification:** [Describe how to verify a successful build]

---

## Software Bill of Materials (SBOM)

- **SBOM Format:** [e.g., SPDX 2.3, CycloneDX 1.5]
- **SBOM Location:** [Repository path or controlled document location]
- **SBOM Generation Tool:** [Tool name and version used to generate the SBOM]

---

## Archive Location

- **Release Archive Location:** [Controlled document management system or release storage location]
- **Archive Retention Policy:** [Retention period or reference to applicable policy]

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
