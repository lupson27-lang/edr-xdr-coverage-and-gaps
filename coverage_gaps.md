# Coverage Gaps: Where EDR and XDR Do Not See

This document outlines common visibility and detection gaps associated with EDR and XDR platforms. Understanding these gaps is essential for realistic risk assessment, informed governance decisions, and accurate communication with leadership and auditors.

Coverage gaps do not imply failure; they reflect the boundaries of technical controls and the need for complementary security measures.

---

## 1. Unmanaged and Unmonitored Assets

EDR and XDR platforms depend on agents, integrations, and telemetry sources. Assets that are not properly onboarded introduce blind spots, including:

- Unmanaged endpoints
- Bring-your-own-device (BYOD) systems
- Contractor and third-party devices
- Legacy systems that cannot support agents

These assets may operate within trusted network boundaries while remaining invisible to detection tooling.

---

## 2. Non-Endpoint Activity

EDR visibility is endpoint-centric by design. Activities that occur outside endpoints are often partially or entirely unmonitored, such as:

- Network-based lateral movement without endpoint execution
- Credential abuse via remote services
- Malicious activity within network appliances
- Cloud-native service abuse without endpoint interaction

XDR may correlate some of this activity, but only when appropriate telemetry sources are integrated and retained.

---

## 3. Encrypted Traffic and Limited Inspection

Modern environments rely heavily on encrypted communications. As a result:

- Malicious activity may be hidden within encrypted sessions
- Network metadata alone may lack sufficient context
- Decryption may be limited due to privacy, performance, or regulatory constraints

Detection effectiveness depends on complementary controls and contextual correlation.

---

## 4. Living-off-the-Land Techniques

Adversaries increasingly use legitimate tools and processes to avoid detection, including:

- Native system utilities
- Administrative tools
- Scripting engines
- Legitimate cloud services

These techniques reduce behavioral anomalies and generate low-signal activity that may evade detection or blend with normal operations.

---

## 5. Operational and Configuration Gaps

Coverage gaps may also arise from operational realities, such as:

- Disabled or misconfigured agents
- Outdated detection rules
- Log ingestion failures
- Inconsistent policy enforcement across environments

Without continuous validation, assumed coverage may not reflect actual monitoring effectiveness.

---

## 6. OT, IoT, and Specialized Environments

Many environments fall outside traditional EDR/XDR scope, including:

- Operational Technology (OT) systems
- Industrial control systems (ICS)
- Medical devices
- Embedded and proprietary platforms

These systems often require alternative monitoring approaches and should be explicitly excluded from EDR/XDR coverage statements.

---

## 7. Governance Implications

From a governance perspective, coverage gaps should be:

- Documented and reviewed
- Mapped to risk acceptance decisions
- Communicated transparently to leadership
- Considered during audits and assessments

Explicit acknowledgment of gaps enables informed decision-making and prevents overstatement of security posture.

---
