cat > surfaces/README.md <<'EOF'
# Decision Surfaces

Status: analytical taxonomy  
Scope: classification of governance decision types  
Posture: descriptive, non-prescriptive

This directory defines **decision surfaces**.

A decision surface is the *type of decision being made*, independent of:
- who decides
- how legitimacy is signaled
- what mechanism is used

Separating decision surfaces from legitimacy signals is necessary to avoid
category errors where a signal is applied to a decision it cannot credibly evaluate.

---

## What is a decision surface?

A decision surface is defined by:
- the kind of correctness it requires
- the kind of accountability it implies
- the failure modes it must defend against

Different decision surfaces require different forms of justification.
No single signal is fit for all surfaces.

---

## Non-goals

This directory does NOT:
- propose governance mechanisms
- recommend voting systems
- rank legitimacy signals
- argue for reforms
- take positions on governance philosophy

It only classifies decision types.

---

## Surfaces defined here

Each file in this directory specifies:
- the nature of the decision
- what must be true for the decision to be sound
- what kinds of signals are informative vs misleading

Defined surfaces include:

- **protocol-correctness.md**  
  Decisions where technical safety and correctness dominate.

- **resource-allocation.md**  
  Decisions involving distribution of funds or scarce resources.

- **execution-accountability.md**  
  Decisions about delivery, enforcement, and responsibility.

- **preference-signaling.md**  
  Decisions informed by stakeholder sentiment or directional input.

These surfaces are orthogonal.  
Confusing them is a primary source of governance failure.

---

## Relationship to signals

Legitimacy signals (defined in `../signals/`) are evaluated *relative to a surface*.

A signal may be strong on one surface and weak or invalid on another.
This framework does not assign authority. It assigns **fitness**.

---

## License

CC0 1.0 Universal
EOF
