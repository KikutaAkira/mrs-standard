# MRS — Micro Robot Standard

**Version:** 0.1  
**Status:** DRAFT

MRS is an open interoperability standard for micro-robot parts, assembly, certification, and lifecycle management.  
This repository is the working source of truth for the technical core and anti-capture governance rules.

## 1. Technical Core

MRS Core will define the minimum common specifications required for interoperable micro-robot components.

Initial scope:
- Part / Device ID
- Mechanical interface
- Electrical interface
- Power
- Communication
- Version identification
- Basic compatibility requirements

## 2. Constitution & Governance

MRS must not be controlled by a single company or corporate group.

Draft anti-capture rules:
- Corporate-group voting cap: **10%**
- Funding dependency on a single corporate group: **15% maximum**
- Changes to protected constitutional rules: **90% approval**
- Important MRS Core changes: **75% approval**
- Certification and Registry authority must not be controlled by a single corporate group

These values are provisional and require legal and governance review.

## 3. Vendor Extension Rules

Vendor extensions are allowed, but they must:
- remain clearly separate from MRS Core
- not modify, overwrite, or replace MRS Core
- not be marketed as part of MRS Core
- preserve Core interoperability when the extension is disabled

## 4. Compatibility Test

Initial compatibility tests:

- **CT-001 Core Preservation**  
  Vendor extensions must not modify, overwrite, or replace MRS Core.

- **CT-002 Extension Independence**  
  MRS Core functions must operate correctly with vendor extensions disabled.

- **CT-003 Honest Identification**  
  Vendor-specific functions must not be represented as “MRS Standard” or “MRS Core”.

Additional mechanical, electrical, protocol, safety, and version tests will be added.

## 5. MRS Certified

Passing compatibility tests alone does not grant the right to use “MRS Certified”.

Proposed certification chain:

**Compatibility Test PASS → Official Certification → Official Registry ACTIVE → MRS Certified mark use permitted**

Products that are SUSPENDED, REVOKED, or not officially registered may not use the MRS Certified name or certification mark.

## 6. Official Registry

The Official MRS Registry will provide a verifiable record of certified products.

Minimum registry fields:
- Registry ID
- Vendor / Organization
- Product / Model
- MRS Core Version
- Compatibility Test Version
- Certification Status: ACTIVE / SUSPENDED / REVOKED

No single company or corporate group may unilaterally control registration, modification, or deletion decisions.

## 7. Trademark & Brand Protection

The MRS Core specification is intended to be openly implementable.

However, use of:
- **MRS**
- **MRS Certified**
- official certification marks / logos

will be governed separately from the technical specification.

Only products meeting official certification and Registry requirements may use the MRS Certified designation.

---

## Current Phase

**MRS v0.1 — Governance + Compatibility baseline**

Next priorities:
1. Freeze the v0.1 governance baseline
2. Define mechanical / electrical / communication Core requirements
3. Expand compatibility test cases
4. Define certification and Registry operating rules
5. Perform prior trademark research before filing

> All specifications and governance thresholds in this repository are draft proposals and have not yet been legally validated.
