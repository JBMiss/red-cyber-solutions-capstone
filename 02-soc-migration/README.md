# 02 — SOC Migration Decision: On-Prem to Cloud

**Course:** CYB/492 — Capstone Implementation
**Deliverable:** Decision Making Report
**Audience:** Executive management at Red Cyber Solutions

## The question

Red Cyber Solutions operates a 10-person on-premises Security Operations Center. The team is well-certified (CISSP, CEH, Security+) but is constrained by static infrastructure, rising capital costs, and limited access to modern tooling like AI-driven threat detection.

Leadership asked: **should we migrate the SOC to a cloud-based architecture, and if so, how?**

## What I produced

A decision-making report ([`Decision_Making_Report.docx`](./Decision_Making_Report.docx)) that covers the current state, the case for change, and an eight-phase migration plan.

### Current SOC assessment

- Structure, staffing, and tooling (firewalls, IDS, SIEM, EPP, manual threat intel feeds)
- Three core drawbacks: limited scalability, high operational costs, lagging threat detection capability

### Case for cloud migration

| Drawback | Cloud solution |
|---|---|
| Static infrastructure, global scalability is hard | Elastic capacity, rapid adjustment to new requirements |
| High CapEx + OpEx for in-house SOC | Shift fixed costs to variable costs via SOCaaS |
| Reliance on older tools, slow to adopt AI/ML | Access to AI-driven threat intelligence and real-time detection |

### Eight-phase migration plan

1. **Assessment & Planning** — objectives, gap analysis, risk assessment
2. **Cloud Service Provider Selection** — evaluate AWS, Azure, GCP against security features, SLAs, pricing
3. **Cloud SOC Architecture Design** — IAM, encryption, GDPR/HIPAA compliance considerations
4. **Migration Strategy** — prioritize sensitive data, compatibility checks
5. **Testing & Validation** — pilot deployments, vulnerability assessments, pen testing
6. **Training & Change Management** — tooling retraining, communication plan
7. **Deployment & Continuous Improvement** — phased rollout, feedback loops
8. **Compliance & Audit** — recurring audits and third-party assessments

## What this demonstrates

- **Structured decision-making** — presents the current state honestly before arguing for change
- **Cost-framing literacy** — distinguishes CapEx from OpEx and explains why the shift matters to executives
- **Awareness of migration risk** — the plan front-loads assessment and pilot testing rather than charging into cutover
- **Compliance as a first-class concern** — GDPR and HIPAA aren't an afterthought; they shape the architecture phase

## Key takeaway

The report argues for the cloud migration, but the real work is in Phase 1 (Assessment) and Phase 5 (Testing) — the phases where organizations most often cut corners and regret it later.
