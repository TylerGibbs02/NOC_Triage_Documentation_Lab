# Layered Network Triage Methodology

## Purpose
Provide a consistent, repeatable troubleshooting sequence that prevents layer skipping and reduces time to escalation.

---

## General Rules

- Troubleshoot layers in order
- Do not assume higher-layer issues until lower layers are validated
- Stop and escalate when escalation criteria are met

---

## Layer 1: Physical

### What This Layer Covers
- Cabling
- Interface state
- Link stability

### Checks
- Interface up/down state
- Error counters
- Link flaps

### Interpretation
- If down or unstable: escalate immediately
- If clean: proceed to Layer 2

---

## Layer 2: Switching

### What This Layer Covers
- VLAN membership
- MAC address learning
- ARP resolution

### Checks
- VLAN assignment
- MAC table presence
- ARP completeness

### Interpretation
- Missing MAC or ARP issues indicate local switching problems
- Clean results allow progression to Layer 3

---

## Layer 3: Routing

### What This Layer Covers
- IP reachability
- Routing decisions
- Path availability

### Checks
- Ping tests
- Traceroute behavior
- Route table entries

### Interpretation
- Failure at first hop indicates local issue
- Mid-path failure suggests upstream or provider issue

---

## Layers 4–7: Services

### What This Layer Covers
- Ports
- DNS
- Application response

### Checks
- Port availability
- Name resolution
- Service responsiveness

### Interpretation
- If L1–L3 are clean, suspect service or application ownership

---

## Mandatory Rule
Do not advance layers until the current layer is validated or escalated.
