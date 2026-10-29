# AI Governance and Risk Assessment
### A Simulated Case Study of Generative AI Risks in a SaaS Company

**Author:** Nancy | GRC and Cybersecurity | ISC2 Certified in Cybersecurity (CC)

> **Simulation notice:** This is a simulated assessment based on fictional organisational details and assumed control gaps. It is not an actual security audit and contains no verified findings.

**[Read the full report (PDF)](AI-Governance-Risk-Assessment.pdf)**

## Overview

Generative AI can boost productivity, but it also creates security, privacy, legal and operational risk. This project assesses those risks in a fictional US SaaS company of about 100 employees, where AI adoption has outpaced governance. It identifies 12 risks, maps them to the NIST AI RMF and NIST CSF 2.0, recommends controls, and sets out a 90-day roadmap to establish responsible AI use.

## At a Glance

| Item | Summary |
|---|---|
| Scenario | Fictional US SaaS company using generative AI in marketing, support, HR, development and operations |
| Risks assessed | 12 (11 High, 1 Moderate, 0 Critical) |
| Frameworks | NIST AI RMF 1.0, NIST CSF 2.0 |
| Deliverables | Risk register, treatment plans, acceptable-use policy requirements, governance structure, 90-day roadmap, residual risk summary |

## Top Risks

| ID | Risk | Score | Rating |
|---|---|---:|---|
| R-001 | Sensitive information exposure through AI tools | 16 | High |
| R-002 | Inaccurate or misleading AI-generated content | 16 | High |
| R-004 | Unauthorised or unapproved AI tool usage | 16 | High |
| R-006 | Exposure of customer information through AI integrations | 15 | High |
| R-007 | Insecure AI-generated code entering production | 15 | High |

The full register of 12 risks is in [`risk-register.csv`](risk-register.csv).

## Key Recommendations

1. Publish an AI acceptable-use policy and maintain an approved AI tools register.
2. Require documented human review of AI-generated external content, code and high-impact decisions.
3. Deliver AI security awareness training (target 95% completion by day 60).
4. Apply data protection safeguards, vendor assessments and least-privilege controls to AI tools and integrations.
5. Add AI scenarios to incident response and appoint an AI governance lead.

## Repository Contents

| Path | Description |
|---|---|
| [`report/AI-Governance-Risk-Assessment.pdf`](report/AI-Governance-Risk-Assessment.pdf) | Complete report |
| [`docs/methodology-and-scoring.md`](docs/methodology-and-scoring.md) | Scope, assumptions, methodology and scoring |
| [`docs/detailed-risk-treatment.md`](docs/detailed-risk-treatment.md) | Risk register and treatment plans for R-001 to R-012 |
| [`docs/acceptable-use-policy.md`](docs/acceptable-use-policy.md) | Policy requirements and governance structure |
| [`docs/90-day-roadmap.md`](docs/90-day-roadmap.md) | Roadmap and proposed KPIs |
| [`docs/residual-risk.md`](docs/residual-risk.md) | Illustrative residual risk for all risks |
| [`risk-register.csv`](risk-register.csv) | Machine-readable risk register |

## Skills Demonstrated

AI governance | Risk assessment and prioritisation | NIST AI RMF and CSF 2.0 alignment | Policy development | Third-party risk | Data protection and privacy awareness | Risk treatment and residual risk analysis | Incident response planning | Executive reporting

## Limitations

Simulated scenario with assumed control gaps; ratings and framework mappings are illustrative; not legal advice. See the full report for details.
