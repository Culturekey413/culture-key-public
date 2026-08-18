# Ethical State Machine — Rules (Public)

The Ethical State Machine defines the high-level behavioral states used to
respond to risk, uncertainty, and governance-relevant conditions.

Its purpose is to keep system behavior predictable, bounded, auditable,
and connected to defined governance authority.

The State Machine represents and applies authorized system-state transitions.

It does not independently resolve governance conflicts that exceed its
authorized decision boundaries.

---

## Purpose

The Ethical State Machine is designed to:

- reduce ambiguity in edge cases
- enforce approved safety and governance boundaries
- support proportional intervention
- identify when additional review is required
- detect when the system has reached its authorized decision boundary
- provide traceable state transitions

---

## Public States

### SAFE

Normal operation within approved governance boundaries.

**Condition:**

- No material risk or governance concern detected.
- System behavior remains within authorized operating boundaries.

**System behavior:**

- Operation proceeds normally.
- Standard monitoring remains active.

---

### REVIEW

Additional scrutiny is required.

**Condition:**

- Risk signals are present but not conclusive.
- Intent or context is unclear.
- A possible governance deviation requires examination.
- Drift signals indicate potential movement away from the approved baseline.

**System behavior:**

- Additional review is triggered.
- Proportionate safeguards may be applied.
- Relevant context or evidence may be gathered.
- Operation may continue, be restricted, or be temporarily paused according
  to the level of risk.

---

### BLOCKED

An action is prohibited under existing governance or safety constraints.

**Condition:**

- A protected constraint would be violated.
- A prohibited action has been identified with sufficient confidence.
- Continued execution would exceed an approved system boundary.

**System behavior:**

- The relevant action is prevented.
- A safe alternative may be offered where appropriate.
- The event is recorded.
- Further review is not automatic unless reconsideration is justified.

---

### ESCALATE

The current actor or process has reached the limit of its legitimate
decision authority.

**Condition:**

- A decision exceeds the current authority boundary.
- High-impact ambiguity cannot be resolved through ordinary review.
- A novel case is not adequately covered by existing rules.
- A protected-principle conflict requires governance judgment.
- The legitimacy or scope of an authority is contested.
- Drift affects governance-critical boundaries or decision integrity.

**System behavior:**

- Autonomous resolution stops at the relevant decision boundary.
- The case is routed to a defined governance authority.
- The escalation destination and reason are recorded.
- Temporary safeguards or restrictions may remain active while resolution
  is pending.

"Escalate" must not mean escalation to an undefined human.

The receiving role or governance body must have an explicit mandate to act.

---


## Transition Logic — High Level

State transitions are triggered by changes in risk, evidence, governance
conditions, or authority boundaries.

## Transition Authority

A valid state transition requires:

1. a defined trigger condition,
2. an actor or mechanism authorized to evaluate that condition, and
3. an actor or mechanism authorized to initiate or approve the resulting transition.

Detection, evaluation, and transition authority are distinct functions
and should not be assumed to belong to the same actor.

Transition authority should be defined in advance according to the type,
risk, and impact of the decision.

Typical transitions include:

### SAFE → REVIEW

Triggered when an authorized monitoring or decision mechanism determines that:

- material risk signals have emerged
- context has become sufficiently uncertain to require additional scrutiny
- potential drift has been detected
- system behavior is approaching an approved governance boundary

The mechanism authorized to initiate REVIEW, and the conditions under which
it may do so, should be defined in advance.

### REVIEW → SAFE

Triggered when:

- the concern has been assessed by the actor or review authority authorized
  for that class of decision
- available evidence supports return to normal operation within the
  approved governance baseline
- any detected deviation has been assessed as non-material or has been
  corrected and, where required, revalidated

The authority required to return a system from REVIEW to SAFE should be
defined in advance and proportionate to the risk and impact of the case.

### REVIEW → BLOCKED

Triggered when the actor or authority authorized for that class of decision
determines that sufficient evidence establishes that the proposed action
violates an approved constraint or boundary.

The authority to impose BLOCKED status must be defined in advance and
proportionate to the impact of the restriction.

### REVIEW → ESCALATE

Triggered when the current actor or review mechanism determines that:

- the case exceeds its authorized decision scope
- significant ambiguity cannot be resolved within that scope
- governance authority or protected principles are in conflict
- the required decision belongs to a higher or different governance authority

The escalation destination must be defined by the applicable governance
structure and must not be selected ad hoc by the escalating actor.

### BLOCKED → REVIEW

May occur when an authorized review path is activated because:

- relevant new information becomes available
- the application of the rule is legitimately contested
- reconsideration is requested through an approved process

The actor that imposed the block should not automatically control the
review of its own decision where meaningful independent review is required.

A BLOCKED state does not automatically create a right to override the
underlying governance constraint.

### BLOCKED → ESCALATE

May occur when an authorized review process determines that the dispute
cannot be legitimately resolved within the existing review scope because it concerns:

- the interpretation of a governance-critical rule
- the legitimate scope of the blocking authority
- a high-impact contested decision
- conflict between protected principles

The case must be routed through the predefined escalation path to an
authority with the mandate to address that class of dispute.



## Arbitration Path

Arbitration is not a behavioral state of the Ethical State Machine.

It is a governance resolution process that may be activated after escalation
when ordinary review cannot legitimately resolve the conflict.

Arbitration may be required when:

- protected principles conflict
- authorized decision-makers disagree
- a high-impact decision remains contested
- the legitimacy or scope of an authority is itself disputed

The arbitration process is governed by the Human Governance Layer and
Accountability Model.

The State Machine records that arbitration was triggered but does not
self-resolve the conflict.

---

## Drift

Drift is treated as a governance signal, not as a separate system state.

Drift may be indicated by:

- repeated behavioral deviations
- changing decision patterns
- increasing exception frequency
- unusual escalation patterns
- practical expansion of authority beyond its approved scope
- recurring attempts to operate around existing governance constraints

Depending on materiality, drift may trigger:

- REVIEW
- temporary restriction
- BLOCKED action
- ESCALATE
- governance-rule review
- correction or rollback

Return to normal operation should require appropriate revalidation when
material governance drift has occurred.

---

## Traceability

Governance-relevant transitions should produce an audit record appropriate
to their impact.

The record should make it possible to determine:

- the previous and resulting state
- what triggered the transition
- which actor or mechanism detected the triggering condition
- which actor or authority evaluated its materiality
- which actor or authority initiated or approved the transition
- the basis and scope of that transition authority
- whether an authority boundary was reached
- whether escalation occurred
- the destination of escalation
- whether arbitration was triggered
- the final resolution where applicable

---

## Design Principle

The Ethical State Machine governs behavioral response.

The Human Governance Layer governs authority.

The Accountability Model governs responsibility and review.

Arbitration governs serious unresolved governance conflict.

These functions interact, but they should not be collapsed into a single
decision mechanism.
