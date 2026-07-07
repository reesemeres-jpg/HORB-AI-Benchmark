# HORB Methodology

## Core Evaluation Principle

Operational readiness cannot be inferred from apparent readiness.

Healthcare environments contain many indicators that appear to suggest readiness:

- Green dashboards
- Scheduled appointments
- Completed checklists
- Ready rooms
- Copied-forward documentation
- Pending discharges
- Available beds
- Completed orders

These indicators often appear sufficient when viewed individually. In practice, operational execution frequently depends on additional owner-confirmed decisions, resource availability, workflow constraints, staffing, safety checks, or unresolved dependencies documented elsewhere.

HORB evaluates whether an AI system recognizes that distinction.

## Benchmark Construction Process

### 1. Select an operational workflow

Each benchmark begins with a realistic healthcare workflow, such as emergency department triage, sterile processing, home health routing, hospice on-call routing, medication reconciliation, case management, or primary care triage.

### 2. Create a fictional operational environment

Each benchmark includes fictional but operationally plausible documents representing the types of information available to healthcare coordinators.

These may include:

- Operational boards
- Staffing assignments
- Secure messages
- Callback logs
- Nursing notes
- Scheduling views
- Transport updates
- Equipment status
- Pharmacy updates
- Huddle agendas

### 3. Introduce realistic operational uncertainty

Benchmarks intentionally include evolving conditions such as:

- Conflicting documentation
- Copied-forward information
- Pending owner decisions
- Staffing changes
- Workflow bottlenecks
- Unresolved dependencies
- Time-sensitive updates

### 4. Require prioritization among plausible actions

The strongest scenarios are not built around a single obvious correct answer.

They require the model to weigh several operationally plausible actions and identify what can realistically happen next.

### 5. Evaluate operational reasoning

Models are evaluated on whether they:

- Distinguish confirmed information from apparent readiness
- Respect ownership boundaries
- Identify unresolved dependencies
- Prioritize realistically
- Allocate limited resources appropriately
- Avoid unsupported operational commitments

## Evaluation Philosophy

Healthcare operations require balancing decisiveness with appropriate restraint.

A high-quality operational plan does not simply recommend the next possible action. It identifies the next action that is realistically executable based on available evidence while explicitly recognizing unresolved dependencies that remain outside the coordinator’s authority.

HORB rewards operational judgment rather than confident completion.
