# Residual Risk Assessment

> **Simulation notice:** This is a simulated assessment based on fictional organisational details and assumed control gaps. It is not an actual security audit and contains no verified findings.

Part of the [AI Governance and Risk Assessment](../README.md) project. The complete report is available as a [PDF](../report/AI-Governance-Risk-Assessment.pdf).
Residual risk is the risk remaining after recommended controls are implemented and their effectiveness is assessed.


### Illustrative residual risk summary

| ID | Risk | Inherent | Rating | Residual | Rating | Basis for change |
|---|---|---|---|---|---|---|
| R-001 | Sensitive information exposure through AI tools | 4 x 4 = 16 | High | 2 x 4 = 8 | Moderate | Approved tools, training and safeguards reduce likelihood |
| R-002 | Inaccurate or misleading AI-generated content | 4 x 4 = 16 | High | 2 x 4 = 8 | Moderate | Mandatory review lowers likelihood; reputational impact remains |
| R-003 | Copyright and intellectual property infringement | 3 x 4 = 12 | High | 2 x 4 = 8 | Moderate | Guidelines and licence review reduce likelihood |
| R-004 | Unauthorised or unapproved AI tool usage | 4 x 4 = 16 | High | 2 x 4 = 8 | Moderate | Approval process and usage reviews reduce likelihood |
| R-005 | Overreliance on AI outputs without human verification | 3 x 4 = 12 | High | 2 x 3 = 6 | Moderate | Review requirements lower likelihood and limit impact |
| R-006 | Exposure of customer information through AI integrations | 3 x 5 = 15 | High | 2 x 5 = 10 | High | Likelihood falls, but severity keeps this risk High |
| R-007 | Insecure AI-generated code entering production | 3 x 5 = 15 | High | 2 x 4 = 8 | Moderate | SAST and review catch most flaws before production |
| R-008 | Third-party AI provider security and privacy weaknesses | 3 x 4 = 12 | High | 2 x 4 = 8 | Moderate | Due diligence and contract terms reduce likelihood |
| R-009 | Prompt injection and data leakage through AI integrations | 3 x 4 = 12 | High | 2 x 3 = 6 | Moderate | Least privilege and testing lower likelihood and blast radius |
| R-010 | Bias and discrimination in AI-assisted HR activities | 3 x 4 = 12 | High | 2 x 4 = 8 | Moderate | Human decision requirements reduce likelihood |
| R-011 | Regulatory and contractual non-compliance in AI use | 3 x 4 = 12 | High | 2 x 4 = 8 | Moderate | Requirements register and review reduce likelihood |
| R-012 | Absence of AI-specific incident response procedures | 3 x 3 = 9 | Moderate | 2 x 2 = 4 | Low | Playbooks and exercises improve readiness |


### Risk acceptance and ownership

| ID | Proposed risk owner | Proposed decision |
|---|---|---|
| R-006 | Privacy/Legal with Executive Leadership | Continue monitoring; consider additional controls such as stricter masking or in-house tooling |
| All others | Respective owner named in the detailed treatment plans | Accept residual risk at Moderate or Low, subject to annual review |

> Residual scores are hypothetical targets. They should be recorded as actual reassessments only after implementation evidence and control effectiveness testing are available.
