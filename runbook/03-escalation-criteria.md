# Escalation Criteria and Decision Rules

## Purpose
Define when troubleshooting should stop and escalation should occur.

---

## Immediate Escalation Triggers

Escalate immediately if any of the following are true:
- Core or WAN physical link down
- Routing protocol instability
- Multi-site impact
- Security indicators present
- Issue occurs outside approved change window

---

## Time-Boxed Escalation

| Severity | Max Tier 1 Investigation Time |
|--------|-------------------------------|
| P1 | 15 minutes |
| P2 | 30 minutes |
| P3 | 60 minutes |

If root cause is not identified within the time limit, escalate.

---

## Do Not Escalate If

- Issue is confirmed false positive
- Known maintenance is in progress
- Single endpoint misconfiguration is identified

---

## Escalation Targets

- Network Engineering (L2/L3 issues)
- Systems/Application Teams (L4–L7 issues)
- ISP or Carrier (provider-related failures)

---

## Escalation Requirement
All escalations must include documented evidence and completed handoff template.
