# Decision Trace Template

This template provides a structured record for governance-relevant decisions,
state transitions, interventions, escalations, and arbitration.

Its purpose is to make the decision path reconstructable without assuming
that detection, evaluation, decision authority, and execution belong to
the same actor.

---

## 1. Case Information

**Case / Decision ID:**  
[Unique reference]

**Date / Time:**  
[Timestamp]

**Scenario:**  
[Short description]

**Governance / Risk Type:**  
[e.g. manipulation, autonomy, bias, authority conflict, drift, safety]

**Impact Level:**  
[Low / Medium / High / Critical — according to the applicable implementation]

---

## 2. Trigger

**Triggering Condition:**  
[What initiated the governance process?]

**Detected By:**  
[Actor, agent, monitoring mechanism, or process]

**Evidence / Signal:**  
[Relevant evidence, pattern, threshold, or observation]

**Baseline / Constraint Referenced:**  
[Approved rule, boundary, policy, governance baseline, or protected constraint]

---

## 3. Evaluation

**Evaluated By:**  
[Actor or authority authorized to assess this class of condition]

**Evaluation Authority / Mandate:**  
[Why this actor or authority is authorized to evaluate it]

**Assessment:**  
[Material / Non-material / Uncertain / Other]

**Reasoning:**  
[Concise rationale]

---

## 4. State and Action

**Previous State:**  
[SAFE / REVIEW / BLOCKED / ESCALATE]

**Resulting State:**  
[SAFE / REVIEW / BLOCKED / ESCALATE]

**Transition Authorized By:**  
[Authorized actor, mechanism, or governance role]

**Transition Authority Basis:**  
[Mandate, policy, role, or approved governance rule]

**Action Taken:**  
[Continue / Restrict / Pause / Block / Rollback / Other]

**Action Authorized By:**  
[Actor or authority with mandate for that intervention]

**Action Authority Basis:**  
[Scope or rule authorizing the action]

---

## 5. Accountability

**Responsible:**  
[Who performed or coordinated the action]

**Accountable:**  
[Who owns the outcome]

**Review Authority:**  
[Who may independently review the decision]

**Consulted / Informed:**  
[Relevant roles where applicable]

---

## 6. Escalation

**Escalation Required:**  
[Yes / No]

If yes:

**Reason for Escalation:**  
[Authority boundary, ambiguity, impact, conflict, drift, other]

**Escalated By:**  
[Actor or process]

**Escalation Destination:**  
[Defined governance authority]

**Destination Mandate:**  
[Why this authority is legitimate for this class of decision]

---

## 7. Arbitration

**Arbitration Triggered:**  
[Yes / No]

If yes:

**Conflict:**  
[Principles, authorities, interpretations, or decisions in conflict]

**Competing Positions:**  
[Concise record of the relevant positions]

**Arbitration Authority:**  
[Authorized governance body or role]

**Authority Basis:**  
[Mandate for resolving this class of conflict]

**Dissent / Minority View:**  
[Record where applicable]

**Resolution:**  
[Final reasoned decision]

---

## 8. Drift

**Drift Involved:**  
[Yes / No]

If yes:

**Drift Type:**  
[Behavioral / Governance / Authority / Exception / Other]

**Baseline Deviation:**  
[What changed relative to the approved baseline]

**Pattern / Duration:**  
[Relevant repeated behavior or time pattern]

**Corrective Action:**  
[Restriction / Correction / Rollback / Governance Review / Other]

**Revalidation Required:**  
[Yes / No]

**Revalidated By:**  
[Authorized actor or mechanism]

---

## 9. Review and Contestability

**Decision Reviewable:**  
[Yes / No]

**Review / Appeal Path:**  
[Defined process or authority]

**Review Deadline or Condition:**  
[If applicable]

**Independent Review Required:**  
[Yes / No]

---

## 10. Final Outcome

**Final Decision / Outcome:**  
[Summary]

**Final Decision Authority:**  
[Who authorized the outcome]

**Rationale:**  
[Why the outcome was selected]

**Follow-up Required:**  
[Yes / No + actions]

**Return to Normal Operation:**  
[If applicable, who authorized and on what basis]

---

## Traceability Principle

A governance record should make it possible to reconstruct:

**what was detected → who evaluated it → who had authority to decide →
what action was authorized → who remained accountable → whether the decision
was challenged → how the case was resolved.**

A decision is not fully traceable if its outcome is recorded but its
authority path is not.
