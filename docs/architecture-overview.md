# Architecture Overview

## SBJ AI Governance Architecture V1.0

SBJ AI Governance Architecture V1.0 provides a governance structure for AI systems whose capabilities, authority, operating environments, and consequences can change over time.

The Solutions by Jewel website is the canonical public source for V1.0:

https://solutionsbyjewel.com/sbj-ai-governance-architecture-v1

### Ten Governance Dimensions

The Governance Dimensions characterize capabilities and governance conditions that may exist within an AI system. They may overlap and are not maturity stages.

| Dimension | Governance focus |
|---|---|
| Generation | The extent to which an AI system creates, transforms, predicts, recommends, synthesizes, or otherwise produces outputs from available inputs and context. |
| Assistance | The role an AI system performs in supporting human activity, judgment, decision-making, analysis, creation, or execution. |
| Agency | The capacity of an AI system to pursue a defined objective through planning, task selection, tool use, sequencing, or consequential action. |
| Autonomy | The degree to which an AI system can operate, decide, or act without contemporaneous human direction or approval. |
| Environmental Interaction | The extent to which an AI system receives information from, interprets, responds to, or changes conditions within a digital or physical operating environment. |
| Physical Actuation | The capacity of an AI system to produce physical action through vehicles, robotics, machinery, devices, infrastructure, or other actuated systems. |
| Authority | The formally permitted scope within which an AI system, agent, or governed actor may act, including applicable boundaries, approvals, credentials, targets, conditions, and limitations. |
| Evidence | The records, observations, artifacts, logs, approvals, decisions, and other information required to establish what occurred and under what governed conditions. |
| Accountability | The assignment and preservation of responsibility for authorization, oversight, operation, intervention, outcomes, and governance decisions associated with an AI system. |
| Continuous Control | The ongoing monitoring, reassessment, intervention, restriction, and governance necessary to keep an AI system within approved conditions throughout operation and lifecycle change. |

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

### Operational Authorization Sequence

`IDENTITY → GOAL → CAPABILITY → AUTHORITY → PERMISSION → ENVIRONMENT → ACTION → OBSERVATION → EVIDENCE → ACCOUNTABILITY → CONTINUOUS CONTROL`

This sequence does not replace the Ten Governance Dimensions.

### SBJ Methodology Relationship

The SBJ AI Governance Architecture sits across the methodology stack as the cross-cutting architecture.

- **STRATA™** — GRC foundation.
- **SIGNAL™** — AI-specific control and audit methodology.
- **Decision Record** — Governance-decision accountability and evidence practice.
- **SYNTHESIZE™** — Physical AI governance methodology.
- **NIST MEASURE** — Separate 25-point Solutions by Jewel assessment scale aligned to the NIST AI RMF MEASURE function. It is not a NIST-developed scoring system, NIST certification, or NIST endorsement.

The public V1.0 package does not disclose scoring, weighting, certification, derivation, evidence-sufficiency, or implementation mechanics for these methodologies.

### Human Operational-Use Interpretation

Adversarial Testing Cycle 1 clarified that consequence/exposure includes material changes in how AI outputs are operationally consumed, acted upon, escalated, automated, or embedded in downstream workflows, regardless of whether the AI system itself has technically changed.

A human-configured process, organizational practice, downstream workflow, or operating decision that materially changes the practical consequence or exposure associated with an AI output constitutes a governance-relevant change under V1.0. Where that change crosses an approved consequence/exposure boundary, Transition Authorization is required.

This interpretation introduced no new architecture construct and required no V1.0 modification.

## Reference Context

The public V1.0 package is informed by established AI governance, risk-management, management-system, terminology, and regulatory sources, including NIST AI RMF, ISO/IEC 42001, ISO/IEC 22989, OECD AI governance materials, and the EU Artificial Intelligence Act — Regulation (EU) 2024/1689.

See [Public References](references.md).

These references do not imply endorsement, certification, or validation of SBJ AI Governance Architecture by the referenced institutions.
