# Culture Key — Framework Map

## Purpose

Culture Key is a human-governance framework for systems whose capability,
autonomy, complexity, or real-world impact may increase over time.

Its purpose is not to prescribe a specific AI architecture.

It provides a governance structure for determining:

- who holds legitimate authority
- how risk is identified and evaluated
- how decisions change system state
- when intervention is justified
- how systems can be stopped, contained, recovered, and revalidated
- how legitimate conflicts are resolved
- how decisions and authority remain traceable, reviewable, and contestable

The framework is designed to remain applicable across different models,
agents, orchestration patterns, and technical implementations.

---

## 1. Foundational Principles

The foundational principles define what the governance architecture is
intended to preserve.

### Human Agency

Increasing system capability should not remove meaningful human capacity
to understand, question, choose, contest, intervene, or correct.

### Human Governance First

Human presence alone does not constitute governance.

Governance requires legitimate authority, defined mandates, accountability,
review, and meaningful intervention capacity.

### Consent and Boundaries

Consent should be meaningful, scoped, revocable where applicable, and
distinguished from other legitimate bases of authority.

Interaction boundaries should protect human autonomy without converting
governance into identity-based judgment or profiling.

### Governability Under Increasing Capability

A system should not operate at a level of autonomy or impact beyond the
demonstrated capacity of its governance structure to supervise, intervene,
recover, and resolve serious conflict.

---

## 2. Core Governance Architecture

The core architecture consists of distinct but interacting governance
functions.

These functions should not be collapsed into a single decision-maker,
model, agent, or oversight mechanism.

### Authority

Defines who or what may:

- make governance-relevant decisions
- authorize actions
- intervene
- stop or restrict operation
- review decisions
- validate recovery
- resolve contested authority

Technical capability does not automatically create legitimate authority.

### Accountability

Defines responsibility across the governance process.

Execution, permission, review, intervention, and accountability are
distinct functions and may belong to different actors.

Accountability should remain attributable even when decisions involve
multiple technical or human components.

### Risk

Identifies conditions requiring governance attention.

Risk may include:

- safety and operational failure
- manipulation or loss of human agency
- authority misuse
- opacity
- accountability failure
- governance drift
- emergent interaction risk
- failure of escalation, intervention, or recovery

Risk detection does not itself determine the governance response.

### State and Decision Logic

Governance-relevant conditions may move the system between operational
states such as:

`SAFE ↔ REVIEW ↔ BLOCKED`

with escalation available when ordinary governance cannot resolve the case.

State transitions should be evidence-sensitive, reviewable, and capable of
moving in more than one direction when conditions materially change.

A restriction should not become permanent merely because it once became
necessary.

Nor should a previous approval remain valid when its underlying assumptions
no longer hold.

### Intervention and Recovery

Governance must remain capable of meaningful intervention when continued
operation may create or compound material risk.

Intervention may include restriction, pause, isolation, containment,
rollback, or stop.

Stopping and recovery are separate governance problems.

Recovery should establish a legitimate operating condition and may require
revalidation before normal operation resumes.

### Arbitration

Legitimate principles, authorities, or governance requirements may conflict.

Conflict itself is not necessarily governance failure.

Governance failure occurs when consequential conflict has no legitimate,
defined, and accountable resolution path.

Arbitration provides that path when ordinary escalation is insufficient.

### Traceability and Review

Governance-relevant decisions should leave sufficient evidence to reconstruct:

- what triggered the decision
- what evidence was considered
- how risk was evaluated
- which authority was exercised
- what state transition occurred
- what action followed
- whether escalation or arbitration occurred
- how the outcome was reviewed or revalidated

Traceability exists to support understanding, accountability, correction,
and institutional learning.

It is not a mechanism for assigning blame by default.

---

## 3. Governance Cycle

Culture Key is not a linear decision pipeline.

Governance functions interact through feedback and review.

A simplified cycle is:

```text
               AUTHORITY
                   │
                   ▼
RISK ───────► DECISION / STATE
 ▲                 │
 │                 ▼
 │           INTERVENTION
 │                 │
 │                 ▼
 │              RECOVERY
 │                 │
 └───── REVIEW ◄───┘
           │
           ▼
      REVALIDATION
```

Accountability and traceability apply across the entire cycle.

Arbitration becomes available when legitimate conflict cannot be resolved
through the ordinary governance path.

New evidence, changed context, system drift, recovery outcomes, or review
may return the system to an earlier governance function.

The objective is therefore not to produce irreversible governance decisions.

It is to preserve the capacity for legitimate, evidence-sensitive correction.

---


## 4. Cross-Cutting Governance Mechanisms

Some mechanisms support multiple parts of the core architecture rather than
forming independent governance authorities.

### Input / Output Contracts

Define operational boundaries between the governed system and its external
environment.

They help constrain interaction without treating users or other actors as
fixed risk identities.

### Consent Protocol

Operationalizes the foundational principle of consent.

It defines how consent is requested, scoped, recorded, withdrawn, renewed,
and distinguished from other legitimate authority.

### Metrics

Provide governance signals.

Metrics may support detection, review, and evaluation, but do not constitute
proof, authority, or judgment by themselves.

Metrics must themselves remain open to review for drift, gaming, distortion,
or loss of contextual validity.

### Failure Modes

Describe how governance itself may fail.

These include failures of detection, evaluation, authority, accountability,
escalation, arbitration, intervention, recovery, change control, and other
interacting governance functions.

### Security and Governance Integrity

Security protects both technical integrity and the integrity of governance.

This includes protection of:

- governance rules
- authority boundaries
- decision and audit evidence
- intervention mechanisms
- version and configuration history
- rollback and recovery capability

Security controls themselves remain subject to legitimate authority.

### Change Control and Versioning

Governance structures must be able to evolve without silent or
unaccountable change.

Material changes should be versioned, traceable, reviewable, and revalidated
where their impact requires it.

---

## 5. Specialized Frameworks

Specialized frameworks apply selected parts of the Culture Key core to
specific governance conditions.

### STOP Framework 

The STOP Framework evaluates governance readiness before deployment,
major capability expansion, or increased real-world impact.

It examines four capabilities:

- Authority
- Veto Velocity
- Rollback Integrity
- Arbitration

STOP does not replace the Culture Key core.

It tests whether critical governance capabilities are operationally credible
before system impact increases.

---


## 6. Practical Application

### Pre-Scale Governance Audit

The Pre-Scale Governance Audit applies Culture Key to real systems approaching
deployment or increased scale.

It examines governance readiness rather than model performance alone.

The audit may identify gaps in areas such as:

- decision authority
- intervention capability
- escalation
- rollback and recovery
- accountability
- consent and boundaries
- traceability

Practical assessment methods may evolve independently from the underlying
governance architecture.

---


## 7. Reference Implementations

Culture Key may be demonstrated through specific:

- agents
- models
- orchestration structures
- technical components
- interaction flows

These are reference implementations.

They demonstrate possible ways to operationalize parts of the framework.

They are not universal requirements of Culture Key.

The governance architecture should remain valid when the underlying
technical implementation changes.

## Framework Boundary

Culture Key does not attempt to determine every correct decision in advance.

It defines the conditions under which consequential decisions can remain:

- legitimately authorized
- bounded
- accountable
- traceable
- contestable
- reviewable
- interruptible where necessary
- capable of correction when evidence or context changes

The framework should itself remain open to revision when evidence,
implementation experience, or governance failure reveals that one of its
assumptions no longer holds.

## Core Principle

**Increasing technical capability should not exceed the demonstrated
capacity for meaningful governance.**
