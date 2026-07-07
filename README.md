# HORB: Healthcare Operational Reasoning Benchmark Suite

**Version:** 1.0  
**Author:** Meredith Reese, RN  
**Initial Public Portfolio Release:** July 2026  

HORB is an original healthcare AI evaluation benchmark suite designed to test whether large language models can reason through realistic healthcare operations rather than simply retrieve facts or summarize documents.

The central question behind HORB is:

> Can an AI distinguish apparent operational readiness from actual executable readiness while making operationally sound decisions under realistic healthcare constraints?

## Project Overview

Healthcare workflows often contain signals that appear to indicate readiness: green dashboards, scheduled appointments, clean rooms, completed checklists, signed orders, available beds, and copied-forward documentation.

In practice, those signals are often not enough.

Execution may still depend on staffing, transport, equipment, medication readiness, updated clinical status, receiving-unit acceptance, provider decisions, safety gates, authorization status, or ownership boundaries.

HORB evaluates whether AI systems can recognize that difference.

## What HORB Tests

HORB focuses on operational judgment across healthcare workflows, including:

- Multi-document reasoning
- Operational prioritization
- Temporal reasoning
- Workflow coordination
- Resource allocation
- Ownership boundaries
- Source provenance
- Uncertainty management

## Suite at a Glance

- **12** benchmark workflows
- **336** fictional operational source documents
- **12** healthcare operational domains
- **8** core capability categories
- **30–45 minutes** estimated human evaluation time per benchmark
- **0** real patients, PHI, or confidential clinical records

## Benchmark Domains

| ID | Benchmark Domain |
|---|---|
| HORB-001 | Labor & Delivery / OB Triage Flow |
| HORB-002 | Sterile Processing / OR Case-Cart Readiness |
| HORB-003 | Home Health Visit Coordination / Field Nursing Route |
| HORB-004 | Outpatient Infusion / Oncology Treatment Readiness |
| HORB-005 | Hospice On-Call / Symptom Crisis & Visit Routing |
| HORB-006 | Emergency Department Triage / Room Assignment & Ambulance Offload |
| HORB-007 | Perioperative OR Add-On / Turnover Flow |
| HORB-008 | Behavioral Health Crisis Unit / Psychiatric Intake & Safety Placement |
| HORB-009 | Medication Reconciliation & Discharge Readiness |
| HORB-010 | Case Management / Discharge Disposition & Throughput |
| HORB-011 | Pre-Admission Testing / Day-of-Surgery Clearance |
| HORB-012 | Primary Care Same-Day Triage / Schedule Routing |

## Core Evaluation Principle

**Operational readiness cannot be inferred from apparent readiness.**

A strong model response should not simply choose the action that looks available. It should determine which action is actually executable based on the evidence provided, while recognizing unresolved dependencies and limits of authority.

## Why Nursing Matters

HORB was shaped by bedside nursing experience. Healthcare operations require constant prioritization, reassessment, coordination, and judgment under incomplete information.

These benchmarks evaluate whether AI can navigate the kind of practical cognitive load that appears in real healthcare workflows: competing priorities, multiple stakeholders, limited resources, evolving patient status, and incomplete documentation.

## Repository Contents

This repository includes:

- Portfolio overview
- One-page project summary
- Methodology notes
- Scoring framework
- Capability taxonomy
- Failure-mode taxonomy
- Benchmark domain summaries
- Roadmap for future development

## Intended Use

HORB is intended for:

- Healthcare AI evaluation
- Clinical model quality review
- Medical data annotation
- AI response grading
- Clinical documentation review
- Workflow reasoning assessment
- Portfolio/work-sample demonstration

## Important Disclaimer

All HORB materials use fictional healthcare scenarios. HORB is intended for AI evaluation and portfolio use only.

It is **not** clinical decision support, medical advice, patient-care guidance, or a substitute for institutional policy, clinician judgment, or licensed medical practice.

## Author

Created by **Meredith Reese, RN**.

This project reflects clinical nursing experience applied to healthcare AI evaluation, source-grounded reasoning, rubric-based model review, and operational workflow analysis.
