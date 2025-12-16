# EDR / XDR Coverage and Gaps

A practical overview of Endpoint Detection and Response (EDR) and Extended Detection and Response (XDR) capabilities, focusing on detection scope, limitations, signal quality, and governance considerations in enterprise environments.

---

## Overview

EDR and XDR platforms are often treated as comprehensive detection solutions. In practice, they provide **strong but incomplete visibility**, and their effectiveness depends heavily on deployment scope, telemetry quality, tuning, and organizational processes.

This repository explores what EDR/XDR can and cannot realistically detect, how gaps emerge, and how security teams and leadership should interpret detection outcomes. The goal is to bridge technical detection concepts with risk awareness and governance decision-making.

---

## Key Questions This Project Addresses

- What types of activity are EDR and XDR good at detecting?
- Where do blind spots commonly exist?
- How does alert volume differ from meaningful signal?
- How should organizations reason about “coverage” claims?
- What governance and risk assumptions are often made incorrectly?

---

## Repository Contents

1. **[README.md](README.md)** — Project overview and objectives  
2. **[detection_scope.md](detection_scope.md)** — What EDR/XDR typically monitors and detects  
3. **[coverage_gaps.md](coverage_gaps.md)** — Common detection blind spots and limitations  
4. **[alert_fatigue_and_signal_quality.md](alert_fatigue_and_signal_quality.md)** — Alert volume, false positives, and signal quality  
5. **[governance_considerations.md](governance_considerations.md)** — Risk interpretation, reporting, and leadership implications  

---

## Conceptual Scope

This project focuses on **conceptual and architectural understanding**, not vendor-specific implementation. It does not include:
- Product comparisons
- Configuration guides
- Detection rules or scripts

Instead, it emphasizes:
- Detection logic
- Coverage assumptions
- Operational realities
- Risk and governance implications

---

## Relationship to Risk and GRC

Detection technologies are only one input into organizational risk posture. Gaps in telemetry, unmanaged assets, encrypted traffic, and non-endpoint activity can all create **false confidence** if not explicitly acknowledged.

This repository complements governance-focused work by helping decision-makers understand:
- What monitoring data actually represents
- Where monitoring does *not* exist
- Why absence of alerts does not equal abse

