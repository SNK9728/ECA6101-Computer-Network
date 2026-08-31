# ECA6101-Computer-Network
# 🔍 Digital Forensic Investigation Report

## Simulated Cyber Incident Analysis

**Incident Type:** Unauthorized Access and Suspected Data Exfiltration  
**Severity:** High  
**Affected System:** FIN-SRV-01  
**Operating System:** Windows Server  

---

## 1. Problem Definition

A simulated cyber incident was investigated to identify the attack source, attack method, affected systems, evidence of compromise, and possible impact.

### Objectives

- Detect and analyze the cyber incident.
- Collect and preserve digital evidence.
- Reconstruct the sequence of the attack.
- Identify Indicators of Compromise (IoCs).
- Evaluate the impact of the incident.
- Provide recommendations to prevent similar attacks.

---

## 2. Incident Scenario

On **30 August 2026 at 10:15 AM**, the organization's Security Operations Centre detected unusual login activity on a Windows server.

Multiple failed login attempts were followed by a successful login from an external IP address. Sensitive files were accessed shortly after the login, and network logs showed suspicious outbound data transfer.

### Incident Classification

| Category | Details |
|---|---|
| Incident Type | Unauthorized Access |
| Attack Method | Brute-Force / Credential Attack |
| Affected System | FIN-SRV-01 |
| Operating System | Windows Server |
| Severity | High |
| Potential Impact | Data Theft |

---

## 3. Forensic Investigation Methodology

The investigation followed standard digital forensic procedures:

```text
Identification
      ↓
Preservation
      ↓
Collection
      ↓
Examination
      ↓
Analysis
      ↓
Reporting
