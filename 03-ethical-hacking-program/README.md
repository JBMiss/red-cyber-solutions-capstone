# 03 — Ethical Hacking Program Proposal

**Course:** CYB/492 — Capstone Implementation
**Deliverable:** Investigation Report
**Audience:** Executive management + IT Security team at Red Cyber Solutions

## The question

With the SOC migration underway (see [02](../02-soc-migration)), the next question was whether Red Cyber Solutions should formalize an internal ethical hacking capability — and if so, what that program should look like, what it would cost, and who needs to be involved.

## What I produced

A full investigation report ([`Investigation_Report.docx`](./Investigation_Report.docx)) proposing a 20-week ethical hacking program. This is the most comprehensive deliverable in the capstone — it covers business objectives, stakeholders, tooling, resourcing, cost, and effort estimation.

### Business objectives

**Objective 1 — Enhance cybersecurity posture**
- Target: 50% reduction in security incidents within 12 months
- Means: regular penetration exercises feeding into policy updates and a prioritized vulnerability remediation framework
- Regulatory alignment: PCI DSS, HIPAA, GDPR

**Objective 2 — Build customer trust and protect reputation**
- Target: 15% improvement in customer retention
- Means: demonstrating proactive security posture as market differentiator

### Stakeholders and their roles

| Stakeholder | Responsibility | Impact |
|---|---|---|
| IT Security Team | Implementation leaders, vulnerability analysis, policy updates | Workload increase, training needs |
| Executive Management | Strategic oversight, budget approval, risk management | Budget decisions, cultural influence |

### Recommended tooling

- **Nmap** — network discovery and security auditing; NSE scripting for advanced detection
- **Metasploit Framework** — extensive exploit library, integration with Nmap for targeted testing
- **Burp Suite Professional** — web application security testing ($449/user/year)

### Resource estimate

**Personnel (20 weeks: Oct 2024 – Feb 2025)**
- 2 certified ethical hackers (consultants)
- 5 IT Security Team members
- 1 project manager

**Technical resources**
- Nmap + Metasploit: open source
- Burp Suite Pro: $898 (2 users)
- Testing servers: $6,000
- Secure storage: $1,500

**Training**
- Workshops: $4,000
- CEH certification (3 team members): $8,685

### Cost breakdown

| Line Item | Cost |
|---|---|
| Consultant personnel (560 hrs × $200) | $112,000 |
| IT team overtime (500 hrs × $60) | $30,000 |
| Training (workshops + CEH) | $12,685 |
| Tools (Burp Suite Pro) | $898 |
| Hardware (servers + storage) | $7,500 |
| Travel | $3,000 |
| Contingency (10%) | $16,608 |
| **Total** | **$182,691** |

### Timeline (20 weeks)

| Phase | Duration | Dates |
|---|---|---|
| Planning | 2 weeks | Oct 1 – Oct 14 |
| Tool Setup & Training | 1 week | Oct 15 – Oct 22 |
| Testing Phase | 4 weeks | Oct 23 – Nov 16 |
| Analysis & Reporting | 2 weeks | Nov 17 – Nov 30 |
| Remediation Implementation | 8 weeks | Dec 1 – Jan 31 |
| Follow-up Testing | 2 weeks | Feb 1 – Feb 14 |

## What this demonstrates

- **Full-stack program design** — not just "we should do pen tests" but what it costs, who does the work, how long it takes, and how success is measured
- **Realistic budgeting** — includes a 10% contingency line (most student budgets don't), real licensing costs, and a distinction between consultant rates and internal overtime
- **Proper sequencing** — notice that remediation (8 weeks) is the longest phase. Finding vulnerabilities is the easy part; fixing them well is the actual work.
- **Measurable objectives** — the 50% incident reduction and 15% retention improvement are stakes leadership can evaluate the program against

## Key takeaway

A pen test program that doesn't budget for remediation time is just an expensive way to generate a list of findings that nobody fixes. This proposal puts remediation at 40% of the program timeline — a much more honest ratio than most "ethical hacking" proposals.
