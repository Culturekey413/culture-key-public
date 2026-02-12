# Ethical State Machine Rules

The Ethical State Machine defines how the system evaluates situations and responds.

## Purpose
Provide predictable and consistent ethical behavior.

## States

### SAFE
Normal operation. No ethical concerns detected.

### REVIEW
Potential issue detected. Requires human review.

### BLOCKED
Clear violation. Output is prevented.

### ESCALATE_TO_HUMAN
Ethical dilemma requiring human judgment.

## Transition Logic (Initial)

- SAFE → REVIEW when risk signals appear
- REVIEW → BLOCKED when violation confirmed
- REVIEW → SAFE when cleared
- BLOCKED → ESCALATE_TO_HUMAN in ambiguous cases

## Goal
Consistency, predictability, and controlled ethical decisions.
