# HORB: Healthcare Operational Reasoning Benchmark Suite

**Version:** 1.0  
**Author:** Meredith Reese, RN  
**Status:** Initial public portfolio release  

> HORB is an original healthcare AI benchmark suite for evaluating operational reasoning, workflow judgment, and executable decision-making across realistic healthcare settings.

## Overview

Healthcare AI is increasingly being used in environments where safe and useful decisions depend on more than isolated medical facts. In real healthcare workflows, the correct next step often depends on timing, staffing, ownership boundaries, documentation quality, resource availability, and whether a task is actually executable.

HORB was created to evaluate whether AI systems can reason through that kind of operational complexity.

Rather than testing medical knowledge alone, HORB focuses on whether a model can distinguish **apparent operational readiness** from **actual executable readiness**.

## Central Evaluation Question

> **Can an AI distinguish apparent operational readiness from actual executable readiness while making operationally sound decisions under realistic healthcare constraints?**

## Project Highlights

- **12** original healthcare operational reasoning benchmarks
- **336** fictional source documents
- Realistic multi-document workflows across healthcare operations
- Original system instructions, task prompts, grading guidelines, and design briefs
- Focus on prioritization, uncertainty, workflow constraints, ownership boundaries, and source-grounded reasoning
- Built from a nursing-informed perspective on real operational decision-making
- No PHI, real patient records, or confidential healthcare organization data

## Why HORB Exists

Many AI benchmarks test factual recall, isolated reasoning, or cleanly structured tasks. Healthcare operations are different. Real workflows are messy, time-sensitive, and dependent on multiple evolving sources of information.

A model may sound confident while still missing the practical question that matters most:

**Can this action actually happen right now?**

HORB is designed to surface those failure modes.

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
HORB-AI-Benchmark/
âââ README.md
âââ LICENSE.md
âââ CITATION.md
âââ CHANGELOG.md
âââ FILE_INDEX.md
âââ docs/
â   âââ Executive_Summary.md
â   âââ Methodology.md
â   âââ Benchmark_Overview.md
â   âââ Common_Failure_Modes.md
â   âââ Scope_and_Limitations.md
â   âââ additional project documentation
âââ portfolio/
â   âââ Project_Summary.md
â   âââ About_Meredith.md
â   âââ Resume_Bullets.md
âââ benchmarks/
â   âââ HORB_v1_0_12_Benchmark_Package.zip
â   âââ HORB-001_...
â   âââ HORB-002_...
â   âââ HORB-012_...
âââ website/
    âââ index.html
    âââ style.css
```

The full benchmark set may be included as a downloadable zip package and/or as browsable benchmark folders.

## What Each Benchmark Includes

Each HORB benchmark includes:

- `00_Design_Brief.md` â benchmark summary and design rationale
- `UseCase_System_Prompt.md` â use case, system instructions, and task prompt
- `Strict_Grading_Guidelines.md` â scoring and evaluation criteria
- `source_docs/` â fictional operational source documents
- `SourceDocs.zip` â archived source document package
- `Source_Documents_Manifest.md` â source document list
- `original_batches/` â original batch archives where available

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

Healthcare operations reward appropriate restraint as much as decisive action. A high-quality operational plan does not simply identify what could happen next; it identifies what can actually happen next based on confirmed information, available resources, realistic workflow, and appropriate ownership.

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

## Documentation

Key supporting documents include:

- [`docs/Executive_Summary.md`](docs/Executive_Summary.md)
- [`docs/Methodology.md`](docs/Methodology.md)
- [`docs/Benchmark_Overview.md`](docs/Benchmark_Overview.md)
- [`docs/Common_Failure_Modes.md`](docs/Common_Failure_Modes.md)
- [`docs/Scope_and_Limitations.md`](docs/Scope_and_Limitations.md)
- [`portfolio/Project_Summary.md`](portfolio/Project_Summary.md)

## Scope and Disclaimer

All benchmark materials are fictional and were created for evaluation and portfolio purposes. No real patient information, health records, or healthcare organization data are included.

HORB is not clinical decision support, medical advice, patient-care guidance, or a substitute for institutional policy, clinician judgment, or licensed medical practice.

## Author

Created by **Meredith Reese, RN**.

HORB reflects clinical nursing experience applied to healthcare AI evaluation, source-grounded reasoning, workflow analysis, and rubric-based model review.

## Citation

See [`CITATION.md`](CITATION.md) for suggested citation format.

## License

See [`LICENSE.md`](LICENSE.md) for reuse terms and limitations.
