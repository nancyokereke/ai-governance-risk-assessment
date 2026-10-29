# Risk Register and Detailed Risk Treatment

> **Simulation notice:** This is a simulated assessment based on fictional organisational details and assumed control gaps. It is not an actual security audit and contains no verified findings.

Part of the [AI Governance and Risk Assessment](../README.md) project. The complete report is available as a [PDF](../report/AI-Governance-Risk-Assessment.pdf).

## AI Risk Register

| ID | Risk | Departments | L | I | Score | Rating | NIST AI RMF | NIST CSF 2.0 |
|---|---|---|---|---|---|---|---|---|
| R-001 | Sensitive information exposure through AI tools | All | 4 | 4 | 16 | High | Govern, Map | PR.DS, PR.AT, GV.PO |
| R-002 | Inaccurate or misleading AI-generated content | Marketing, Support | 4 | 4 | 16 | High | Measure, Manage | GV.PO, GV.RR |
| R-003 | Copyright and intellectual property infringement | Marketing, Development | 3 | 4 | 12 | High | Govern, Map | GV.OC, GV.PO |
| R-004 | Unauthorised or unapproved AI tool usage | All | 4 | 4 | 16 | High | Govern, Map | ID.AM, GV.PO |
| R-005 | Overreliance on AI outputs without human verification | All | 3 | 4 | 12 | High | Govern, Manage | GV.RR, PR.AT |
| R-006 | Exposure of customer information through AI integrations | Support, Operations | 3 | 5 | 15 | High | Map, Manage | PR.DS, GV.SC |
| R-007 | Insecure AI-generated code entering production | Development | 3 | 5 | 15 | High | Measure, Manage | PR.PS, ID.RA |
| R-008 | Third-party AI provider security and privacy weaknesses | All | 3 | 4 | 12 | High | Govern, Map | GV.SC, ID.RA |
| R-009 | Prompt injection and data leakage through AI integrations | Support, Operations, Development | 3 | 4 | 12 | High | Map, Measure | PR.PS, DE.CM, ID.RA |
| R-010 | Bias and discrimination in AI-assisted HR activities | HR | 3 | 4 | 12 | High | Map, Measure, Manage | GV.OC, ID.RA |
| R-011 | Regulatory and contractual non-compliance in AI use | All | 3 | 4 | 12 | High | Govern | GV.OC, GV.PO |
| R-012 | Absence of AI-specific incident response procedures | All | 3 | 3 | 9 | Moderate | Manage | RS.MA, RS.CO, DE.AE |

> L = Likelihood, I = Impact. R-009 to R-012 were added after a gap review of the initial eight risks.


### Risk descriptions

- **R-001: Sensitive information exposure through AI tools.** Employees may enter confidential company information, customer data or unreleased product information into unapproved AI tools, causing unauthorised disclosure, privacy violations or loss of competitive advantage.
- **R-002: Inaccurate or misleading AI-generated content.** AI tools may generate false statistics, inaccurate product claims or misleading information. If published without verification, this could cause reputational damage, customer complaints or legal exposure.
- **R-003: Copyright and intellectual property infringement.** AI-generated text, images or code may raise copyright, licensing or ownership concerns.
- **R-004: Unauthorised or unapproved AI tool usage.** Employees may adopt AI tools without IT or Security approval, creating visibility gaps over how company information is processed and stored.
- **R-005: Overreliance on AI outputs without human verification.** Employees may rely on AI recommendations, summaries or decisions without sufficient review, leading to poor decisions or inappropriate actions.
- **R-006: Exposure of customer information through AI integrations.** Support staff may submit identifiable customer information, support conversations or account details to AI tools without safeguards.
- **R-007: Insecure AI-generated code entering production.** Developers may introduce AI-generated code containing vulnerabilities, insecure dependencies or unsafe practices into production systems.
- **R-008: Third-party AI provider security and privacy weaknesses.** The organisation may rely on AI providers without assessing their security practices, data handling, access controls or incident response.
- **R-009: Prompt injection and data leakage through AI integrations.** AI tools connected to internal systems, documents or email may be manipulated by malicious content (indirect prompt injection) into exposing data or taking unintended actions.
- **R-010: Bias and discrimination in AI-assisted HR activities.** AI-assisted job descriptions, screening or candidate summaries may reflect or amplify bias, creating discrimination, fairness and reputational concerns.
- **R-011: Regulatory and contractual non-compliance in AI use.** AI use may conflict with privacy obligations, customer contracts, sector requirements or emerging AI-related laws (for example state-level rules on AI in hiring, or EU requirements if European customers are served).
- **R-012: Absence of AI-specific incident response procedures.** The organisation may be unable to recognise, escalate and contain AI-related incidents such as data pasted into a public tool, harmful outputs or a compromised AI integration.


