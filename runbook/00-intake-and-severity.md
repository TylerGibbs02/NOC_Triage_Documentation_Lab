# Incident Intake and Severity Classification

## Purpose
Establish a consistent intake process to prevent mis-prioritization and unnecessary troubleshooting.

No technical troubleshooting is performed until intake is complete.

---

## Incident Intake Header (Required)

Every incident must begin with the following information:

- Incident ID:
- Detection Time (UTC):
- Detection Source: (Monitoring / User / Automated)
- Alert Name or Report Summary:
- Initial Severity: (1 / 2 / 3 / 4) lower = more severe

---

## Detection Source Handling

### Monitoring Alert
- Validate the alert is current and not flapping
- Check for related or duplicate incidents
- Confirm monitoring system credibility

### User-Reported Issue
- Clarify scope (single user vs multiple)
- Identify affected service
- Confirm reproducibility

### Automated Ticket
- Check timestamp and correlation
- Identify triggering condition
- Confirm no existing parent incident

---

## Severity Definitions

| Severity | Description |
|--------|-------------|
| 1 | Multi-site outage, core service down, or critical business impact |
| 2 | Single-site outage or major service degradation |
| 3 | Single user or non-critical service impact |
| 4 | Informational, false positive, or no impact |

---

## Severity Adjustment Rules
Severity may be raised if:
- Scope increases
- Impact is greater than initially reported
- Issue persists beyond defined SLA

Severity should not be lowered without evidence.

---
