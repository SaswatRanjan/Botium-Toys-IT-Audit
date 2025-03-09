# Botium Toys IT Audit

## **Project Overview**
This repository contains an internal IT audit for Botium Toys, a growing toy company expanding its online presence. The audit follows the **NIST Cybersecurity Framework (NIST CSF)** and assesses compliance with **PCI DSS, GDPR, and SOC 2**.

## **Files in this Repository**
- `reports/IT_Audit_Report.md` - Detailed audit findings and recommendations.
- `reports/Controls_Checklist.xlsx` - Completed compliance checklist.
- `README.md` - Overview of the audit process.

## **Key Findings**
- **Missing encryption for payment data** (Non-compliant with PCI DSS).
- **No Intrusion Detection System (IDS)** (High security risk).
- **Weak password policies** (Potential for account compromise).
- **No disaster recovery plan** (Data loss risk).

## **Recommendations**
1. Encrypt customer payment data to meet PCI DSS standards.
2. Deploy an Intrusion Detection System (IDS) for threat monitoring.
3. Strengthen password policies to require at least 12-character passwords.
4. Implement a disaster recovery plan with regular backups.

## **How to Use This Repository**
1. Clone the repository:
   ```sh
   git clone https://github.com/SaswatRanjan/Botium-Toys-IT-Audit.git