## Detailed Risk Assessment and Treatment

All risks use the treatment strategy Mitigate. Target dates are counted from programme start.


### R-001: Sensitive information exposure through AI tools

**Risk statement:** Employees in any department may enter confidential company information or customer data into unapproved AI tools, resulting in unauthorised disclosure, privacy violations or loss of competitive advantage.

**Potential causes:** No acceptable-use policy; no approved tools list; insufficient data-handling guidance; no confirmed technical safeguards against sensitive data entering public AI tools.

**Potential business impact:** Exposure of confidential information; unauthorised disclosure of personal information; contractual or regulatory consequences; reduced customer trust.

**Inherent rating:** Likelihood 4, Impact 4, Score 16, High

| Recommended action | Owner | Target |
|---|---|---|
| Develop an AI acceptable-use policy | IT/Security | 30 days |
| Establish a register of approved AI tools | IT/Security | 30 days |
| Train employees on safe AI usage | HR and IT/Security | 60 days |
| Evaluate data loss prevention and access restrictions | IT/Security | 60 days |

**Success measure:** Register established; policy published; training completed; technical safeguards evaluated and implemented where necessary.


### R-002: Inaccurate or misleading AI-generated content

**Risk statement:** Marketing and support employees may publish or send inaccurate AI-generated statistics, product claims or other misleading content without verification.

**Potential causes:** No review requirement for external content; time pressure; trust in fluent but unverified outputs; no approved claims reference.

**Potential business impact:** Reputational damage; customer complaints; false-advertising or contractual exposure.

**Inherent rating:** Likelihood 4, Impact 4, Score 16, High

| Recommended action | Owner | Target |
|---|---|---|
| Introduce mandatory human review before external publication | Marketing | 30 days |
| Require verification of statistics and product claims | Marketing | 30 days |
| Establish an approved product claims and messaging reference | Marketing | 60 days |
| Document content approval responsibilities | Marketing | 60 days |

**Success measure:** All externally published AI-assisted content undergoes documented human review, with factual claims traceable to reliable sources.


### R-003: Copyright and intellectual property infringement

**Risk statement:** Employees may use AI-generated text, images or code without considering copyright, licensing or ownership implications.

**Potential causes:** No IP guidance for AI content; unclear licensing terms of AI tools; no review of AI-generated code for licence conflicts.

**Potential business impact:** IP disputes; takedown demands; uncertainty over ownership of company assets; contractual exposure to customers.

**Inherent rating:** Likelihood 3, Impact 4, Score 12, High

| Recommended action | Owner | Target |
|---|---|---|
| Publish guidelines on AI-generated content and IP | Legal | 45 days |
| Require review of externally published AI-generated material | Marketing | 30 days |
| Review licensing and output-ownership terms of approved AI tools | Legal, IT/Security | 60 days |
| Include IP considerations in employee training | HR, Legal | 60 days |

**Success measure:** IP guidelines published; approved tools have documented licensing review; training covers IP.


### R-004: Unauthorised or unapproved AI tool usage

**Risk statement:** Employees may independently adopt AI applications without approval, creating security and data governance blind spots.

**Potential causes:** No approval process; easy access to free AI tools and browser extensions; no monitoring of AI tool usage.

**Potential business impact:** Unknown data flows; inability to assess provider security; inconsistent controls; difficulty responding to incidents.

