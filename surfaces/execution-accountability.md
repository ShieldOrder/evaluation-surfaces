cat > surfaces/execution-accountability.md <<'EOF'
# Execution and Accountability Decision Surface

Status: surface definition  
Scope: verification of delivery, enforcement of commitments, handling of failure  
Posture: descriptive, non-prescriptive

---

## Definition

An **execution and accountability decision** governs how commitments are
verified, how failures are handled, and how responsibility is assigned
after a decision has been made.

This surface is not about *what should be done*, but about *whether what was promised actually occurred*.

---

## Primary characteristics

Execution and accountability decisions are characterized by:

- verifiability of claims
- enforceability of commitments
- attribution of responsibility
- asymmetric information between operators and observers
- irreversibility once funds or authority are exercised

Examples include:
- milestone validation
- delivery acceptance or rejection
- corrective action after failure
- revocation of authority
- dispute resolution

---

## Evaluation requirements

Sound evaluation on this surface requires:

- objective verification criteria
- unambiguous success and failure states
- pre-declared enforcement mechanisms
- independence between executor and verifier
- clear assignment of responsibility

Ambiguity benefits operators, not systems.

---

## Legitimate signals (high fitness)

Signals that provide meaningful information on this surface include:

- cryptographic verification
- deterministic test results
- third-party audits with scoped authority
- reproducible artifacts
- explicit milestone definitions

These signals directly measure execution reality.

---

## Supporting but limited signals (medium fitness)

Signals that may inform but cannot bind outcomes:

- narrative explanations
- progress reports without verification
- community goodwill
- historical reputation

These signals may contextualize failure but cannot substitute for verification.

---

## Weak or invalid signals (low fitness)

Signals that are weak or misleading on this surface include:

- popularity or sentiment
- voting outcomes unrelated to verification
- urgency framing
- post hoc rationalization

These signals do not measure execution.

---

## Failure modes

Common failure modes when this surface is mis-evaluated:

- **Accountability collapse**  
  No mechanism exists to enforce consequences.

- **Verification theater**  
  Reports replace proofs.

- **Responsibility diffusion**  
  Failure is attributed to process rather than actors.

- **Irreversible drift**  
  Resources are expended without recoverability.

---

## Boundary conditions

Execution accountability requires authority to say **no**, **stop**, or **fail**.

Without enforcement power, evaluation is symbolic.

This surface governs responsibility, not preference.

---

## License

CC0 1.0 Universal
EOF
