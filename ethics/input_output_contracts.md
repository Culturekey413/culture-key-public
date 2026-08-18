# Input / Output Contracts

Input / Output Contracts define the governance boundaries that apply when
external input enters an AI system and when system output is produced.

Their purpose is not to require ideal user behavior.

Their purpose is to ensure that the system responds predictably,
proportionately, and accountably across different kinds of interaction.

The governed object is the interaction and the system response —
not the identity or character of the person interacting.

---

## Core Principle

An input may contain ambiguity, error, harmful intent, manipulation,
conflicting instructions, or incomplete information.

These conditions do not remove the system's governance obligations.

The system remains responsible for operating within its approved boundaries
regardless of whether the incoming request itself satisfies those boundaries.

Input classification should therefore evaluate the governance relevance
of the interaction without converting that assessment into a judgment
about the user as a person.

---

## Input Handling

Inputs may be evaluated for conditions including:

- ambiguity or insufficient context
- potential harm
- manipulation or coercion attempts
- deceptive or conflicting instructions
- consent-related concerns
- attempts to exceed authorized system boundaries
- governance-relevant uncertainty
- signals associated with known or emerging risk patterns

Detection of such a condition does not automatically determine the response.

Evaluation and resulting action must follow the applicable governance rules,
authority boundaries, and Ethical State Machine.

---

## Output Boundaries

System outputs must remain within approved governance and safety boundaries.

Depending on context, this may require the system to:

- provide the requested output
- request clarification
- provide a bounded or modified response
- refuse a prohibited action
- offer a safer alternative where appropriate
- restrict or pause execution
- trigger additional review
- escalate when the required decision exceeds current authority

The system should not intentionally produce outputs that rely on
unjustified coercion, manipulation, harassment, deception, or other
prohibited methods defined by the applicable governance baseline.

The possibility that an accurate, necessary, or appropriately bounded
response may cause discomfort does not by itself make that response
a governance violation.

---

## Response Governance

Input / Output Contracts do not define a separate response-state system.

Governance-relevant interaction states and transitions are handled through
the Ethical State Machine.

The contract defines what the interface must preserve while those
mechanisms operate:

- approved behavioral boundaries
- proportional response
- authority limits
- traceability where governance-relevant
- meaningful routes for review or escalation

A system must not expand its own authority simply because an input presents
a case not anticipated by existing rules.

Novelty is a reason for evaluation or escalation where required,
not permission for autonomous authority expansion.

---

## Authority

Detection of a risky or unusual input does not automatically grant authority
to restrict, block, or escalate the interaction.

The applicable governance implementation should define:

- who or what may classify relevant input conditions
- who or what may evaluate their materiality
- which responses may be selected autonomously
- which interventions require additional authority
- when review or escalation becomes mandatory

Where an action exceeds the current actor's mandate, the decision must follow
the predefined escalation path.

---

## Interaction Context and Drift

Governance should not rely only on isolated input/output pairs.

Patterns across interactions may reveal:

- repeated boundary pressure
- recurring exceptions
- changes in system response behavior
- inconsistent application of governance rules
- authority drift
- emerging failure patterns

Such patterns may trigger governance review when material.

Pattern analysis should remain proportionate to its governance purpose and
should not become unnecessary behavioral surveillance.

---

## Traceability

Governance-relevant interaction decisions should be traceable according to
their impact.

Where applicable, the record should make it possible to determine:

- what condition was detected
- what input or context was relevant to the decision
- who or what evaluated the condition
- what response was selected
- who or what had authority to authorize that response
- whether a state transition occurred
- whether review, escalation, or arbitration was triggered
- what final outcome resulted

Traceability should focus on accountability for system decisions rather
than unnecessary profiling of users.

---

## Privacy, Safety, and Proportionality

Governance visibility does not justify unlimited data collection,
persistent profiling, or behavioral surveillance.

Information should be processed only to the extent reasonably necessary
for the applicable governance, safety, audit, or accountability purpose.

A governance concern should not automatically become a persistent
classification of the person who initiated the interaction.

However, where available information indicates a credible and serious
risk to the life, physical safety, or fundamental rights of one or more
people, additional processing or escalation may be justified where
necessary and legally permitted.

The determination that such a threshold has been met must be made through
an authorized assessment process appropriate to the severity and context
of the risk.

Such exceptional action should be:

- proportionate to the severity and credibility of the risk
- limited to information necessary for the protective purpose
- governed by predefined authority and escalation rules
- subject to applicable law and organizational obligations
- traceable and reviewable
- discontinued when the exceptional justification no longer applies

The system should distinguish between assessing risk in an interaction
and making persistent claims about the identity or character of a person.

Govern the interaction by default.

Depart from that default only when a serious protective need,
legitimate authority, and proportionate basis justify doing so.
---

## Final Principle

Input / Output Contracts define how a governed system meets the outside world.

Users are not required to behave perfectly for governance to function.

The system is required to remain within its legitimate boundaries even
when they do not.
