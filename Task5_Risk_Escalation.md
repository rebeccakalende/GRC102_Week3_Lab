Add Task 5 Cyber-Risk Escalation and Segregation of Duties

# Task 5: Cyber-Risk Escalation and Segregation of Duties

## Organisation: TechGlobal

## 5.1 Major Cyber-Risk Escalation Workflow

TechGlobal requires a consistent cyber-risk escalation process to ensure that security issues are identified, assessed, escalated, managed and formally closed. The process should ensure that operational teams can resolve routine issues while significant risks receive executive or Board-level attention.

### Escalation Workflow

```text
Operational Detection or Risk Identification
                  |
                  v
Initial Assessment and Validation
                  |
                  v
Risk Classification and Impact Assessment
                  |
                  v
Assign Escalation Level
                  |
        +---------+---------+
        |         |         |
        v         v         v
    Level 1   Level 2   Level 3
 Operational Executive Board/Material
        |         |         |
        +---------+---------+
                  |
                  v
Containment and Risk Treatment
                  |
                  v
Governance and Executive Review
                  |
                  v
Decision, Action Assignment and Tracking
                  |
                  v
Monitoring, Verification and Closure
```

### Workflow Description

#### Step 1: Detection or Identification

A cyber-risk issue may be identified through:

- Security monitoring and alerts.
- Vulnerability assessments.
- Incident reports.
- Internal audits.
- Employee reports.
- Third-party assessments.
- Business continuity or operational reviews.

The identified issue must be logged and assigned an owner.

#### Step 2: Initial Assessment

The IT or security team conducts an initial assessment to determine:

- Systems and services affected.
- Potential confidentiality, integrity and availability impact.
- Possible business disruption.
- Data or regulatory exposure.
- Existing controls.
- Immediate containment requirements.

#### Step 3: Risk Classification

The issue is classified according to its severity, business impact, likelihood, regulatory implications and alignment with the organisation's risk appetite.

The assessment determines whether the issue can be managed operationally or must be escalated.

#### Step 4: Escalation

The issue is assigned an escalation level using the approved threshold table. The relevant management, executive or Board authority is informed based on the level of risk.

#### Step 5: Containment and Risk Treatment

The responsible teams implement appropriate actions, which may include:

- Containment.
- Patching or remediation.
- Access restriction.
- System recovery.
- Additional monitoring.
- Risk transfer.
- Formal risk acceptance.

#### Step 6: Governance Review and Decision

Significant risks are reviewed by the CISO, Security Governance Committee, CEO or Board, depending on the escalation level. The authorised decision-maker approves the risk treatment, accepts the risk, requests additional controls or directs further escalation.

#### Step 7: Monitoring and Closure

The assigned owner tracks the agreed actions. Closure requires evidence that:

- The required actions have been completed.
- The remaining risk has been assessed.
- Relevant stakeholders have been informed.
- The authorised reviewer has approved closure.
- The decision and supporting evidence have been recorded.

---

## 5.2 Escalation Threshold Table

TechGlobal should use three primary escalation levels.

| Escalation Level | Trigger Criteria | Escalation Authority | Required Response |
|---|---|---|---|
| Level 1: Operational | Low-impact issue, limited systems affected, no significant business disruption and manageable within approved procedures | IT/Security Team and relevant operational manager | Resolve, document actions and report through routine governance channels |
| Level 2: Executive | Significant service disruption, repeated control failure, high-risk vulnerability, cross-department impact or risk requiring additional resources | CISO, Security Governance Committee and CEO | Coordinate response, allocate resources, review treatment and escalate further if required |
| Level 3: Board/Material Risk | Major business disruption, significant data exposure, regulatory implications, substantial financial impact or risk exceeding organisational risk appetite | Executive Security Council, CEO and Board | Make strategic decisions, approve risk treatment, oversee recovery and review material risk exposure |

### Escalation Principles

1. Escalation should be based on risk impact rather than technical severity alone.
2. The CISO should escalate issues when risk exceeds approved operational authority.
3. The CRO/Risk function should provide independent risk challenge.
4. Legal and Compliance should be consulted where regulatory or contractual obligations may apply.
5. Risk acceptance must be approved by an authorised risk owner.
6. Escalation decisions and actions must be documented in a central decision register.

---

## 5.3 Segregation-of-Duties and Accountability Weakness Register

TechGlobal's IT-centric model may create conflicts when one individual or department controls multiple stages of a security or risk decision. The following weaknesses and controls are proposed.