**Inherent rating:** Likelihood 4, Impact 4, Score 16, High

| Recommended action | Owner | Target |
|---|---|---|
| Create an AI tool request and approval process | IT/Security | 30 days |
| Maintain an approved AI tools register | IT/Security | 30 days |
| Assess tools before adoption | IT/Security | 45 days |
| Periodically review usage (for example network or browser logs) to find unapproved tools | IT/Security | 90 days |

**Success measure:** All in-use AI tools are either approved and registered or retired; a repeatable approval process exists.


### R-005: Overreliance on AI outputs without human verification

**Risk statement:** Employees may make business decisions or take operational actions based on AI outputs without sufficient human verification.

**Potential causes:** No defined review requirements; limited understanding of AI limitations; productivity pressure.

**Potential business impact:** Inaccurate decisions; inappropriate customer or employee actions; unclear accountability.

**Inherent rating:** Likelihood 3, Impact 4, Score 12, High

| Recommended action | Owner | Target |
|---|---|---|
| Define tasks that require mandatory human review | Department Heads | 30 days |
| Assign accountability for decisions involving AI recommendations | Department Heads | 45 days |
| Train employees on AI limitations | HR, IT/Security | 60 days |
| Prohibit fully automated high-impact decisions without governance approval | Executive Leadership | 30 days |

**Success measure:** Review requirements documented per department; no high-impact automated decisions without recorded approval.


### R-006: Exposure of customer information through AI integrations

**Risk statement:** Customer support employees may submit personal or confidential customer information to AI tools without authorisation or safeguards.

**Potential causes:** Support tickets contain identifiable data; AI summarisation is convenient; no masking tools; unclear provider retention practices.

**Potential business impact:** Privacy breach; contractual breach with business customers; regulatory consequences; loss of customers. Impact is rated 5 because a SaaS company's customers entrust it with their own data.

**Inherent rating:** Likelihood 3, Impact 5, Score 15, High

| Recommended action | Owner | Target |
|---|---|---|
| Define approved methods for AI use in customer support | Customer Support, IT/Security | 30 days |
| Prohibit unnecessary submission of identifiable customer data | Privacy/Legal | 30 days |
| Evaluate data masking and anonymisation controls | IT/Security | 60 days |
| Review AI provider data handling and retention terms | Privacy/Legal | 60 days |

**Success measure:** Support workflows use approved tools only; identifiable data is masked or excluded; provider retention terms reviewed.


### R-007: Insecure AI-generated code entering production

**Risk statement:** Developers may use AI-generated code containing vulnerabilities or insecure practices, introducing weaknesses into production applications.

**Potential causes:** AI suggestions accepted without scrutiny; outdated or vulnerable dependencies suggested; no AI-specific secure coding guidance. The scenario assumes general peer review exists, so likelihood is rated possible.

**Potential business impact:** Exploitable vulnerabilities; customer data compromise; remediation cost; reputational harm. Impact is rated 5 because production flaws in SaaS products can affect all customers.

**Inherent rating:** Likelihood 3, Impact 5, Score 15, High

| Recommended action | Owner | Target |
|---|---|---|
| Require code review before merging AI-generated code | Engineering | 30 days |
| Run static application security testing in the pipeline | Application Security | 60 days |
| Add dependency and vulnerability checks | Engineering | 60 days |
| Train developers on secure AI-assisted coding | Application Security | 60 days |

**Success measure:** All AI-assisted code passes review and automated scanning before merge; training completed by developers.


### R-008: Third-party AI provider security and privacy weaknesses

**Risk statement:** The organisation may expose data or systems to security and privacy risks by adopting AI providers without sufficient due diligence.

**Potential causes:** No AI-specific vendor assessment; unclear data retention or model-training practices; weak contractual protections.

**Potential business impact:** Provider breach affecting company data; hidden use of company data for model training; contractual gaps.

**Inherent rating:** Likelihood 3, Impact 4, Score 12, High

