# 01 — Risk Analysis: DDoS & Ransomware

**Course:** CYB/490 — Capstone Design
**Deliverable:** Risk Analysis Report
**Audience:** Security leadership at Red Cyber Solutions

## The question

Two attack categories dominate the current threat landscape for service-oriented businesses: distributed denial-of-service (DDoS) and ransomware. Leadership asked for a written analysis covering:

1. How should we respond to each attack type?
2. What ethical considerations shape those responses (especially ransom payment decisions)?
3. What should our risk assessment framework look like?
4. Where do firewalls, IDS, and IPS fit into our layered defense?

## What I produced

A concise risk analysis report ([`Risk_Analysis_Report.docx`](./Risk_Analysis_Report.docx)) covering:

- **Incident response strategies** for DDoS (volumetric vs. protocol attacks, traffic rerouting, ISP coordination) and ransomware (isolation, forensic tracing, backup restoration)
- **Ethical analysis** of ransom payment — weighing immediate operational recovery against the risk of funding criminal or sanctioned entities
- **Five-component risk assessment framework** — asset identification, threat evaluation, vulnerability assessment, impact analysis, risk mitigation
- **Layered defense architecture** — firewall placement and segmentation, IDS/IPS complementary roles, multi-factor authentication, regular audits

## What this demonstrates

- **Industry-aware analysis** — report cites 2024 data including Cloudflare's observation that network-layer DDoS attacks rose 85% in 2023
- **Ethical reasoning in security decisions** — recognizes that technically valid choices (paying a ransom to recover fast) can carry broader consequences
- **Layered security mental model** — treats firewalls, IDS, and IPS as complementary controls with distinct roles, not interchangeable tools

## Key takeaway

The report's core argument: technical controls alone don't reduce risk — they need to be paired with explicit decision frameworks for when an incident occurs. An organization that hasn't pre-decided its ransom-payment position is going to make that decision under duress, badly.
