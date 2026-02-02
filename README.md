# Security Audit Report: Botium Toys

## Project Overview
This project consists of a comprehensive internal security audit for **Botium Toys**, a fictional company. The audit was completed as part of the **Google Cybersecurity Professional Certificate** to demonstrate proficiency in risk assessment, control implementation, and compliance alignment.

## Objective
The primary goal was to assess the organization's security posture, identify critical vulnerabilities in their digital presence, and recommend specific security controls to mitigate risks and ensure compliance with industry standards.

## Scope & Frameworks
- **Scope:** Entirety of Botium Toys' internal and external systems (User permissions, Legacy software, Financial data handling).
- **Frameworks Used:** 
  - [NIST Cybersecurity Framework (CSF)](https://www.nist.gov)
  - [GDPR (General Data Protection Regulation)](https://gdpr-info.eu)
  - [PCI DSS (Payment Card Industry Data Security Standard)](https://www.pcisecuritystandards.org)

## Key Audit Findings
- **Access Control:** Identified lack of "Least Privilege" protocols; users had excessive permissions.
- **Vulnerability Management:** Discovery of outdated legacy systems lacking recent security patches.
- **Compliance Gaps:** Found inconsistencies in encryption for customer PII (Personally Identifiable Information).

## Recommendations
1. **Implement MFA:** Multi-factor authentication for all internal employee accounts.
2. **Hardening Systems:** Decommissioning or patching legacy software to reduce the attack surface.
3. **Encryption:** Enforce end-to-end encryption for all data at rest and in transit to meet PCI DSS requirements.

## Files in this Repository
- `Controls and Compliance_Checklist .pdf`: Alignment mapping with GDPR and PCI DSS.

---
*Note: This is a portfolio activity from the Google Cybersecurity Professional Certificate program.*

