# Cybersecurity Audit: Internal Risk Assessment for Botium Toys

## 📝 Project Note
---
**NOTE:** This project is a practical exercise from a cybersecurity professional training program.
- **Date:** January 2026
- **Scenario:** This audit is based on a fictional case study of a retail company ("Botium Toys") to demonstrate skills in internal auditing, risk assessment, and compliance gap analysis using the NIST Cybersecurity Framework (CSF).
---

## 📋 Project Overview
The scope of this audit encompasses the entire security program at Botium Toys. The primary goal was to assess existing assets and complete a controls and compliance checklist to identify necessary implementations to improve the company’s overall security posture.

## 🔍 Audit Findings & Risk Assessment
The current risk score for Botium Toys is **8/10**, which is considered high. This score is driven by a significant lack of critical security controls and non-adherence to several compliance best practices.

### Key Observations:
* **Access Control:** All employees currently have access to sensitive internal data, including customer PII/SPII and cardholder information.
* **Data Protection:** Encryption is not utilized for customers' credit card information during acceptance, processing, or storage.
* **Authentication:** Password requirements are nominal and do not meet modern complexity standards.
* **Resilience:** There are no disaster recovery plans or backups for critical data.

## 🛠️ Controls Assessment
Below is the evaluation of current cybersecurity controls based on the audit:

| Control | Status | Category | Type |
| :--- | :--- | :--- | :--- |
| **Least Privilege** | ❌ NO | Administrative | Preventative |
| **Disaster Recovery Plans** | ❌ NO | Administrative | Corrective |
| **Firewall** | ✅ YES | Technical | Preventative |
| **Intrusion Detection System (IDS)** | ❌ NO | Technical | Detective |
| **Backups** | ❌ NO | Technical | Corrective |
| **Antivirus Software** | ✅ YES | Technical | Corrective |
| **Encryption** | ❌ NO | Technical | Deterrent |
| **Password Management System** | ❌ NO | Technical | Preventative |
| **CCTV Surveillance** | ✅ YES | Physical | Preventative/Detective |
| **Fire Detection/Prevention** | ✅ YES | Physical | Detective/Preventative |

## ⚖️ Compliance Checklist
The following table summarizes the company's adherence to regulatory standards:

| Regulation | Adherence | Key Finding |
| :--- | :--- | :--- |
| **PCI DSS** | ❌ NO | Unauthorized access to credit card data and lack of encryption procedures. |
| **GDPR** | ⚠️ PARTIAL | A 72-hour breach notification plan exists, but data classification is missing. |
| **SOC Type 1/2** | ❌ NO | Sensitive data is not private across the organization and user access policies are weak. |

## 💡 Strategic Recommendations
To mitigate the identified risks and improve security posture, the following actions are recommended:

1. **Implement Identity and Access Management (IAM):** Establish Least Privilege and Separation of Duties to ensure employees only access data necessary for their roles.
2. **Enforce Data Encryption:** Deploy encryption for all sensitive customer data, especially credit card information, to comply with PCI DSS.
3. **Enhance Network Monitoring:** Install an Intrusion Detection System (IDS) to identify anomalous traffic that may bypass the firewall.
4. **Establish Business Continuity:** Develop a formal Disaster Recovery Plan and implement a regular schedule for Critical Data Backups.
5. **Strengthen Password Policies:** Deploy a centralized password management system to enforce minimum complexity requirements.
