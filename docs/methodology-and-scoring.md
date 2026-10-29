# Methodology, Scope and Scoring

> **Simulation notice:** This is a simulated assessment based on fictional organisational details and assumed control gaps. It is not an actual security audit and contains no verified findings.

Part of the [AI Governance and Risk Assessment](../README.md) project. The complete report is available as a [PDF](../report/AI-Governance-Risk-Assessment.pdf).

## Organisation Background and Scope

The fictional organisation is a US-based SaaS company employing approximately 100 people. It provides cloud-based software products to business customers and has introduced generative AI tools to improve employee productivity.


### Business functions using AI

| Department | AI use cases |
|---|---|
| Marketing | Social media posts, email campaigns, blogs and advertising copy |
| Customer Support | Drafting customer responses and summarising support tickets |
| Human Resources | Drafting job descriptions and supporting recruitment activities |
| Software Development | Code generation, debugging and documentation |
| Operations | Internal documentation, research and meeting summaries |


### Objective

To identify and evaluate the risks associated with the company's use of generative AI and recommend governance measures to reduce those risks.


### Scope

In scope: employee use of generative AI tools; handling of confidential and personal information; accuracy and reliability of AI-generated outputs; intellectual property and copyright considerations; AI tool approval and oversight; human accountability and employee awareness; fairness considerations in HR use cases; AI-specific incident handling.

Out of scope: penetration testing, source code security testing, vendor audits and a formal legal compliance review.


## Assessment Methodology

The assessment follows a risk-based approach informed by the NIST AI Risk Management Framework.

1. Identify AI use cases across business functions.
2. Identify potential risks associated with each use case.
3. Evaluate likelihood and business impact.
4. Map risks and controls to NIST AI RMF and CSF 2.0.
5. Recommend controls and risk treatment measures.
6. Establish an implementation roadmap and monitoring approach.


### Risk scoring

Each risk is scored on a five-point likelihood scale and a five-point impact scale. Risk score = Likelihood x Impact.

| Score | Rating |
|---|---|
| 1-4 | Low |
| 5-9 | Moderate |
| 10-16 | High |
| 17-25 | Critical |

| Score | Likelihood | Impact |
|---|---|---|
| 1 | Rare | Insignificant |
| 2 | Unlikely | Minor |
| 3 | Possible | Moderate |
| 4 | Likely | Major |
| 5 | Almost certain | Severe |

> These thresholds are illustrative criteria developed for this case study, not a prescribed NIST scoring system.


### Why no risk is rated Critical

A Critical rating (17-25) requires, for example, a likelihood of at least 4 combined with an impact of 5, or a likelihood of 5 with an impact of at least 4. In this scenario, no single event is both almost certain and severe. The highest-impact risks (R-006 and R-007) are rated as possible rather than likely because the scenario assumes some baseline engineering practices, such as peer review, are already in place. The clustering of High ratings reflects the real picture: many significant risks that need treatment, none yet at crisis level. Different assumptions would change the ratings.


### Framework mapping approach

Each risk is mapped to the most relevant functions of the NIST AI RMF (Govern, Map, Measure, Manage) and categories of NIST CSF 2.0 (for example GV.PO for Policy, ID.AM for Asset Management, PR.DS for Data Security). The mappings are illustrative and show alignment of thinking; they are not a formal compliance mapping.


## Assumptions and Existing Control Environment

The following conditions are assumed for the fictional organisation. They set the baseline and are not verified findings.

| Control area | Scenario assumption |
|---|---|
| AI governance policy | No formal AI acceptable-use policy |
| Approved AI tools | No documented register of approved AI tools |
| Data protection | No confirmed technical safeguards preventing sensitive data from being entered into public AI tools |
| Employee awareness | No confirmed organisation-wide AI security training |
| Human oversight | No documented review requirements for AI-generated external content |
| Vendor oversight | No documented AI-specific third-party risk assessment process |
| Accountability | No clearly documented AI governance ownership structure |
| Software development | General peer code review exists, but there is no AI-specific guidance |
| HR processes | No documented review of AI-assisted recruitment for fairness |
| Incident response | A general incident response process exists but does not cover AI-specific incidents |
