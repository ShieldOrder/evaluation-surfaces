# Protocol Correctness Decision Surface

Status: surface definition  
Scope: consensus, cryptography, safety, and privacy correctness  
Posture: descriptive, non-prescriptive

---

## Definition

A **protocol correctness decision** is any decision whose validity depends on
technical truth rather than preference, sentiment, or economic alignment.

These decisions have a right or wrong answer in principle, even if uncertainty
exists in practice.

---

## Primary characteristics

Protocol correctness decisions are characterized by:

- binary or constrained correctness outcomes
- irreversible or high-cost failure modes
- system-wide externalities
- safety properties that cannot be compensated for by popularity

Examples include:
- consensus rule changes
- cryptographic primitive selection
- privacy mechanism design
- security parameter tuning
- validation and verification logic

---

## Correctness requirements

For a protocol correctness decision to be sound, it must satisfy:

- logical validity
- cryptographic soundness
- adversarial robustness
- compatibility with existing safety guarantees
- clear articulation of assumptions

Failure to meet these requirements cannot be justified by preference signals.

---

## Legitimate signals (high fitness)

Signals that provide meaningful information on this surface include:

- expert technical review
- formal analysis or proofs
- implementation experience
- adversarial testing and audits
- reproducible empirical results

These signals speak directly to correctness and safety.

---

## Weak or invalid signals (low fitness)

Signals that are weak or misleading on this surface include:

- popularity or sentiment measures
- economic exposure alignment
- majority voting without technical constraints
- narrative consensus
- time pressure or urgency framing

These signals do not measure correctness.

Using them as substitutes creates correctness risk.

---

## Failure modes

Common failure modes when this surface is mis-evaluated:

- **Correctness bypass**  
  Safety constraints overridden by preference or urgency.

- **Authority inflation**  
  Non-technical signals treated as binding authority.

- **Legitimacy laundering**  
  Process participation used to justify unsafe outcomes.

- **Irreversible error**  
  Faults discovered only after deployment.

---

## Boundary conditions

Protocol correctness decisions may consider preference *after* correctness
constraints are satisfied, but never in place of them.

This surface defines constraints, not direction.

---

## License

CC0 1.0 Universal
EOF
