# Enterprise Privacy & ROPA Framework

A practical, Excel-based framework designed for Privacy Officers and IT Managers to maintain GDPR Article 30 compliance and track Data Subject Access Requests (DSARs).

## The Problem
Under GDPR (Europe) and the DPDP Act (India), organizations must document every system that processes Personal Identifiable Information (PII). Most small businesses do this in scattered Word documents that are impossible to audit.

## The Solution
This repository provides a structured methodology and two ready-to-use trackers:
1. **[Methodology Guide](./00_GDPR_DPDP_Methodology.md):** Compares GDPR and DPDP, and explains the data mapping lifecycle.
2. **[ROPA Register](./01_Enterprise_ROPA_Register.xlsx) / ([.csv](./01_Enterprise_ROPA_Register.csv)):** Maps processing activities, legal bases, and data retention periods.
3. **[DSAR Tracker](./02_DSAR_Tracker.xlsx) / ([.csv](./02_DSAR_Tracker.csv)):** Tracks user access and erasure requests against the mandatory 30-day deadline.

## 📊 Sample View: ROPA Register

| ROPA ID | Processing Activity | Data Subject | Legal Basis | Retention Period |
| :--- | :--- | :--- | :--- | :--- |
| ROPA-001 | Employee Payroll | Employees | Contractual Necessity | 7 years post-termination |
| ROPA-002 | Website Analytics | Visitors | Legitimate Interest | 14 months |

## 📊 Sample View: DSAR Tracker

| Request ID | Request Type | Deadline | Status |
| :--- | :--- | :--- | :--- |
| DSAR-001 | Access | 2026-12-01 | 🟢 Completed |
| DSAR-002 | Erasure | 2026-12-10 | 🟡 Open |

## Author
Built by Piyush Gahlawat. For more of my work, see my [Vendor Risk Framework](https://github.com/Piyush-Gahlawat/vendor-risk-framework) and [IT Asset Register](https://github.com/Piyush-Gahlawat/it-asset-license-register).