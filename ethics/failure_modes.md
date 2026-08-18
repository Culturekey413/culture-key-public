# Failure Modes

This document describes high-level governance failure modes that may arise
when an AI system, its authority structure, or its safety mechanisms no longer
operate as intended.

Failure modes are not the same as system states.

The Ethical State Machine represents behavioral state.
The Risk Model identifies structural risk.
System Safety defines intervention, recovery, and revalidation.

This document focuses on how governance itself can fail.

---

## 1. Detection Failure

A material condition exists but is not detected.

Examples include:

- harmful or anomalous behavior remains invisible
- drift is not identified
- interaction effects are missed
- monitoring coverage is incomplete
- detection logic becomes outdated

**Governance concern:** the system may remain in normal operation despite
conditions that should have triggered review or intervention.

---

## 2. Evaluation Failure

A condition is detected but its significance is assessed incorrectly.

Examples include:

- material risk is classified as non-material
- weak evidence is treated as conclusive
- high-impact uncertainty is dismissed
- context is ignored
- outdated criteria are applied

**Governance concern:** detection exists, but the resulting decision is not
supported by a legitimate assessment.

---

## 3. Authority Failure

An actor, agent, process, or human role acts outside its legitimate mandate.

Examples include:

- unauthorized restriction or intervention
- autonomous expansion of decision scope
- approval by an actor without the required mandate
- authority concentrated without meaningful review
- an authority validating its own contested scope

**Governance concern:** technically valid action may still be illegitimate.

---

## 4. Accountability Failure

Responsibility exists in theory but cannot be meaningfully attributed
or enforced.

Examples include:

- unclear ownership
- distributed responsibility without accountable outcome ownership
- missing review responsibility
- corrective actions without an accountable owner
- decisions that cannot be reconstructed

**Governance concern:** failure occurs without a clear path to responsibility,
correction, or learning.

---

## 5. Escalation Failure

A case reaches an authority boundary but cannot move effectively to the
appropriate decision-maker or governance mechanism.

Examples include:

- undefined escalation destination
- routing to the wrong authority
- delay incompatible with operational risk
- escalation loops
- unresolved handoffs
- escalation that terminates at generic "human review"

**Governance concern:** the system recognizes its limit but cannot reach
legitimate resolution.

---

## 6. Arbitration Failure

A serious governance conflict exists but cannot be resolved through a
legitimate arbitration process.

Examples include:

- no arbitration path exists
- conflicting principles remain unresolved
- the disputed authority is also the sole arbiter
- competing positions are not documented
- arbitration has no enforceable outcome

**Governance concern:** unresolved conflict may be hidden, deferred, or
resolved through power rather than governance.

---

## 7. Intervention Failure

The system identifies a condition requiring intervention but cannot
meaningfully restrict or stop relevant operation.

Examples include:

- intervention authority is unclear
- stop mechanisms are inaccessible
- intervention is too slow
- affected components cannot be isolated
- safeguards can be bypassed
- technical stop exists but operational use is impractical

**Governance concern:** detection and authority exist, but control cannot be
exercised effectively.

---

## 8. Recovery Failure

The system can be stopped but cannot be safely restored.

Examples include:

- no known acceptable baseline
- rollback restores an invalid or outdated state
- dependencies remain inconsistent
- recovery is incomplete
- revalidation is skipped
- operation resumes before governance integrity is restored

**Governance concern:** stopping failure does not guarantee safe recovery.

---

## 9. Drift Failure

Gradual deviation becomes normal practice without appropriate governance
response.

Examples include:

- repeated exceptions become routine
- authority expands informally
- safeguards weaken over time
- documented rules diverge from actual practice
- recurring anomalies are normalized

**Governance concern:** governance may fail without any single dramatic event.

---

## 10. Emergent Interaction Failure

Individually governed components interact in ways that produce ungoverned
system-level behavior.

Examples include:

- cascading actions
- feedback loops
- distributed authority expansion
- cross-agent coordination producing unintended effects
- combined impact exceeding individual mandates
- failures visible only at system level

**Governance concern:** component-level compliance does not guarantee
system-level governability.

---

## 11. Metric Failure

Governance metrics become misleading, incomplete, or incentive-distorting.

Examples include:

- outdated baselines
- metric drift
- false confidence from low incident counts
- gaming of governance indicators
- targets replacing judgment
- important risks remaining unmeasured

**Governance concern:** measurement may create the appearance of control
without reliable governance.

---

## 12. Version and Change-Control Failure

Material governance change occurs without appropriate review,
authorization, traceability, or revalidation.

Examples include:

- silent rule changes
- operational changes altering governance meaning
- outdated approval assumptions
- emergency changes becoming permanent
- rollback without governance review

**Governance concern:** the system may remain technically functional while
its governance baseline becomes uncertain.

---

## Compound Failure

Governance failures may combine.

A detection failure may produce drift.

Drift may create authority expansion.

Authority expansion may bypass escalation.

Weak traceability may then prevent accountability.

The absence of a single obvious failure point should not be mistaken for
the absence of systemic failure.

---

## Response Principle

Failure response should be proportionate to the type, materiality, speed,
and reversibility of the failure.

Depending on context, response may include:

- REVIEW
- restriction
- BLOCKED action
- ESCALATE
- intervention or stop
- rollback
- governance review
- arbitration
- revalidation

The response must follow the applicable authority structure.

Failure does not create unlimited emergency authority.

---

## Public Scope

This document describes governance failure modes at a high level.

Implementation-specific thresholds, detection logic, operational controls,
and enforcement mechanisms may remain private where disclosure would create
security or misuse risk.

---

## Final Principle

A governed system should be designed not only to reduce failure,
but to recognize when its own governance mechanisms are failing.

**Silent governance failure is itself a failure mode.**

---


