# Ethical State Machine — Rules (Public)

The Ethical State Machine defines the high-level decision logic used to evaluate
risk signals and determine appropriate system behavior.

It ensures responses remain predictable, auditable, and aligned with human oversight.

---

## Purpose

Provide consistent and structured ethical behavior across AI interactions.

The model is designed to:

- reduce ambiguity in edge cases  
- enforce safety boundaries  
- support human-in-the-loop governance  
- maintain predictable system responses  

---

## Public States

### SAFE
Normal operation.

**Condition:**
- No material ethical risk detected.

**System behavior:**
- Output proceeds normally.
- Standard monitoring remains active.

---

### REVIEW
Potential concern detected.

**Condition:**
- Risk signals present but not conclusive.
- Intent or context unclear.

**System behavior:**
- Additional scrutiny applied.
- May trigger soft safeguards.
- Eligible for human review.

---

### BLOCKED
Confirmed ethical violation.

**Condition:**
- High-confidence policy breach.
- Manipulation, deception, or safety violation detected.

**System behavior:**
- Output is prevented.
- Safe alternative may be offered.
- Event is logged.

---

### ESCALATE_TO_HUMAN
Human judgment required.

**Condition:**
- High-impact ambiguity.
- Value conflict or sensitive edge case.

**System behavior:**
- Decision deferred to human governance.
- No autonomous resolution.
- Escalation path recorded.

---

## Transition Logic (High-Level)

The system follows structured transitions:

- **SAFE → REVIEW**  
  Triggered when risk signals exceed baseline thresholds.

- **REVIEW → BLOCKED**  
  Triggered when violation confidence becomes high.

- **REVIEW → SAFE**  
  Triggered when concern is cleared.

- **BLOCKED → ESCALATE_TO_HUMAN**  
  Triggered in rare ambiguous or high-impact cases.

---

## Design Goals

The Ethical State Machine is designed to provide:

- behavioral predictability  
- bounded autonomy  
- human oversight guarantees  
- audit-friendly decision paths  

This public model describes the external logic only.  
Internal scoring, thresholds, and enforcement mechanisms remain private.
