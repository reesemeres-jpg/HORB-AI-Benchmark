# Healthcare Operational Reasoning Benchmark Suite

**Version:** 1.0  
**Author:** Meredith Reese, RN  
**Status:** Initial portfolio release

> An original benchmark suite for evaluating AI operational reasoning across realistic healthcare workflows.

## Executive Summary

Healthcare AI is increasingly being used in environments where safe decision-making depends on coordinating multiple evolving information sources rather than retrieving isolated facts.

This project presents an original benchmark suite designed to evaluate operational reasoning across realistic healthcare workflows. The benchmarks emphasize prioritization, ownership boundaries, workflow dependencies, temporal reasoning, and resource constraints while requiring AI systems to distinguish **apparent operational readiness** from **actual executable readiness**.

Rather than evaluating medical knowledge alone, the suite focuses on operational judgment in complex healthcare environments.

## Central Evaluation Question

> **Can an AI distinguish apparent operational readiness from actual executable readiness while making operationally sound decisions under realistic healthcare constraints?**

## Project Highlights

- 12 original healthcare operational reasoning benchmarks
- Fictional but realistic multi-document source materials
- Original system instructions, prompts, and grading rubrics
- Focus on operational judgment under uncertainty
- Cross-domain coverage across inpatient, ambulatory, perioperative, post-acute, behavioral health, pharmacy, and case management workflows

## Benchmark Domains

| Benchmark | Domain | Operational Focus |
|---|---|---|
| HORB-001 | Labor & Delivery Operations | Labor & Delivery Charge Nurse / OB Triage Flow |
| HORB-002 | Sterile Processing and Perioperative Operations | Sterile Processing / OR Case-Cart Readiness Flow |
| HORB-003 | Home Health Operations | Home Health Visit Coordination / Field Nursing Route |
| HORB-004 | Outpatient Infusion and Oncology Operations | Outpatient Infusion Center / Oncology Treatment Readiness |
| HORB-005 | Hospice Operations | Hospice On-Call / Symptom Crisis & Visit Routing |
| HORB-006 | Emergency Department Operations | Emergency Department Triage / Room Assignment & Ambulance Offload Flow |
| HORB-007 | Perioperative Operations | Perioperative OR Add-On / Turnover Flow |
| HORB-008 | Behavioral Health Operations | Behavioral Health Crisis Unit / Psychiatric Intake & Safety Placement |
| HORB-009 | Hospital Pharmacy and Transitions of Care | Hospital Pharmacy / Medication Reconciliation & Discharge Readiness |
| HORB-010 | Case Management and Discharge Planning | Hospital Case Management / Discharge Disposition & Throughput |
| HORB-011 | Perioperative Pre-Admission Testing | Perioperative Pre-Admission Testing / Day-of-Surgery Clearance |
| HORB-012 | Primary Care Operations | Primary Care Same-Day Triage / Schedule Routing Flow |


## Repository Structure

```text
Healthcare-Operational-Reasoning-Benchmark-Suite-v1.0/
├── README.md
├── LICENSE.md
├── CITATION.md
├── CHANGELOG.md
├── docs/
├── benchmarks/
│   ├── HORB-001_...
│   └── HORB-012_...
├── portfolio/
└── website/
```

## What Each Benchmark Includes

Each benchmark folder contains:

- `00_Design_Brief.md` — portfolio cover page and benchmark summary
- `UseCase_System_Prompt.md` — use case, system instructions, and user prompt
- `Strict_Grading_Guidelines.md` — grading methodology for evaluation
- `source_docs/` — extracted fictional operational source documents
- `SourceDocs.zip` — original source document archive
- `original_batches/` — original batch archives where available

## Design Philosophy

Healthcare operations reward appropriate restraint as much as decisive action. A high-quality operational plan does not simply identify what could happen next; it identifies what can actually happen next based on confirmed information, available resources, realistic workflow, and appropriate ownership.

This suite evaluates executable reasoning, not confident completion.

## Scope

All benchmark materials are fictional and were created for evaluation and portfolio purposes. No real patient information, health records, or healthcare organization data are included.
