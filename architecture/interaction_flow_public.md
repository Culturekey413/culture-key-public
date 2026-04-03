# Interaction Flow (Public – High Level)

## Purpose
This document describes the high-level flow of how inputs are processed within the Culture Key system.

It provides structural transparency without exposing internal logic, thresholds, or implementation details.

---

## Core Flow

User Input  
↓  
Aequitas (Ethical Pre-Check)  
↓  
Lychnia Bridge (Semantic Clarification)  
↓  
Magna (Orchestration & Decision Layer)  
↓  
[Optional] Human Escalation  
↓  
PosterKit (Controlled Output Delivery)

---

## Step-by-Step Description

### 1. User Input
A request, message, or interaction enters the system.

No assumptions are made about intent at this stage.

---

### 2. Aequitas — Ethical Pre-Check
- Evaluates input for ethical signals and potential risk patterns
- Detects ambiguity, manipulation risk, or safety concerns
- Does not take action, only flags or clears

---

### 3. Lychnia Bridge — Semantic Clarification
- Interprets meaning and emotional nuance
- May generate clarification responses if intent is unclear
- Ensures communication remains human-aligned and non-escalatory

---

### 4. Magna — Orchestration & Decision
- Coordinates system response based on inputs from previous layers
- Determines whether:
  - normal response proceeds
  - clarification is sufficient
  - escalation is required

---

### 5. Human Escalation (if required)
- Triggered when ethical ambiguity or risk exceeds acceptable boundaries
- May require:
  - single human approval
  - double approval (for sensitive cases)

---

### 6. PosterKit — Controlled Output
- Delivers final response
- Ensures output respects system constraints and communication integrity

---

## Key Principles

### No Autonomous Ethical Mutation
Core ethical behavior does not change without explicit human approval.

---

### Controlled Transparency
The system exposes structure, not internal logic.

---

### Human Authority Retained
Final authority remains with human oversight where required.

---

## Notes

- This flow represents a generalized pathway.
- Not all interactions require escalation or full traversal of all stages.
- Internal evaluation criteria are intentionally not disclosed.
