# Cybersecurity Assessment & Posture Reinforcement  
## NIST Cybersecurity Framework (CSF) 2.0 – Dental Practice Case Study

**Organization:** [Redacted] Family Dental
**Location:** Fontana, CA
**Practice Size:** 1 Dentist, 3 Staff (Office Manager, Dental Assistant, Hygienist)  
**Engagement Type:** Independent Cybersecurity Assessment & Roadmap  
**Framework Used:** NIST Cybersecurity Framework (CSF) 2.0  

**Reference:**  
NIST Cybersecurity Framework 2.0  
https://www.nist.gov/cyberframework

---

## Introduction

This engagement involved assessing and improving the cybersecurity posture of a small, independently owned dental practice handling **electronic Protected Health Information (ePHI)**. The objective was to evaluate the practice’s current cybersecurity posture, identify material risks, and develop a pragmatic improvement roadmap aligned with the **NIST Cybersecurity Framework (CSF) 2.0**, while remaining realistic for a low-budget, non-technical environment.

The assessment was conducted using:
- Staff interviews  
- Review of existing IT practices  
- Observation of daily workflows  
- Configuration review of systems and cloud services  

Findings were mapped to CSF outcomes using a **pass / partial / fail** model. Recommendations focused on **HIPAA-aligned safeguards**, operational resilience, and risk reduction rather than enterprise-grade tooling.

The engagement began with a short briefing to explain cybersecurity risk in plain language and concluded with prioritized, achievable remediation steps.

---

## CSF Core Functions Overview

The NIST CSF Core Functions provide a lifecycle view of cybersecurity risk management:

| Function | Purpose |
|--------|--------|
| **GOVERN** | Establish risk strategy, roles, and accountability |
| **IDENTIFY** | Understand assets, data, and risks |
| **PROTECT** | Safeguard systems and patient data |
| **DETECT** | Identify cybersecurity events |
| **RESPOND** | Contain and manage incidents |
| **RECOVER** | Restore operations and data |

---

## Governance Tiers

CSF 2.0 defines **Implementation Tiers** to describe the maturity of cybersecurity governance.

### Current Profile — Tier 1: Partial
- Cybersecurity handled reactively and informally  
- No documented policies or risk process  
- Heavy reliance on external IT vendor  
- Security decisions driven by convenience and cost  

### Target Profile — Tier 2: Risk-Informed
- Basic governance and policies documented  
- Security risks considered in operational decisions  
- Clear responsibility assigned for cybersecurity tasks  
- Controls aligned with HIPAA Security Rule safeguards  

> For a small dental practice, Tier 2 represents a **realistic and sustainable target**.

---

## Current State Summary

### Environment Overview
- Cloud-based dental practice management software  
- Microsoft 365 email and file storage  
- 4 Windows workstations  
- Networked dental imaging system  
- Shared Wi-Fi for staff and patients  
- Third-party IT support provider (break/fix model)

### Key Observations

| Area | Observation |
|----|------------|
| Governance | No formal cybersecurity or HIPAA security policies |
| Asset Management | No documented inventory of devices or systems |
| Data Handling | ePHI stored in cloud apps and local imaging systems |
| IAM | Shared logins used for dental software |
| MFA | Not enabled on email or cloud services |
| Backups | Cloud backups enabled, but not periodically tested |
| Monitoring | No centralized logging or alerting |
| Training | Informal, verbal HIPAA reminders only |
| Incident Response | No defined process or contacts |

---

## Findings & Recommendations by CSF Function

---

## GOVERN

**Findings**
- No documented cybersecurity roles or responsibilities  
- HIPAA Security Rule requirements understood informally but not documented  
- No risk assessment or risk acceptance process  

**Recommendations**
- Designate Office Manager as Security & HIPAA Coordinator  
- Document a simple cybersecurity and HIPAA security policy (5–7 pages)  
- Conduct annual lightweight risk assessment focused on ePHI  

---

## IDENTIFY

**Findings**
- No formal asset inventory  
- No classification of systems storing ePHI  
- Third-party vendors not evaluated for security risk  

**Recommendations**
- Create and maintain an asset inventory (devices, software, vendors)  
- Identify systems handling ePHI and label them as high impact  
- Maintain a list of critical vendors and their access level  

---

## PROTECT

**Findings**
- Shared user accounts in practice management software  
- No MFA for email or cloud services  
- Patient Wi-Fi not segmented from business network  
- Limited security awareness training  

**Recommendations**
- Implement unique user accounts for all staff  
- Enable MFA on Microsoft 365 and cloud applications  
- Separate patient Wi-Fi from business systems  
- Conduct short quarterly security awareness refreshers  

**Protect Metrics**

| Control | Before | After |
|------|-------|------|
| MFA enabled | No | Yes |
| Shared accounts | Yes | No |
| Network segmentation | No | Yes |
| Staff trained | Informal | Quarterly |

---

## DETECT

**Findings**
- No centralized monitoring or alerting  
- Relies solely on antivirus notifications  

**Recommendations**
- Enable audit logging in Microsoft 365  
- Configure email security alerts for suspicious logins  
- Periodically review security alerts with IT provider  

---

## RESPOND

**Findings**
- No documented incident response process  
- Staff unsure who to notify in case of breach or ransomware  

**Recommendations**
- Create a simple incident response checklist (1–2 pages)  
- Define escalation contacts (IT vendor, dentist, legal counsel)  
- Include HIPAA breach notification considerations  

---

## RECOVER

**Findings**
- Backups exist but restoration not tested  
- No communication plan for extended outages  

**Recommendations**
- Test data restoration annually  
- Document recovery priorities (patient scheduling, imaging, billing)  
- Define patient communication approach for major disruptions  

---

## Conclusion

This dental practice’s cybersecurity posture was **informal but typical** for a small healthcare provider. While no immediate evidence of compromise was found, several gaps posed elevated risk to **patient data confidentiality and operational continuity**.

By adopting the **NIST Cybersecurity Framework 2.0** as a practical roadmap—and targeting **Tier 2: Risk-Informed**—the practice can materially reduce cyber and HIPAA risk without excessive cost or complexity.

The most impactful improvements included:
- Enabling MFA  
- Eliminating shared accounts  
- Clarifying responsibility for security  
- Establishing basic incident response and recovery procedures  

This case study demonstrates how nationally recognized frameworks can be **right-sized** for small healthcare organizations while still providing measurable risk reduction.

---