| No. | Potential Weakness | Risk Created | Recommended Governance or Control Measure |
|---|---|---|---|
| 1 | One IT employee requests, approves and implements privileged access | Unauthorised or inappropriate access may be granted without independent review | Separate access request, approval and implementation. Require periodic privileged-access reviews |
| 2 | The CISO recommends and independently approves major risk acceptance | Risk decisions may lack independent challenge | Require CRO/Risk review and approval by an authorised business risk owner |
| 3 | The same person requests and approves high-risk system changes | Unauthorised or poorly assessed changes may be introduced | Require independent change approval, documented testing and post-implementation review |
| 4 | IT controls security budgets without independent financial review | Security expenditure may lack appropriate oversight or prioritisation | Require Finance review and approval through the approved budget authority |
| 5 | IT investigates and closes significant incidents without independent oversight | Incidents may be closed prematurely or evidence may be incomplete | Require CISO, Security Governance Committee or independent review for significant incidents |
| 6 | Business units bypass security controls to meet operational deadlines | Unmanaged exceptions may increase organisational risk | Use documented exceptions with risk assessment, authorised approval, expiry dates and periodic review |

### Control Implementation Principles

The controls should reduce conflicts without creating unnecessary bureaucracy. TechGlobal should apply additional approval and review requirements according to risk level.

- Low-risk operational activities may follow standard procedures.
- High-risk activities should require independent review.
- Material decisions should require documented executive or Board oversight.
- Temporary exceptions should have an owner, expiry date and review requirement.
- Access and change approvals should use existing workflow or ticketing systems where possible.

---

## 5.4 Decision Recording and Assurance Note

TechGlobal should maintain a central Security Decision Register for significant cybersecurity, risk and governance decisions. The register provides evidence of who made a decision, the authority used, the information considered and the actions required.

### Required Decision Register Fields

Each significant decision should include:

1. Decision ID.
2. Date raised and date decided.
3. Description of the issue or decision.
4. Risk and business impact.
5. Options considered.
6. Recommended action.
7. Decision-maker.
8. Consulted stakeholders.
9. Authority or approval level.
10. Agreed actions and deadlines.
11. Assigned action owners.
12. Supporting evidence.
13. Current status.
14. Review date.
15. Closure date and approval.

### Decision Tracking Process

1. The issue or decision is entered into the central register.
2. A responsible owner is assigned.
3. The relevant authority reviews the risk and recommendation.
4. The decision and supporting rationale are recorded.
5. Actions are assigned with deadlines.
6. Progress is reviewed through the appropriate governance committee.
7. Outstanding or overdue actions are escalated.
8. Closure is approved after evidence has been verified.

### Assurance Responsibilities

The CISO should maintain oversight of cybersecurity decisions and ensure that significant issues are reported through the appropriate governance channels.

The Security Governance Committee should review:

- Open and overdue risk actions.
- Major incidents.
- Risk acceptance decisions.
- Policy exceptions.
- Control failures.
- High-risk vulnerabilities.
- Decisions requiring executive attention.

The CRO/Risk function should provide independent challenge and confirm that risks are assessed consistently with the organisation's risk management approach.

Internal Audit or another independent assurance function may periodically review the decision register to verify that:

- Decisions were approved by authorised individuals.
- Segregation-of-duties controls were followed.
- Actions were completed.
- Evidence was retained.
- Risk acceptance was properly documented.
- Decisions were reviewed and closed appropriately.

### Illustrative Decision Register

| Decision ID | Decision | Decision Owner | Required Action | Status |
|---|---|---|---|---|
| SEC-001 | Remediate a high-risk vulnerability | CISO/IT | Patch affected systems and provide evidence | Open |
| SEC-002 | Approve a temporary security exception | Authorised Risk Owner | Apply compensating controls and review expiry date | Under Review |
| SEC-003 | Escalate a material cyber-risk issue | CEO/Executive Security Council | Review business impact and determine further action | Open |

The entries above are illustrative examples and should be replaced or updated with actual organisational decisions where available.

---

## 5.5 Expected Outcomes

The proposed cyber-risk escalation and segregation-of-duties framework is expected to:

- Improve the consistency of cyber-risk escalation.
- Clarify operational, executive and Board decision-making authority.
- Reduce conflicts of interest within the IT-centric model.
- Strengthen independent risk oversight.
- Improve accountability for risk treatment and closure.
- Provide an auditable record of significant security decisions.
- Support informed executive and Board-level risk management.
- Reduce the likelihood of undocumented risk acceptance or delayed escalation.
