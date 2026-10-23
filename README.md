# Botium-Toys---Controls-and-Compliance-
Internal security audit, risk assessment, and compliance evaluation (NIST CSF, PCI DSS, GDPR) for Botium Toys, completed as part of the Google Cybersecurity Certificate.

# 🛡️ Botium Toys: Internal Security Audit & Compliance Assessment

## 📌 Scenario & Business Context
**Botium Toys**, a growing e-commerce retail organization, recently experienced significant growth and expanded its digital footprint. However, the organization's IT infrastructure and security posture have not kept pace with this expansion. 

To maintain business continuity, protect sensitive customer data, and meet regulatory requirements, an internal security audit was conducted. The primary objective was to evaluate current security controls, assess organizational risk exposure, and align operations with key industry frameworks and compliance standards (NIST CSF, PCI DSS, GDPR, SOC 2).

---

## 📂 Project Structure & Artifacts

This repository contains three core deliverables from the internal security assessment:

1. 📑 **[Risk Assessment Report](./docs/Botium_Toys_Risk_Assessment.pdf)**
   * Outlines the organization's asset inventory, threat landscape, current vulnerability gaps, and potential risk impacts (financial, operational, and reputational).
2. 🗂️ **[Control Categories Overview](./docs/Control_Categories_Overview.pdf)**
   * Categorizes existing and proposed security controls across **Administrative**, **Technical**, and **Physical** domains, assessing their alignment with the **CIA Triad** (Confidentiality, Integrity, Availability).
3. ✅ **[Controls & Compliance Checklist](./docs/Controls_and_Compliance_Checklist.pdf)**
   * A granular compliance matrix evaluating Botium Toys against regulatory standards including **PCI DSS** (payment data), **GDPR** (data privacy), and **SOC 1/SOC 2** compliance criteria.

---

## 🔍 Audit Methodology: How I Completed This Project

The assessment was conducted in three structured phases:

### Phase 1: Risk & Vulnerability Analysis
* Conducted a thorough analysis of Botium Toys' existing infrastructure, user access protocols, and data processing workflows.
* Identified major security gaps, including unencrypted sensitive customer data at rest, lack of Multi-Factor Authentication (MFA), over-privileged user accounts, and outdated incident response procedures.

### Phase 2: Control Mapping & Categorization
* Categorized all identified security needs into **Administrative** (policies, training), **Technical** (encryption, firewalls, MFA), and **Physical** (locks, surveillance) controls.
* Ensured every control mapped directly to preserving the **CIA Triad** and aligned with the **NIST Cybersecurity Framework (NIST CSF)** functions (*Identify, Protect, Detect, Respond, Recover*).

### Phase 3: Compliance & Remediation Planning
* Assessed the impact of identified control failures against legal and regulatory standards:
  * **PCI DSS:** Evaluated cardholder data environment (CDE) protection mechanisms.
  * **GDPR:** Evaluated compliance regarding consumer PII data rights and processing policies.
* Prioritized actionable, cost-effective remediation strategies for management to reduce risk exposure.

---

## 💡 Key Findings & Remediation Recommendations

| Domain | Identified Risk / Deficit | Recommended Mitigation Strategy |
| :--- | :--- | :--- |
| **Access Control** | Single-factor authentication on critical internal systems; excessive user privileges. | Implement mandatory **Multi-Factor Authentication (MFA)** and enforce the **Principle of Least Privilege (PoLP)**. |
| **Data Protection** | Unencrypted cardholder data and PII stored on local workstations/databases. | Enforce **AES-256 encryption** for data at rest and **TLS 1.3** for data in transit to satisfy PCI DSS & GDPR. |
| **Governance & Policy** | Outdated incident response plans and missing formal security awareness training. | Develop a formalized **Incident Response Playbook** and implement mandatory quarterly cybersecurity awareness training. |
| **Physical Security** | Inadequate physical access controls surrounding server rooms. | Install biometric/badge access control systems and high-definition CCTV monitoring. |

---

## 🎓 Key Learnings & Takeaways

Through this project, I strengthened my practical understanding of:
* **GRC (Governance, Risk, and Compliance):** How technical vulnerabilities directly convert into business and legal risks under frameworks like PCI DSS and GDPR.
* **NIST CSF Application:** Translating abstract security frameworks into tangible operational controls for a business.
* **Risk Prioritization:** Learning to balance business objectives with security constraints, providing executive stakeholders with practical remediation paths rather than simple "pass/fail" results.
* **Defense-in-Depth:** Understanding how combining administrative, technical, and physical controls creates a resilient security architecture.

---

## 🛠️ Frameworks & Standards Applied
* **Frameworks:** NIST Cybersecurity Framework (NIST CSF)
* **Regulations & Standards:** PCI DSS | GDPR | SOC 1 / SOC 2
* **Core Concepts:** Risk Assessment, Control Mapping, CIA Triad, Principle of Least Privilege (PoLP), Threat Modeling

---

## 👤 Author
* **Name:** Aditya Salish
* **Portfolio / Credentials:** Google Cybersecurity Professional Certificate
* **LinkedIn:** https://www.linkedin.com/in/adityasalish/
