# Versioning Policy

The Culture Key Versioning Policy defines how governance-relevant changes
are identified, reviewed, authorized, recorded, released, and, where
necessary, reversed.

Version history is treated as part of system integrity.

Its purpose is not only to show that something changed.

It should make it possible to determine whether the change was legitimate,
what assumptions it affected, and whether additional review or
revalidation became necessary.

---

## Scope

Versioning applies to governance-relevant changes including:

- ethical principles and protected constraints
- governance rules and decision boundaries
- authority structures and mandates
- Ethical State Machine logic
- risk models and materiality criteria
- intervention, stop, rollback, and recovery mechanisms
- escalation and arbitration paths
- accountability assignments
- Input / Output Contracts
- consent and privacy protocols
- governance-relevant metrics and thresholds
- other changes capable of materially altering governed system behavior

Not every editorial or documentation change requires the same governance
process.

Change control should be proportionate to the significance of the change.

---

## Change Classification

Changes should be classified according to their governance impact.

### Editorial Change

A change that improves wording, formatting, navigation, examples,
or documentation without materially altering governance meaning,
authority, system behavior, or protected boundaries.

Editorial changes should remain traceable but may use a lightweight
review process.

### Operational Change

A change that modifies implementation or operational behavior within
already approved governance boundaries.

Operational changes should be reviewed according to their risk,
reversibility, and potential impact.

### Material Governance Change

A change is material when it may alter:

- a protected principle or governance constraint
- the scope or holder of decision authority
- intervention or stop authority
- escalation or arbitration paths
- accountability or review rights
- state-transition logic
- risk classification or materiality criteria
- consent, privacy, or protection boundaries
- rollback, recovery, or revalidation requirements
- the assumptions under which a previous approval remains valid

Material governance changes require explicit authorized review before release.

---

## Change Record

Governance-relevant changes should record, where applicable:

- what changed
- why the change was proposed
- change classification
- affected governance components
- previous and resulting behavior or rule
- risk and impact assessment
- who proposed the change
- who evaluated it
- who had authority to approve it
- the basis of that approval authority
- whether independent review was required
- whether revalidation was required
- when the change became effective
- the version or release in which it appeared
- rollback or reversal path where applicable

A version number without an authority and decision record is not sufficient
governance traceability.

---

## Approval Authority

No actor should gain authority to approve a governance change merely
because they created, implemented, or detected the need for that change.

Approval authority should be defined according to:

- the type of change
- governance impact
- risk and reversibility
- affected rights or protected constraints
- operational scale
- applicable legal or organizational requirements

High-impact or contested changes may require independent or multi-party
review.

The number of reviewers is not itself evidence of legitimate governance.

What matters is whether the approving authority has the mandate,
independence, competence, and accountability required for that class
of change.

---

## Protected Boundaries

Changes to protected governance boundaries should not be introduced
through ordinary operational updates.

Where a proposed change affects a protected principle, authority boundary,
or critical safety mechanism, the applicable governance process should
require explicit review and authorization at the level defined for that
boundary.

An implementation should not be able to silently redefine the rules
that govern its own authority.

---

## Revalidation

A material change may invalidate assumptions under which previous
governance approval was granted.

Revalidation should be required when a change materially affects:

- system behavior
- authority structure
- safety controls
- risk exposure
- interaction between components or agents
- intervention or recovery capability
- protected governance assumptions

Revalidation should determine whether the modified system remains within
its approved governance baseline.

---

## Rollback and Reversal

Governance versioning should preserve the ability to identify and,
where appropriate, restore a previous known acceptable configuration.

Rollback planning should consider:

- whether the change is technically reversible
- whether downstream effects can also be reversed
- which authority may initiate rollback
- which authority may validate the restored configuration
- whether the previous version remains safe and legitimate under
  current conditions

Rollback should not be treated as automatically safe merely because
the previous version was previously approved.

---

## Emergency Changes

Urgent protective changes may sometimes be necessary before the ordinary
change process can be completed.

Where emergency change authority exists, its:

- trigger conditions
- scope
- authorized actors
- duration
- documentation requirements
- post-change review
- revalidation requirements

should be defined in advance.

Emergency authority may accelerate governance procedure.

It should not eliminate governance accountability.

---

## Version Integrity

Version history should allow reconstruction of:

- what governance baseline applied at a given time
- which rules and authority structures were active
- which material changes occurred
- who authorized those changes
- what evidence or rationale supported them
- whether rollback, review, or revalidation followed

Historical governance states should remain distinguishable from current ones.

---

## Design Principle

Culture Key treats governance versioning as part of system integrity,
not as administrative overhead.

A governed system should be able to answer not only:

**"What rules apply now?"**

but also:

**"What changed, under whose authority, why, and what did that change
require us to reconsider?"**

---

