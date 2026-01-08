# NOC Network Triage Runbook & Simulated Incidents

## Purpose
This repository demonstrates **operational readiness for a Network Operations Center (NOC) analyst role**.  
It focuses on **network triage, incident scoping, escalation judgment, and ticket-quality documentation**, rather than certification study or theoretical labs.

All incidents are simulated but modeled after **real-world Tier 1 / Tier 2 NOC workflows**.

---

## What This Project Demonstrates

- Structured **incident intake and severity classification**
- Accurate **scope and blast-radius determination**
- Layered **L1–L7 network triage**
- Evidence-driven troubleshooting (no guesswork)
- Clear **escalation decision-making**
- Professional, concise **NOC-grade documentation**
- Consistent process execution under simulated time pressure

---

## Repository Structure

- NOC_Triage_Documentation_Lab/
  - README.md
  - runbook/
    - 00-intake-and-severity.md
    - 01-scope-and-blast-radius.md
    - 02-layered-triage.md
    - 03-escalation-criteria.md
    - 04-documentation-standards.md
  - incidents/
    - incident-001-physical-link-down.md
    - incident-002-vlan-mismatch.md
    - incident-003-routing-blackhole.md
    - incident-004-high-latency.md
    - ...
  - templates/
    - incident-ticket-template.md
    - escalation-handoff-template.md
  - diagrams/
    - ...

---

## How to Review This Repository

If you are reviewing this as a recruiter, hiring manager, or interviewer:

1. **Start with the Runbook**
   
2. **Review Templates**
    - These are intended to mirror real world NOC ticketing and handoff standards
    - Designed for speed, clarity, and auditability

3. **Review Simulated Incidents**
    - Each incident follows the same structure
    - Look for:
      - Correct scoping
      - Structured triage order
      - Appropriate escalation decisions
      - Clean, timestamped documentation

---

## Incident Design Philosophy

- Incidents are **alert-driven**
- Each incident forces:
  - A scope decision
  - A triage stop-point
  - A resolve vs escalate judgment
- False positives are intentionally included

## Incident Categories

- Physical/link failures
- Layer 2 switching issues
- Layer 3 routing failures
- Latency and performance degradation
- Monitoring false alarms
