# Prototype Environment II — Physical AI

The Physical AI prototype applies V1.0 governance to AI systems capable of interacting with and acting upon physical environments.

## Governance Scope

Physical AI introduces governance concerns involving environmental transitions, physical actuation, changing operational conditions, intervention, safe-state behavior, evidence preservation, maintenance, and controlled restart or redeployment.

V1.0 does not impose a universal SBJ autonomy-level taxonomy. Domain-specific authoritative autonomy classifications remain applicable where established.

## Safe State

**Safe State** is a cross-domain governance concept within the architecture. Domain-specific safety terminology and technical meanings remain intact.

## Environment Transition

A material environment transition is a first-class authorization concern. Transition Authorization is used to determine whether and under what approved conditions a Physical AI system may move across a governed environment or consequence boundary.

## Incident and Restart Governance

The V1.0 incident/restart flow is:

`Incident/Anomaly → Safe State → Evidence Preservation → Investigation → Diagnosis → Corrective Action → Validation → Restart Eligibility → New Authorization Decision → Controlled Restart/Redeployment`

Previous authority does not automatically revive following an incident, remediation, maintenance event, or controlled restart decision.

## Physical AI Authority Envelope

A Physical AI Authority Envelope may distinguish authority associated with:

- development
- testing
- validation
- deployment
- operation
- intervention
- maintenance
- restart or redeployment

## Accountability

Depending on the operating context, governance accountability may include development, deployment, operation, intervention, incident response, maintenance, restart/redeployment, and independent assurance roles.

## Public Boundary

This document intentionally omits proprietary enforcement logic, detailed control implementations, internal schemas, scoring logic, and internal testing mechanics.