| Recommended action | Owner | Target |
|---|---|---|
| Conduct security assessments of AI providers | IT/Security | 60 days |
| Review provider privacy, retention and training-data practices | Privacy/Legal | 60 days |
| Evaluate access controls, encryption and incident response arrangements | IT/Security | 60 days |
| Include security and data protection requirements in vendor agreements | Procurement, Legal | 90 days |

**Success measure:** Priority AI vendors have documented assessments; contracts include data protection terms.


### R-009: Prompt injection and data leakage through AI integrations

**Risk statement:** AI tools connected to internal systems, documents, tickets or email may process malicious content that manipulates them into revealing data or taking unintended actions.

**Potential causes:** AI assistants granted broad access; untrusted content (customer messages, web pages, documents) processed as instructions; no testing of AI integrations.

**Potential business impact:** Unauthorised data disclosure; unintended actions in connected systems; difficulty detecting misuse.

**Inherent rating:** Likelihood 3, Impact 4, Score 12, High

| Recommended action | Owner | Target |
|---|---|---|
| Apply least-privilege access to AI integrations | IT/Security | 60 days |
| Require security review before connecting AI tools to internal systems | IT/Security | 45 days |
| Test priority integrations for prompt injection scenarios | Application Security | 90 days |
| Log and monitor AI integration activity | IT/Security | 90 days |

**Success measure:** AI integrations are inventoried, scoped to least privilege and reviewed before connection.


### R-010: Bias and discrimination in AI-assisted HR activities

**Risk statement:** AI-assisted job descriptions, candidate screening or summaries may reflect or amplify bias, creating fairness, legal and reputational concerns.

**Potential causes:** No review of AI-assisted recruitment; opaque model behaviour; lack of documented human decision points.

**Potential business impact:** Discrimination complaints; legal exposure; loss of candidate trust; reputational damage.

**Inherent rating:** Likelihood 3, Impact 4, Score 12, High

| Recommended action | Owner | Target |
|---|---|---|
| Require human decision-making for all hiring outcomes | HR | 30 days |
| Review AI-assisted job descriptions for biased language | HR | 45 days |
| Document permitted and prohibited AI uses in recruitment | HR, Legal | 45 days |
| Assess applicable hiring and AI-related laws | Legal | 60 days |

**Success measure:** No AI tool makes or ranks hiring decisions without documented human review; permitted uses documented.


### R-011: Regulatory and contractual non-compliance in AI use

**Risk statement:** AI use may conflict with privacy obligations, customer contracts, sector requirements or emerging AI-related laws.

**Potential causes:** No mapping of legal and contractual obligations to AI use; rapidly changing regulation; no designated owner for AI compliance.

**Potential business impact:** Regulatory scrutiny; contractual breach; customer audit findings; fines or lost deals.

**Inherent rating:** Likelihood 3, Impact 4, Score 12, High

| Recommended action | Owner | Target |
|---|---|---|
| Review customer contracts and privacy commitments for AI-related obligations | Legal | 60 days |
| Maintain a register of applicable AI and privacy requirements | Legal, Privacy | 90 days |
| Assign an AI governance lead responsible for regulatory monitoring | Executive Leadership | 30 days |
| Review AI use cases against identified requirements | Privacy/Legal | 90 days |

**Success measure:** Applicable requirements documented; each AI use case reviewed against them.


### R-012: Absence of AI-specific incident response procedures

**Risk statement:** The organisation may be unable to recognise, escalate and contain AI-related incidents.

**Potential causes:** Existing incident response does not mention AI; no reporting route for AI misuse; no playbooks.

**Potential business impact:** Delayed containment; unreported data exposure; inconsistent response.

**Inherent rating:** Likelihood 3, Impact 3, Score 9, Moderate

| Recommended action | Owner | Target |
|---|---|---|
| Add AI incident scenarios to the incident response plan | IT/Security | 60 days |
| Create a simple reporting channel for suspected AI misuse | IT/Security | 30 days |
| Run a tabletop exercise on an AI data exposure scenario | IT/Security | 90 days |

**Success measure:** AI incident scenarios documented; tabletop exercise completed and lessons recorded.
