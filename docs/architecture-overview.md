# Architecture Overview

## SBJ AI Governance Architecture V1.0

SBJ AI Governance Architecture V1.0 provides a governance structure for AI systems whose capabilities, authority, operating environments, and consequences can change over time.

### Ten Governance Dimensions

| Dimension | Governance focus |
|---|---|
| Generation | AI creation or transformation of content, outputs, recommendations, or artifacts |
| Assistance | AI support provided to human decision-makers or operators |
| Agency | AI capacity to pursue goals and perform actions through tools or systems |
| Autonomy | Degree of independent operation within approved conditions |
| Environmental Interaction | Interaction with digital, organizational, operational, or physical environments |
| Physical Actuation | AI-directed or AI-influenced physical action |
| Authority | Scope and conditions under which the system is permitted to act |
| Evidence | Records sufficient to establish what occurred, under what authority, and with what result |
| Accountability | Attribution of governance responsibility across relevant actors and systems |
| Continuous Control | Ongoing verification that authorization and operating conditions remain satisfied |

### Three-Axis System State

The architecture evaluates governed system state across three axes:

**Lifecycle Stage × Authorization Status × Runtime Operational State**

This structure supports governance decisions when a system changes lifecycle position, authorization condition, or runtime state.

### Authority Envelope

An **Authority Envelope** is the bounded set of conditions within which an AI system or agent is authorized to act. Depending on context, the envelope may include the actor or system, action, target, tool, credential, environment, time, delegated authority, approval, stop conditions, and evidence requirements.

### Transition Authorization

**Transition Authorization** governs whether and under what approved conditions a system may cross a governed environment, lifecycle, privilege, capability, autonomy, or consequence boundary.

### Derived Authorization

**Derived Authorization** is newly scoped authority issued as the result of an event, state or condition, decision, validation, remediation, or authorized transition. Previous authority does not automatically transfer, revive, or expand.

### Decision-to-Action Authority Traceability

The architecture requires governance traceability across:

`Authorization Decision → Execution Instance Identity → Authorized Execution Chain → Consequential Effect → Evidence`

### Supporting Governance Constructs

V1.0 also applies:

- Independent Downstream Authority
- Adverse Evidence Preservation
- Safe State
- Execution Instance Identity
- Continuous Authorization
- Independent Termination Authority

### Human Operational-Use Interpretation

Adversarial Testing Cycle 1 clarified that consequence/exposure includes material changes in how AI outputs are operationally consumed, acted upon, escalated, automated, or embedded in downstream workflows, regardless of whether the AI system itself has technically changed.

A human-configured process, organizational practice, downstream workflow, or operating decision that materially changes the practical consequence or exposure associated with an AI output constitutes a governance-relevant change under V1.0. Where that change crosses an approved consequence/exposure boundary, Transition Authorization is required.

This interpretation introduced no new architecture construct and required no V1.0 modification.

## Reference Context

The public V1.0 package is informed by established AI governance, risk-management, management-system, terminology, and regulatory sources, including NIST AI RMF, ISO/IEC 42001, ISO/IEC 22989, OECD AI governance materials, and the EU Artificial Intelligence Act — Regulation (EU) 2024/1689.

These references do not imply endorsement, certification, or validation of SBJ AI Governance Architecture by the referenced institutions.
