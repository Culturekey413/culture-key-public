# Culture Key — Public Overview

*A human-governance framework for AI systems.*

Culture Key provides a governance structure for preserving human agency,
legitimate authority, accountability, intervention capacity, and meaningful
oversight as AI systems increase in capability, autonomy, complexity, or
real-world impact.

Its purpose is not to prescribe a specific AI architecture.

It defines governance conditions that should remain meaningful across
different models, agents, orchestration patterns, and technical
implementations.

---

## Why Culture Key exists

AI capability can evolve faster than the governance structures responsible
for supervising its use.

The resulting gap is not only a technical or safety problem.

It is a governance problem:

- Who holds legitimate authority?
- Who can intervene?
- How quickly can operation be restricted or stopped?
- What happens when legitimate principles conflict?
- Can a system recover safely after intervention?
- Can consequential decisions be reconstructed and reviewed?
- Can governance itself adapt when evidence shows that its assumptions
  no longer hold?

Culture Key is designed around this gap.

**Increasing technical capability should not exceed the demonstrated
capacity for meaningful governance.**

---

## Core Governance Architecture

Culture Key separates governance into distinct but interacting functions:

- **Authority** — who may make, authorize, review, restrict, or stop
  governance-relevant actions
- **Accountability** — how responsibility remains attributable across
  human and technical actors
- **Risk** — how conditions requiring governance attention are identified
  without allowing detection alone to determine the response
- **State and Decision Logic** — how evidence and governance decisions
  change operational state
- **Intervention and Recovery** — how systems can be restricted, paused,
  contained, rolled back, stopped, recovered, and revalidated
- **Arbitration** — how consequential conflicts between legitimate
  principles or authorities are resolved
- **Traceability and Review** — how decisions, evidence, authority, and
  outcomes remain reconstructable and open to correction

These functions should not be collapsed into a single model, agent,
decision-maker, or oversight mechanism.

Culture Key does not claim these governance functions as novel in isolation.

Its contribution is to examine whether they remain operationally credible
as an interacting governance system — particularly as technical capability,
autonomy, complexity, and real-world impact increase.

The question is therefore not only whether governance mechanisms exist,
but whether authority can become meaningful action, intervention can occur
in time, recovery remains possible, conflict can be legitimately resolved,
and decisions can be reviewed and corrected as evidence changes.

[Read the canonical Framework Map →](./docs/framework_map.md)

---

## Governance Is a Cycle

Culture Key does not treat governance as a one-way approval pipeline.

New evidence, changed context, system drift, intervention outcomes, or
review may require earlier decisions to be reconsidered.

Governance therefore includes the capacity to:

**detect → decide → intervene → recover → review → revalidate**

with accountability and traceability across the cycle, and arbitration
available when ordinary governance cannot resolve legitimate conflict.

The objective is not irreversible decision-making.

It is legitimate, evidence-sensitive correction.

---

## Specialized Framework: STOP

The **STOP Framework** examines governance readiness before deployment,
major capability expansion, or increased real-world impact.

It focuses on four operational capabilities:

1. **Authority** — Who can say stop?
2. **Veto Velocity** — How quickly can intervention become effective?
3. **Rollback Integrity** — Can the system return to a legitimate,
   recoverable state?
4. **Arbitration** — Who resolves consequential conflicts when ordinary
   governance is insufficient?

STOP does not replace the Culture Key core.

It applies selected parts of the core architecture to a specific governance
condition: whether intervention and recovery remain operationally credible
before system impact increases.

[Read the STOP Framework →](./frameworks/STOP_Framework_v1.md)

---

## Current Practical Application: Pre-Scale Governance

The current operational entry point for Culture Key is **pre-scale
governance**: the period before wider deployment or increased system impact,
while structural correction remains comparatively possible.

### Pre-Scale Governance Audit

The audit examines governance readiness rather than model performance alone.

It can be used to identify gaps involving:

- decision authority
- intervention capability
- escalation
- rollback and recovery
- accountability
- consent and boundaries
- traceability

[Start with the Pre-Scale Governance Audit →](./docs/prescale_audit.md)

[See a Pre-Scale Example →](./docs/prescale_example.md)

---

## Start Here

For a structured introduction to Culture Key:

1. [Framework Map →](./docs/framework_map.md)  
   Canonical overview of the governance architecture.

2. [Human Governance First →](./ethics/human_governance_first.md)  
   Foundational principle for meaningful human authority and oversight.

3. [Security Model →](./security/security_model.md)  
   Security and governance-integrity considerations.

4. [STOP Framework →](./frameworks/STOP_Framework_v1.md)  
   Specialized framework for intervention and pre-scale readiness.

5. [Pre-Scale Governance Audit →](./docs/prescale_audit.md)  
   Practical application of the framework to systems approaching scale.

---

## Public Repository Boundary

This repository contains public structural, conceptual, and governance
material.

It may include:

- governance architecture
- foundational principles
- specialized frameworks
- risk and failure-mode analysis
- security and governance-integrity material
- practical governance applications

Sensitive implementation details and internal governance material are not
part of this public repository.

[Read Public Scope →](./public_boundaries.md)

[Read Limitations →](./LIMITATIONS.md)

---

## Status

**Culture Key is an evolving human-governance framework.**

Its architecture is expected to remain open to revision when evidence,
implementation experience, or governance failure reveals that an assumption
no longer holds.

The framework is designed to govern changing systems without treating its
own current form as beyond review.
