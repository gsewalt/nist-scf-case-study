# Cybersecurity Assessment & Posture Reinforcement Using NIST Cybersecurity Framework (CSF) 2.0

## Introduction

This project involved assessing SewaltCorp’s cybersecurity posture and developing a program aligned to the [NIST CSF 2.0](https://www.nist.gov/publications/nist-cybersecurity-framework-csf-20).  
I was provided with a “current state” report reflecting interviews, documentation, and initial observations. Using the CSF as a baseline, I performed a pass/fail assessment across each category and mapped findings against desired outcomes.  

The engagement began with a short stakeholder briefing to explain the framework and roadmap. It concluded with a comprehensive set of recommendations and procedures aimed at moving SewaltCorp from its current state to a mature, adaptive security posture.  

<img height="1000" alt="image" src="https://github.com/user-attachments/assets/8797b396-7290-4969-a6e9-cbb48ee2aa4c" />


---

## CSF Core Functions

The CSF Core Functions — **GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, RECOVER** — represent the highest-level outcomes of an effective cybersecurity program.

| Function | Description |
|----------|-------------|
| ![govern](https://github.com/user-attachments/assets/c536c78f-b8d2-4988-a1ad-ea1b0222bd41) | Establish, communicate, and monitor risk management strategy and policy. |
| ![identify](https://github.com/user-attachments/assets/bd218bc5-9048-4d91-96fd-77aba367d87b) | Understand current cybersecurity risks. |
| ![protect](https://github.com/user-attachments/assets/f6554061-0d01-49e9-91df-b102eb4b8ac7) | Implement safeguards to manage risks. |
| ![detect](https://github.com/user-attachments/assets/26e591c9-9ee6-454f-9f5b-37062bec1d0c) | Identify and analyze potential attacks. |
| ![respond](https://github.com/user-attachments/assets/bfdf2e21-ced1-4767-8ac6-4ec982b6f5e3) | Take appropriate actions during an incident. |
| ![recover](https://github.com/user-attachments/assets/10ef5d64-da8b-41df-a0fe-56acb244fd1c) | Restore affected assets and operations. |

---

## Governance Tiers

CSF 2.0 defines tiers to measure rigor in cybersecurity risk governance and management.  

- **Current Profile — Tier 1: Partial**  
  Risk strategy is ad hoc, awareness is limited, and governance is fragmented. Cyber risks are not consistently shared or considered at the organizational level. Supplier and third-party risks are largely unmanaged.

- **Target Profile — Tier 4: Adaptive**  
  Cybersecurity is integrated into enterprise risk management. Executives treat it alongside financial and operational risks. Continuous improvement, near real-time risk awareness, and advanced practices enable SewaltCorp to adapt to a dynamic threat landscape.

At every stage, the guiding principle is the **CIA Triad** — ensuring confidentiality, integrity, and availability of information assets.  

![cia](https://github.com/user-attachments/assets/5b8e35de-2c04-4de8-a82c-bb526a3f6f5c)

---

<details close>
<summary><h3>SewaltCorp Current State Report (Click to expand)</h3></summary>

**Cybersecurity Team**  
- Analyst: Generalist, reactive incident handling. Reports to IT Manager.  
- Network Engineer: Firewall administration. Reports to Network Team Lead.  
- Cybersecurity Consultant: (my role) reporting initially to IT Manager.  

**Key Observations**  
- **Governance**: CEO has business strategy, but no cybersecurity strategy or defined roles.  
- **Assets**: Spreadsheet inventory of laptops; no asset classification; all data in Azure/Office 365.  
- **Continuity**: Documented DR and BCP with regular testing. Backups in place.  
- **Vulnerability Management**: Owns Qualys but scans are ad hoc. No formal program.  
- **Risk Management**: No cyber risk process; only financial risk covered.  
- **Third-Party Risk**: No supplier risk management; procurement handles contracts.  
- **IAM**: Active Directory used, but no PAM, no MFA, shared admin accounts. VPN without MFA.  
- **Network Security**: Palo Alto firewalls in place, updated and segmented network.  
- **Physical Security**: Strong CCTV, vetting, and 24/7 monitoring.  
- **Data Security**: No DLP. All critical data cloud-hosted.  
- **Policies**: Generic IT policy only. No formal infosec or data governance.  
- **Detection/Response**: No SIEM. Response limited to Microsoft Defender alerts.  
- **Awareness**: One-time web training during induction; no ongoing program.  

</details>

---

## Findings & Recommendations

### Identify
- Asset inventory incomplete (no IP addresses or classification).  
- No third-party risk management.  
- No cybersecurity roles and responsibilities defined.  

**Recommendations**:  
- Implement vulnerability management with authenticated scans.  
- Establish asset classification by criticality.  
- Formalize third-party risk program and role accountability.  

---

### Protect
- Weak IAM (no MFA, shared admin accounts, poor offboarding).  
- Minimal training. No executive or third-party awareness program.  
- No DLP or data classification.  
- No change/configuration management.  

**Recommendations**:  
- Adopt IAM with MFA, role-based access, and offboarding procedures.  
- Launch recurring training for staff, execs, and third parties.  
- Implement DLP and data classification.  
- Formalize change control and HR-linked offboarding.  

---

### Detect
- No SIEM or effective monitoring.  
- Reliance on Microsoft Defender alerts only.  

**Recommendations**:  
- Deploy SIEM aligned to [MITRE ATT&CK](https://attack.mitre.org/).  
- Establish detection processes, escalation points, and periodic penetration testing.  

---

### Respond
- No formal IR plan, playbooks, or escalation.  

**Recommendations**:  
- Develop IR policy and plans (aligned with SANS model).  
- Define communication protocols with regulators, peers, and stakeholders.  
- Incorporate forensic analysis into investigations.  
- Continuously test and improve the response process.  

---

### Recover
- Recovery processes exist but lack coordinated communication.  

**Recommendations**:  
- Formalize recovery communications with ISPs, vendors, CSIRTs, and affected stakeholders.  
- Establish policy for reputational risk management post-incident.  

---

## Conclusion

SewaltCorp’s current posture is reactive and siloed (Tier 1: Partial). By adopting the NIST CSF 2.0 as a roadmap, supported by frameworks like MITRE ATT&CK, NIST 800-53, and OWASP, SewaltCorp can evolve toward an adaptive, risk-informed program (Tier 4).  

The path forward centers on governance, continuous monitoring, vulnerability management, and integrating security into the culture of the organization.  
