# HORB: Healthcare Operational Reasoning Benchmark Suite

**Version:** 1.0  
**Author:** Meredith Reese, RN  
**Status:** Initial public portfolio release  

HORB is an original healthcare AI benchmark suite designed to evaluate operational reasoning across realistic healthcare workflows.

The project focuses on whether AI systems can distinguish **apparent operational readiness** from **actual executable readiness** when working with complex, multi-document healthcare scenarios.

## Executive Summary

Healthcare AI is increasingly being used in environments where safe and useful decision-making depends on coordinating multiple evolving information sources rather than retrieving isolated facts.

HORB evaluates whether AI systems can reason through realistic healthcare operations involving prioritization, workflow dependencies, ownership boundaries, temporal constraints, documentation quality, staffing limits, and resource availability.

Rather than evaluating medical knowledge alone, HORB focuses on operational judgment in complex healthcare environments.

## Central Evaluation Question

> Can an AI distinguish apparent operational readiness from actual executable readiness while making operationally sound decisions under realistic healthcare constraints?

## Project Highlights

- 12 original healthcare operational reasoning benchmarks
- 336 fictional healthcare operations source documents
- Original system instructions, task prompts, design briefs, and grading rubrics
- Focus on operational judgment under uncertainty
- Cross-domain coverage across inpatient, ambulatory, perioperative, post-acute, behavioral health, pharmacy, and case management workflows
- Fictional materials only; no PHI, real patient records, or confidential healthcare organization data

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

## Repository Contents

This repository includes the public portfolio release of HORB v1.0.

Key files include:

- `Executive_Summary.md` — high-level project summary
- `Project_Summary.md` — concise portfolio summary
- `Methodology.md` — benchmark design and evaluation methodology
- `Benchmark_Overview.md` — overview of the 12 benchmark domains
- `Common_Failure_Modes.md` — model failure patterns HORB is designed to reveal
- `Scope_and_Limitations.md` — project scope, limitations, and intended use
- `Design_Philosophy.md` — principles behind the benchmark suite
- `Why_Nursing_Matters.md` — how nursing experience informed the project
- `CITATION.md` — suggested citation format
- `LICENSE.md` — reuse terms and limitations
- `FILE_INDEX.md` — index of the full benchmark package contents
- `HORB_v1_0_12_Benchmark_Package.zip` — downloadable package containing the 12 benchmark scenarios

## 12-Benchmark Package

The full benchmark set is included as a downloadable zip file:

`HORB_v1_0_12_Benchmark_Package.zip`

The package contains all 12 benchmark folders. Each benchmark includes:

- `00_Design_Brief.md` — benchmark summary and design rationale
- `UseCase_System_Prompt.md` — use case, system instructions, and task prompt
- `Strict_Grading_Guidelines.md` — scoring and evaluation criteria
- `source_docs/` — fictional operational source documents
- `SourceDocs.zip` — archived source document package
- `Source_Documents_Manifest.md` — list of source documents
- `original_batches/` — original batch archives where available

## Core Capabilities Evaluated

HORB evaluates whether AI systems can handle:

- Multi-document reasoning
- Operational prioritization
- Temporal reasoning
- Workflow coordination
- Resource allocation
- Ownership boundaries
- Source provenance
- Uncertainty management

## Common Failure Modes

HORB is designed to reveal failures such as:

- Treating apparent readiness as actual readiness
- Making premature operational commitments
- Ignoring unresolved dependencies
- Violating role or ownership boundaries
- Relying on stale or copied-forward information
- Missing time-sensitive safety signals
- Producing polished but unsupported plans

## Design Philosophy

Healthcare operations reward appropriate restraint as much as decisive action.

A high-quality operational plan does not simply identify what could happen next. It identifies what can actually happen next based on confirmed information, available resources, realistic workflow, and appropriate ownership.

HORB evaluates **executable reasoning**, not confident completion.

## Intended Uses

HORB may be useful for:

- Healthcare AI evaluation
- LLM benchmark design
- Clinical workflow reasoning review
- AI response grading and rubric design
- Healthcare operations simulation
- Clinical documentation and operational QA portfolio work
- Demonstrating healthcare domain expertise in AI evaluation roles

## Scope and Disclaimer

All benchmark materials are fictional and were created for evaluation and portfolio purposes. No real patient information, health records, or healthcare organization data are included.

HORB is not clinical decision support, medical advice, patient-care guidance, or a substitute for institutional policy, clinician judgment, or licensed medical practice.

## Author

Created by **Meredith Reese, RN**.

HORB reflects clinical nursing experience applied to healthcare AI evaluation, source-grounded reasoning, workflow analysis, and rubric-based model review.

## Citation

See `CITATION.md` for suggested citation format.

## License

See `LICENSE.md` for reuse terms and limitations.
