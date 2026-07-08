# HORB-001: Labor & Delivery Charge Nurse / OB Triage Flow

**Suite:** Healthcare Operational Reasoning Benchmark Suite  
**Version:** 1.0  
**Author:** Meredith Reese, RN  
**Original File Mapping:** Submission 019

> Evaluating operational reasoning under uncertainty in labor & delivery operations.

## Clinical Domain

Labor & Delivery Operations

## Operational Setting

Hospital-based Labor & Delivery unit

## Operational Window

5:30 PM to 5:45 PM before the Labor and Delivery flow huddle.

## Primary Capability Evaluated

Operational reasoning under uncertainty in a multidisciplinary obstetric workflow.

## Purpose

Evaluates whether an AI system can coordinate a Labor & Delivery flow window involving OB triage arrivals, labor-room admissions, postpartum transfers, scheduled inductions, possible urgent C-section evaluation, fetal monitoring changes, anesthesia coverage, Mother-Baby capacity, transport limits, medication readiness, and OR readiness.

## Primary Evaluation Question

> **Can the model distinguish apparent readiness from executable readiness while producing an operationally realistic plan for this workflow?**

## Capability Profile

| Capability | Evaluated |
|---|:---:|
| Multi-document reasoning | ✓ |
| Operational prioritization | ✓ |
| Temporal reasoning | ✓ |
| Workflow coordination | ✓ |
| Resource allocation | ✓ |
| Ownership boundaries | ✓ |
| Source provenance | ✓ |
| Uncertainty management | ✓ |


## Operational Actors

- Charge nurse
- OB providers
- Labor nurses
- Anesthesia
- OB OR team
- Mother-Baby receiving unit
- Transport
- Pharmacy / blood bank


## Reasoning Challenges

- Competing maternal/fetal priorities
- Labor-room and postpartum bed availability
- Fetal monitoring changes
- Anesthesia and OR readiness
- GBS/medication readiness
- Transport limits
- Receiving-unit acceptance
- Interdisciplinary communication


## Typical Failure Modes

- Premature labor-room assignment
- Assuming a clean room or open OB OR is usable
- Ignoring fetal-monitoring or anesthesia dependencies
- Overlooking postpartum receiving constraints
- Unrealistic sequencing before the huddle
- Unsupported assumptions from green board status


## Expected High-Quality Response

A strong response should:

- Integrate information across multiple documents.
- Distinguish confirmed information from apparent readiness.
- Respect ownership boundaries and role authority.
- Recognize unresolved dependencies.
- Prioritize realistically under time and resource constraints.
- Recommend only operationally executable actions.
- Carry unresolved issues forward to the appropriate huddle or owner.

## Included Materials

- `UseCase_System_Prompt.md`
- `Strict_Grading_Guidelines.md`
- `source_docs/` (28 fictional operational documents)
- `SourceDocs.zip`
- `original_batches/`

## Estimated Difficulty

**Expert**

## Estimated Human Evaluation Time

Approximately **30–45 minutes**.

## Design Notes

This benchmark was designed to evaluate operational judgment rather than factual recall. It presents multiple operationally plausible actions and requires prioritization based on safety, workflow constraints, source provenance, and confirmed operational readiness. The benchmark fits the suite's core design principle: operational readiness cannot be inferred from apparent readiness.

## Keywords

Labor & Delivery • OB triage • charge nurse • obstetric flow • operational reasoning • AI evaluation • benchmark design • healthcare operations
