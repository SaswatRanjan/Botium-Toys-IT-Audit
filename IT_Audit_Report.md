 Botium Toys Internal IT Audit Report

 **1. Introduction**
Botium Toys is a U.S.-based toy company experiencing rapid online growth. This audit aims to assess the company's cybersecurity posture and ensure compliance with industry standards such as NIST CSF, PCI DSS, and GDPR.

 **2. Scope of the Audit**
The audit covers:
- IT infrastructure (on-premises and cloud services)
- Network security (firewalls, IDS, encryption)
- Employee access controls
- Compliance with regulatory standards (PCI DSS, GDPR)
- Disaster recovery and data protection measures

 **3. Risk Assessment Summary**
| **Risk** | **Impact** | **Likelihood** | **Risk Score (1-10)** |
|----------|-----------|---------------|----------------|
| Lack of encryption for credit card data | High | High | 9 |
| No intrusion detection system (IDS) | High | Medium | 8 |
| Weak password policies | Medium | High | 7 |
| No disaster recovery plan | High | High | 9 |
| All employees have unrestricted data access | High | High | 8 |

 **4. Findings**
 **✅ Implemented Controls**
- Firewalls with defined security rules
- Antivirus software with regular monitoring
- CCTV surveillance for physical security

 **❌ Missing or Weak Controls**
- **No encryption** for customer payment data
- **No IDS/IPS system** for threat detection
- **No disaster recovery plan**
- **Weak password policies** (not enforcing strong passwords)
- **Lack of least privilege access control**

 **5. Compliance Gaps**
| **Compliance Standard** | **Requirement** | **Status** |
|------------------------|----------------|-----------|
| PCI DSS | Encrypt cardholder data | ❌ Not Implemented |
| PCI DSS | Restrict data access to authorized users | ❌ Not Implemented |
| GDPR | Notify EU customers of breaches within 72 hours | ✅ Implemented |
| GDPR | Enforce privacy policies and documentation | ✅ Implemented |
| SOC 2 | User access policies for PII data | ❌ Not Implemented |

 **6. Recommendations**
1. **Implement Data Encryption:** Encrypt all sensitive data, especially payment information.
2. **Deploy an Intrusion Detection System (IDS):** Monitor and alert for suspicious activity.
3. **Enforce Stronger Password Policies:** Require complex passwords and use a password manager.
4. **Implement Least Privilege Access:** Restrict access to critical systems based on job roles.
5. **Develop a Disaster Recovery Plan:** Ensure backups and recovery procedures are in place.

 **7. Conclusion**
Botium Toys needs to improve its security by implementing missing controls and aligning with industry compliance standards. Addressing these gaps will reduce risks and enhance customer trust.

---