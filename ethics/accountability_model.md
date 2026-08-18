# Accountability Model

The Culture Key Accountability Model defines how responsibility,
authority, review, and escalation are assigned across an AI governance system.

Its purpose is to prevent responsibility gaps and ensure that every
governance-critical decision has an identifiable and legitimate owner.

Accountability is not the same as control.

A role may execute an action without having authority to define the rule
under which that action is permitted.

---

## Core Principles

The accountability model is based on the following principles:

- responsibility must be explicit
- authority must have defined scope
- execution and approval should be separated where risk requires it
- high-impact decisions must remain reviewable
- escalation must have a defined destination
- governance conflicts require a defined arbitration path
- no critical function should depend on a single point of authority failure
- accountability must remain traceable across both human and automated actors

---

## Governance Roles

Culture Key does not prescribe fixed organizational titles.

Implementations should assign governance functions according to system
scale, risk, and context.

### Operational Responsibility

Responsible for executing or coordinating an authorized action.

Examples may include:

- system operation
- monitoring
- risk detection
- execution of approved safeguards
- escalation initiation

Operational responsibility does not automatically grant governance authority.

### Decision Authority

Authorized to make defined governance decisions within an explicit mandate.

The scope of authority should specify:

- which decisions may be made
- under what conditions
- with what constraints
- when additional review is required
- when authority must be escalated

### Review Authority

Responsible for examining governance-critical decisions, changes,
or interventions.

Review should be sufficiently independent from the original decision
where the level of risk requires meaningful challenge.

### Stop / Intervention Authority

Authorized to suspend, restrict, block, or initiate rollback when
approved governance boundaries are exceeded.

Stop authority must be explicit and accessible quickly enough to prevent
avoidable harm or compounding risk.

### Arbitration Authority

Activated when ordinary decision or review paths cannot legitimately
resolve a governance conflict.

Arbitration may be required when:

- protected principles conflict
- authorized decision-makers disagree
- a high-impact decision is contested
- the scope or legitimacy of an authority is itself disputed

The authority whose mandate is under dispute should not be the sole
arbiter of that dispute.

---

## Responsibility Mapping

Each governance-critical function should identify, at minimum:

- **Responsible** — who performs or coordinates the action
- **Accountable** — who owns the outcome
- **Consulted** — whose relevant judgment is required
- **Informed** — who must receive the decision or outcome
- **Review Authority** — who can independently examine the decision
- **Escalation / Arbitration Path** — where unresolved conflict goes

RACI may be used as a starting structure, but governance-critical systems
should make review and escalation authority explicit rather than assuming
they are captured by ordinary accountability labels.

---

## Escalation and Arbitration

Escalation occurs when a decision exceeds the legitimate authority or
decision boundary of the current actor.

Arbitration occurs when escalation alone cannot resolve a governance conflict.

An escalation record should identify:

- the triggering issue
- the current decision owner
- the authority boundary that was reached
- the destination of escalation
- whether arbitration is required
- the final resolution authority

No escalation path should terminate at an undefined "human review."

---

## Drift Accountability

Accountability also applies to gradual governance drift.

When repeated exceptions, behavioral changes, altered escalation patterns,
or changes in practical authority indicate material deviation from the
approved governance baseline, the system should identify:

- who owns drift detection
- who determines materiality
- who may restrict operation during review
- who authorizes correction or rollback
- who validates return to normal operation

Drift must not become ownerless simply because no single failure event
triggered it.

---

## Decision Traceability

Governance-critical decisions should produce a trace appropriate to their
impact.

The trace should make it possible to determine:

- what happened
- who or what initiated the decision
- who had authority to act
- the basis and scope of that authority
- who reviewed the decision
- whether disagreement occurred
- whether escalation or arbitration was triggered
- what final decision was reached
- who remains accountable for the outcome

---

## Reference Implementations

Specific AI agents, orchestration components, teams, or organizational
roles may be mapped onto this accountability model.

Those mappings are implementation-specific and should not be treated as
universal governance requirements.

Culture Key reference architectures may demonstrate such mappings
separately from the general accountability model.

---

## Final Principle

Accountability must follow authority.

Where authority is distributed, accountability must remain traceable.

Where authority is contested, a legitimate review and arbitration path
must exist.
