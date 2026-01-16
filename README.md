# grc-internal-audit-project
Internal cybersecurity audit and risk assessment for a retail scenario, focusing on NIST CSF, PCI DSS, and GDPR compliance.

## Introduction
The scope of this audit is the entire security program at Botium Toys. The goal is to assess existing assets and complete a controls and compliance checklist to determine necessary implementations to improve the company's security posture.
+1
---
**NOTE:** This project is a practical exercise from a cybersecurity training program. 
- **Date:** January 2026
- **Scenario:** The audit is based on a fictional case study of a toy company ("Botium Toys") to demonstrate internal audit skills, risk assessment, and compliance gap analysis.
---
## Audit Findings
Based on the risk assessment, the company currently has a risk score of 8/10. Key observations include:
+1


 Assets: Management of accounting, database, ecommerce, and inventory systems.


 Access Control: Employees currently have access to sensitive cardholder data and customer PII/SPII.


 Encryption: Not currently used for credit card information.


 Compliance: The IT department has a plan for 72-hour breach notification for E.U. customers (GDPR) , but lacks sufficient controls for PCI DSS.
+1
### Compliance Evaluation

| Regulation | Adherence | Key Finding |
| :--- | :--- | :--- |
| **PCI DSS** | ❌ NO | [cite_start]Lack of encryption and unauthorized access to cardholder data[cite: 73, 74]. |
| **GDPR** | ⚠️ PARTIAL | [cite_start]72-hour breach notification plan exists, but data classification is needed[cite: 81, 82]. |
| **SOC Type 1/2** | ❌ NO | [cite_start]Confidentiality and integrity controls for sensitive data are missing[cite: 73, 75]. |

### Control Assessment Checklist

| Control | Status | Category | Type |
| :--- | :--- | :--- | :--- |
| **Least Privilege** | ❌ NO | Administrative | Preventative |
| **Disaster Recovery Plan** | ❌ NO | Administrative | Corrective |
| **Firewall** | ✅ YES | Technical | Preventative |
| **IDS** | ❌ NO | Technical | Detective |
| **Backups** | ❌ NO | Technical | Corrective |
| **Antivirus Software** | ✅ YES | Technical | Corrective |
| **CCTV Surveillance** | ✅ YES | Physical | Preventative/Detective |
