Case ID: CK-EDL-005

Scenario:
Multiple agents produce conflicting internal signals regarding user intent.

Example pattern:
- Aequitas flags potential ethical risk.
- Lychnia detects benign user intent.
- Magna detects system uncertainty.

Detected Risk:
Multi-agent disagreement / signal conflict.

Ethical State Machine:
REVIEW → ESCALATE_TO_HUMAN (if unresolved)

Human Governance Decision:
When agent disagreement persists, the system must prioritize safety and clarity.

Reasoning:
Conflicting internal signals indicate uncertainty.
Uncertainty requires conservative handling to preserve user safety and system integrity.

Output Policy:
- Avoid confident or risky output
- Provide cautious, neutral response
- Request clarification if appropriate
- Escalate to Human Governance Layer when conflict threshold is exceeded
- Log disagreement event

Outcome:
System enters safe-resolution mode and either:
- provides cautious guidance, or
- requests clarification, or
- escalates to human review.

Logged by:
Culture Key — Human Governance Layer (HGL)
