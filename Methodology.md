# Methodology

## Healthcare Operational Reasoning Benchmark Methodology

Healthcare operations require decisions that extend beyond factual knowledge or document summarization. Coordinators must integrate evolving information from multiple operational sources while accounting for workflow constraints, ownership boundaries, limited resources, and patient safety.

This benchmark suite evaluates whether AI systems produce operationally realistic recommendations under those conditions.

## Core Evaluation Principle

> **Operational readiness cannot be inferred from apparent readiness.**

Healthcare environments contain many indicators that appear to suggest readiness:

- Green dashboards
- Scheduled appointments
- Completed checklists
- Ready rooms
- Copied-forward documentation
- Pending discharges
- Available beds
- Completed orders

These indicators often appear sufficient when viewed individually. In practice, operational execution frequently depends on additional owner-confirmed decisions, resource availability, evolving workflow constraints, or unresolved dependencies documented elsewhere.

The benchmarks evaluate whether an AI system recognizes that distinction.

## Benchmark Construction Process

### 1. Select an operational workflow

Each benchmark begins with a realistic healthcare workflow, such as emergency department triage, sterile processing, home health routing, hospice on-call routing, medication reconciliation, case management, or primary care triage.

### 2. Create a fictional operational environment

Each benchmark includes fictional but operationally plausible documents representing the types of information available to healthcare coordinators. These may include operational boards, staffing assignments, secure messages, callback logs, nursing notes, scheduling views, transport updates, equipment status, pharmacy updates, and huddle agendas.

### 3. Introduce realistic operational uncertainty

Benchmarks intentionally include evolving operational conditions such as conflicting documentation, copied-forward information, pending owner decisions, staffing changes, workflow bottlenecks, and unresolved dependencies.

### 4. Require prioritization among plausible actions

The strongest scenarios are not built around a single obvious correct answer. They require the model to weigh multiple operationally plausible actions and identify what can realistically happen next.

### 5. Evaluate operational reasoning

Models are evaluated on whether they distinguish confirmed information from apparent readiness, respect ownership boundaries, identify unresolved dependencies, prioritize realistically, allocate limited resources appropriately, and avoid unsupported operational commitments.

## Evaluation Philosophy

Healthcare operations require balancing decisiveness with appropriate restraint. A high-quality operational plan does not simply recommend the next possible action. It identifies the next action that is realistically executable based on available evidence while explicitly recognizing unresolved dependencies that remain outside the coordinator's authority.

For this reason, the benchmark suite rewards operational judgment rather than confident completion.
