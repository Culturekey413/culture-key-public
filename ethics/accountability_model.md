# Accountability Model

The Culture Key accountability model defines clear human responsibility,
oversight authority, and escalation structure for AI-governed environments.

---

## Control Authority

**Human Governance Layer (HGL)** retains ultimate control.

Responsibilities:
- approves policy changes
- authorizes high-risk decisions
- validates escalation outcomes
- can halt or override system behavior

No autonomous component can modify governance rules.

---

## Audit Responsibility

Audit functions ensure traceability and verifiability.

Primary mechanisms:
- decision logs
- risk flags
- integrity checks
- post-validation review

Audits may be performed by:
- internal governance reviewers
- designated ethics reviewers
- authorized external auditors (when applicable)

---

## Responsibility Mapping

Accountability is explicitly assigned:

- **HGL:** final ethical authority  
- **Codex Root:** policy integrity  
- **Aequitas:** runtime ethical enforcement  
- **Magna:** system coordination integrity  
- **PosterKit:** controlled output generation  

This prevents responsibility diffusion.

---

## Escalation Process

When risk or ambiguity is detected:

**LOW RISK**
→ handled within system guardrails

**MEDIUM RISK**
→ Ethical State Machine triggers REVIEW

**HIGH RISK**
→ ESCALATE_TO_HUMAN (HGL required)

**CRITICAL**
→ system restriction or block until human decision

Escalation latency and outcomes are logged.

---

## Design Principle

Culture Key enforces:

- explicit human accountability  
- verifiable decision paths  
- no silent autonomous authority  
- governance before scale

  
  ## Responsibility Matrix (RACI)

| Function | Responsible | Accountable | Consulted | Informed |
|----------|------------|------------|-----------|----------|
| Policy integrity | Codex Root | Human Governance Layer | Ethics reviewers | Org stakeholders |
| Runtime ethics enforcement | Aequitas | Human Governance Layer | Magna | Product teams |
| System coordination | Magna | Human Governance Layer | Aequitas | Ops teams |
| Output safety | PosterKit | Human Governance Layer | Lychnia | End users |
| High-risk decisions | Human Governance Layer | Human Governance Layer | Relevant experts | Audit logs |

**RACI key:**

- **R — Responsible:** executes  
- **A — Accountable:** final authority  
- **C — Consulted:** provides input  
- **I — Informed:** notified
