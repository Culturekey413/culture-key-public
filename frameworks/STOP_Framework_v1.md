# Culture Key — STOP Framework
## The Right to Stop

A specialized governance framework for evaluating intervention,
recovery, and conflict-resolution readiness before deployment,
major capability expansion, or increased real-world impact.

---

## The Problem

AI systems do not become unsafe only because they are powerful.

Structural risk emerges when:

- no legitimate authority can intervene
- intervention cannot happen fast enough
- responsibility is unclear
- system behavior cannot be meaningfully contained
- recovery cannot restore a legitimate operating condition
- serious governance conflict has no valid resolution path

The question before scale is therefore not only:

> **Can this system perform?**

but also:

> **Can we govern it when normal operation fails?**

---

## The Culture Key STOP Framework

STOP examines four pre-scale governance capabilities:

1. Authority
2. Veto Velocity
3. Rollback Integrity
4. Arbitration

Together, they test whether an organization can meaningfully intervene,
contain, recover, and resolve serious governance conflict before system
impact becomes difficult to control.

---

## 1. Authority — Who Can Say Stop?

A system without defined intervention authority creates responsibility gaps.

STOP asks:

- who or what may initiate intervention
- what conditions justify intervention
- what scope of action is authorized
- whether intervention authority is independent where required
- who reviews contested use of that authority
- whether the same actor improperly controls detection, intervention,
  approval, and review

Technical access does not automatically create governance authority.

Human presence does not automatically create legitimate authority.

Authority should be explicit, bounded, traceable, and appropriate to
the risk and impact involved.

**No single point of authority failure.**

---

## 2. Veto Velocity — Can Intervention Happen in Time?

Intervention that arrives after irreversible impact is not effective control.

STOP evaluates whether the speed of intervention is proportionate to:

- system speed
- propagation risk
- reversibility
- operational scale
- potential impact
- dependency chains
- interaction between agents or components

Possible controls may include:

- capability restriction
- execution pause
- component isolation
- access limitation
- bounded shutdown
- automated protective action within predefined authority

The objective is not universal instant shutdown.

The objective is intervention capability that is fast enough for the
risk being governed.

---

## 3. Rollback Integrity — Can the System Recover Safely?

Stopping unsafe operation is not the same as restoring safe operation.

STOP examines whether recovery mechanisms can establish:

- a known acceptable baseline
- the integrity of the restored configuration
- the scope of affected components
- downstream consequences of rollback
- authority to initiate recovery
- authority to validate restored operation
- whether revalidation is required before normal operation resumes

A previous version should not be assumed safe merely because it was
approved in the past.

Changes in environment, dependencies, capability, or governance conditions
may invalidate earlier assumptions.

**Rollback without revalidation may reproduce risk rather than resolve it.**

---

## 4. Arbitration — Who Decides When Legitimate Principles Conflict?

Governance conflict is not itself a system failure.

Failure occurs when serious conflict has no legitimate resolution path.

Arbitration may be required when:

- protected principles conflict
- legitimate authorities disagree
- a high-impact decision remains contested
- ordinary escalation cannot resolve the case
- the scope or legitimacy of authority is itself disputed

STOP asks whether the system has:

- a predefined escalation path
- a defined arbitration authority or process
- explicit conflict-resolution criteria
- separation from the authority whose decision is being contested where required
- traceable reasoning and final resolution

Principles should not be silently overridden.

Nor should a fixed hierarchy be assumed where legitimate contextual judgment
is required.

**Conflicting principles are not a flaw.  
Lack of legitimate arbitration is.**

---

## Pre-Scale Evaluation

Before high-impact deployment or major scale increase, organizations should
be able to answer:

### Authority
Who can intervene, under what mandate, and who reviews that authority?

### Velocity
Can intervention occur before material impact propagates beyond meaningful control?

### Recovery
Can operation be safely restored, and who validates that restoration?

### Arbitration
Can serious governance conflict reach a legitimate and accountable resolution?

If these questions cannot be answered clearly, the system may not yet have
sufficient governance capacity for its intended scale.

---

## Relationship to the Culture Key Core

STOP is a specialized pre-scale framework within Culture Key.

It draws on the Core Governance Architecture, including:

- authority boundaries
- accountability
- risk evaluation
- intervention and stop capability
- escalation
- arbitration
- rollback and recovery
- traceability
- revalidation

STOP does not replace these governance functions.

It tests whether selected parts of the core architecture are operationally
credible before system impact increases.

---

## Final Principle

The question is not whether every AI system can be stopped in the same way.

The question is whether its level of autonomy and impact remains within
the demonstrated capacity of its governance system to intervene, contain,
recover, and resolve serious conflict.

**A system should not be deployed at a level of impact beyond the
organization's demonstrated capacity to govern it.**

---

Status: Active  
Version: 1.1  
Layer: Pre-Scale Governance  
Scope: AI systems approaching deployment, major capability expansion,
or increased real-world impact
