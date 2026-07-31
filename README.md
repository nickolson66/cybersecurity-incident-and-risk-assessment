# Enterprise Incident Response & Cybersecurity Risk Assessment

## 📌 Executive Summary
This repository contains a real-world, anonymized **Incident Response (IR) Summary** and a subsequent **Cybersecurity Posture & Risk Assessment** for an enterprise environment. 

The project documents the end-to-end lifecycle of a cloud identity compromise—from initial detection and containment to technical postmortem analysis, regulatory risk evaluation, and long-term remediation planning.

---

## 🛠️ Key Technical Focus Areas

* **Incident Analysis & Containment:** 
  * Cloud identity breach via legacy password authentication (Microsoft Entra ID / Exchange Online).
  * Rapid incident response: credential reset, active session revocation, and global MFA enforcement.
  * Mitigation of persistent attacker access (malicious inbox diversion rule removal).
* **Identity & Access Management (IAM) Hardening:**
  * Transitioning from single-factor authentication to phishing-resistant MFA.
  * Disambiguating shared local/cloud credentials to eliminate lateral movement risks.
  * Drafted recommendations for Location-Based Conditional Access Policies.
* **Endpoint Protection & Visibility:**
  * Identifying critical visibility gaps due to missing host-level EDR (Endpoint Detection & Response).
  * Behavioral analysis planning to protect local workstations against scripts and ransomware.
* **Governance, Risk & Compliance (GRC):**
  * Evaluating Third-Party Risk Management (TPRM) questionnaire failures and business impact.
  * Regulatory alignment with state privacy frameworks, FTC guidelines, and HIPAA/PHI safeguards.

---

## 📂 Repository Structure

```text
.
├── README.md                           # Repository overview and documentation hub
├── docs/
│   ├── 01-incident-response-summary.md  # Detailed IR timeline, root cause, and initial containment
│   └── 02-cybersecurity-risk-assessment.md # Comprehensive posture review and remediation roadmap
