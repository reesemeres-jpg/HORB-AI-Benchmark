# Lessons Learned

Building this suite led to several observations about healthcare AI evaluation and benchmark design.

## Operational reasoning differs from documentation review

Documentation review and chart-based reasoning often produced stronger model performance than expected. Operational planning under uncertainty produced richer evaluation behavior because the model had to coordinate evolving information, people, resources, and workflow constraints.

## Realistic workflow constraints matter

The benchmarks became more discriminative when they included staff roles, ownership boundaries, resource limitations, and time constraints. These elements shifted the task from information retrieval to operational judgment.

## Prompt simplification increased difficulty

Early iterations used more detailed prompts and system instructions. Simplifying the task framing often increased benchmark strength because the model had to derive the relevant operational reasoning from the source documents rather than relying on explicit prompt guidance.

## Multiple plausible actions produced richer evaluation

Scenarios with one clearly correct operational choice were often too easy. The strongest benchmarks required prioritizing among multiple reasonable actions, similar to nursing-style prioritization where several choices may be defensible but one is most appropriate given the situation.

## Operational restraint is a key evaluation signal

A strong response often involved identifying what should not be done yet. The suite rewards appropriate uncertainty, escalation, and handoff rather than unsupported confidence.
