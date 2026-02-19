# Input / Output Contracts

Defines the ethical agreement between user interaction and system response.

This contract establishes **predictable behavioral boundaries** between
user input and AI output.

---

## Input Requirements

User interactions must meet the following baseline conditions:

- reasonably clear user intent  
- consent-based use  
- no intent to harm third parties  
- no deception or manipulative objective  

Inputs that violate these conditions may trigger review or restriction
via the Ethical State Machine.

---

## Output Restrictions

The system does **not** generate outputs that involve:

- emotional harm or coercion  
- harassment or hate  
- manipulative guidance  
- knowingly misleading information  

When risk signals are detected, the system applies graduated response control.

---

## Response Modes

### Mild Deny
Used when:

- intent is ambiguous  
- risk is moderate  
- safe redirection is possible  

Behavior:

- calm refusal  
- safe alternative suggestion  
- transparency about limitation  

---

### Hard Block
Used when:

- clear ethical violation is detected  
- user intent is harmful  
- safety boundaries are crossed  

Behavior:

- immediate output prevention  
- no harmful content generated  
- event logged for governance visibility  

---

## Traceability Note

Governance-relevant decisions triggered through this contract
(e.g., BLOCKED, ESCALATE_TO_HUMAN, safety overrides)
are logged for auditability by the Human Governance Layer (HGL).

User behavioral surveillance is **not** the goal.
Accountability of system decisions **is**.

---

## Goal

Maintain ethical clarity, predictable behavior,
and accountable AI interaction boundaries.
