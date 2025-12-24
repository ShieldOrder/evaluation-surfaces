# Evaluation Surfaces

Status: analytical infrastructure  
Posture: descriptive, non-prescriptive  
Scope: governance evaluation semantics

This repository defines a taxonomy for evaluating governance decisions by separating decision surfaces from legitimacy signals.

It is not a governance proposal.  It does not advocate mechanisms.  It does not recommend reforms.  It does not take positions.

Its purpose is to reduce category errors where a signal is applied to a decision type it cannot credibly evaluate.

## What this repository provides

- Defines distinct classes of governance decisions ("decision surfaces")
- Describes properties and limits of common legitimacy signals
- Documents failure modes when signals are misapplied
- Provides neutral analytical language for governance discussion

## What this repository does not provide

- No prescriptions, mandates, or enforcement
- No scoring or ranking system
- No authority claims, representation claims, or endorsements
- No dispute resolution mechanism for legitimacy debates

## Repository structure

- surfaces/  
  Decision surface definitions and properties.

- signals/  
  Legitimacy and evaluation signals, with their credible domains.

- failure-modes/  
  Common errors and pathologies when signals are used outside their credible domains.

## How to use

- Identify the decision surface first.
- Identify which signals are being used to evaluate it.
- Check whether the signal can credibly evaluate that surface.
- If not, name the mismatch and the expected failure mode.

This is intended to improve clarity of discussion, not to settle disputes by fiat.

## Versioning

Current version is in `VERSION`.

Versioning intent:
- Patch releases may clarify language or framing without changing meaning.
- Any change that alters meaning of a definition requires a version increment and changelog entry.
- Prior versions remain accessible for historical comparison.

## Interpretation and disagreement

This taxonomy is one possible framing.
Different observers or institutions may interpret these categories differently based on context, constraints, or governance norms.
When interpretations conflict, this repository provides no resolution mechanism.  Communities retain full discretion to interpret or disregard these definitions.
Disagreement should be framed as a category disagreement, not an attribution of intent.

## Related Work

This repository is part of a set of independent, descriptive process artifacts published by ShieldOrder.

Related repositories include:

- **Process Layer Doctrine (PLD)**  
  Defines execution hygiene invariants for governance and funding systems.  
  PLD focuses on process legibility, role separation, and verification surfaces.  
  https://github.com/ShieldOrder/process-layer-doctrine

- **Proposal Disclosure Schema (PDS)**  
  A voluntary disclosure template for applicants to surface assumptions, scope boundaries, risks, and verification artifacts.  
  PDS focuses on applicant-side clarity.  
  https://github.com/ShieldOrder/proposal-disclosure-schema

Relationship between repositories:

- PDS addresses *input clarity* (what is being proposed and under what assumptions).
- PLD addresses *process hygiene* (how decisions are executed and verified).
- Evaluation Surfaces addresses *evaluation semantics* (which signals can credibly evaluate which decisions).

Each repository is standalone, non-authoritative, and may be adopted, ignored, or forked independently under CC0.

## License

CC0
EOF
