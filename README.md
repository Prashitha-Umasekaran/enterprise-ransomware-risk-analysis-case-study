# Enterprise Ransomware Incident Response & Risk Analytics Case Study

## Project Overview

This project presents a simulated enterprise ransomware incident involving **NovaMart Global**, a hypothetical retail and e-commerce organisation operating across North America, Europe and Asia-Pacific.

The case study examines how a phishing-based attack can develop into an enterprise-wide cybersecurity and business risk event. It connects simulated SOC investigation concepts with incident response, enterprise risk assessment, business impact analysis and cybersecurity governance.

**Disclaimer:** This is a hypothetical case study created for educational, analytical and portfolio development purposes. NovaMart Global, its infrastructure, the attack scenario and operational details are fictional. This project does not represent a real security breach or a live SOC investigation.

## Project Snapshot

| Area | Summary |
|---|---|
| Case organisation | NovaMart Global (fictional retail and e-commerce organisation) |
| Scenario date | 14 March 2026 |
| Incident type | Simulated ransomware incident beginning with a phishing email |
| Analysis focus | Threat progression, incident response, enterprise risk and business continuity |
| Frameworks | MITRE ATT&CK and Cyber Kill Chain |
| Intended audience | SOC, IT, cybersecurity risk, business continuity and management stakeholders |
| Evidence status | Hypothetical scenario and conceptual analysis; no live telemetry or production deployment |

This project is best understood as a **scenario-based cybersecurity risk and incident-response case study**, rather than a hands-on SOC deployment or a forensic investigation of a real breach.

## Simulated Attack Progression

The scenario describes a hypothetical sequence:

1. Phishing email provides the initial access point.
2. Suspicious PowerShell execution is considered during the investigation.
3. Credential compromise and privilege escalation are examined.
4. Lateral movement and suspicious outbound communication are considered.
5. Ransomware-related file encryption creates potential business disruption.

The sequence is an analytical scenario, not a claim that these events were observed in real systems.

## Project Objectives

- Examine a simulated ransomware attack scenario and its progression.
- Understand SIEM-based threat detection and security monitoring concepts.
- Analyse incident classification, escalation and CSIRT response workflows.
- Identify cybersecurity vulnerabilities and enterprise risk exposure.
- Evaluate potential operational, financial, reputational and compliance impacts.
- Recommend security controls and business continuity improvements.

## Case Study Scenario

The simulated incident takes place on **14 March 2026**. An employee in the Finance department opens a malicious email attachment, providing the hypothetical attacker with an initial access point.

The scenario develops through suspicious PowerShell execution, credential compromise, privilege escalation, lateral movement, suspicious outbound communication and ransomware-related file encryption.

The incident is classified as a **Priority 1 – Critical Security Incident** because of its potential impact on customer-facing services, financial operations, internal infrastructure and business continuity.

## Key Areas of Analysis

### 1. SIEM-Based Threat Detection
Discusses how SIEM platforms such as Splunk Enterprise, Wazuh and FortiSIEM could support monitoring and investigation in the hypothetical scenario. The project does not claim that these platforms were deployed or used to collect live telemetry. Detection concepts include:
- Suspicious PowerShell execution
- Repeated authentication failures
- Privilege escalation attempts
- Suspicious outbound connections
- High-volume file modification
- Lateral movement indicators

### 2. Incident Response and CSIRT Workflow
Examines the simulated response lifecycle:
- Alert validation and triage
- Incident classification and escalation
- Containment of compromised systems
- Eradication and recovery
- Stakeholder communication
- Business continuity support

### 3. Enterprise Risk Assessment
Evaluates potential exposure across:
- Operational risk
- Financial risk
- Reputational risk
- Compliance risk
- Data security risk
- Business continuity risk

The report uses qualitative likelihood and business-impact categories to prioritise risks.

### 4. Cyber Kill Chain and MITRE ATT&CK
Relates the hypothetical attack progression to Cyber Kill Chain stages and selected MITRE ATT&CK technique references. These mappings are analytical associations for the scenario, not verified detections:
- Phishing – T1566
- PowerShell – T1059.001
- Credential Dumping – T1003
- Exploitation for Privilege Escalation – T1068
- Remote Services – T1021
- Application Layer Protocol – T1071
- Data Encrypted for Impact – T1486

### 5. Risk Mitigation and Cybersecurity Governance
Recommends improvements in:
- Security monitoring and SIEM correlation
- Endpoint Detection and Response (EDR)
- Multi-Factor Authentication (MFA)
- Privileged Access Management (PAM)
- Network segmentation
- Employee security awareness
- Backup isolation and recovery testing
- Business continuity and executive-level cyber risk reporting

## Tools and Concepts

- Splunk Enterprise – SIEM monitoring concepts
- Wazuh – Security monitoring concepts
- FortiSIEM – Security event monitoring concepts
- MITRE ATT&CK Framework
- Cyber Kill Chain
- Cybersecurity Risk Assessment
- Business Impact Analysis
- Incident Response and CSIRT
- Enterprise Risk Management

*The tools and frameworks are discussed as part of the simulated scenario; this repository does not claim a live deployment or independently verified security telemetry.*

## Business Relevance

The case study demonstrates how a technical cybersecurity incident can create wider business risks, including service disruption, recovery costs, customer confidence concerns, compliance exposure and business continuity challenges.

It highlights the importance of connecting SOC operations with enterprise risk management, executive decision-making and organisational resilience.

## Skills Demonstrated

- Structuring a cybersecurity incident scenario and its attack progression.
- Relating attacker behaviours to recognised cybersecurity frameworks.
- Identifying potential operational, financial, reputational and compliance impacts.
- Organising qualitative enterprise risk assessment and prioritisation.
- Developing incident response, resilience and mitigation recommendations.
- Translating technical cyber-risk concepts into business-facing language.

## Project Outcome

The report brings together scenario-based threat analysis, incident response concepts, qualitative risk assessment and business-focused mitigation recommendations. It demonstrates how cybersecurity events can be assessed in terms of organisational impact and communicated to business stakeholders.

## Scope and Evidence Limitations

- NovaMart Global and the incident are fictional and created for educational purposes.
- The scenario does not represent a real breach, live SOC investigation or verified incident timeline.
- References to Splunk Enterprise, Wazuh and FortiSIEM describe relevant SIEM concepts; they do not establish a live deployment or hands-on use within this case study.
- No live security logs, forensic artefacts, validated alert counts or measured financial losses are claimed.
- Attack-technique mappings and risk impacts are scenario-based analytical assessments and should be interpreted accordingly.

## Repository Contents

- `report/` – Detailed enterprise ransomware incident response and risk analytics case study.
- `README.md` – Project overview, scope, tools and key analysis areas.
