cat > README.md <<'EOF'
# Evaluation Surfaces

Status: analytical infrastructure  
Scope: governance evaluation semantics  
Posture: descriptive, non-prescriptive

This repository defines a taxonomy for evaluating governance decisions by
separating **decision surfaces** from **legitimacy signals**.

It is not a governance proposal.
It does not advocate mechanisms.
It does not recommend reforms.
It does not take positions.

Its sole purpose is to reduce category errors where a signal is applied to a
decision type it cannot credibly evaluate.

## What this repository does

- Defines distinct classes of governance decisions ("decision surfaces")
- Describes properties of common legitimacy signals
- Documents failure modes when signals are misapplied
- Provides neutral analytical language for precise governance discussion

## What this repository does not do

- Propose voting systems
- Argue for or against coin voting
- Recommend governance structures
- Reference specific ZIPs, upgrades, or timelines
- Make normative claims about legitimacy

All signals discussed are treated as legitimate within their appropriate scope.

## Structure

- `surfaces/`  
  Decision surface definitions (what kind of decision is being made)

- `signals/`  
  Legitimacy signal properties (what a signal can and cannot measure)

- `failure-modes/`  
  Common breakdown patterns when signal–surface fit is violated

## Usage

This material is intended to be cited surgically in governance discussions to
clarify *what is being decided* and *what evidence is being used*, without
escalating into ideological debate.

## License

CC0 1.0 Universal  
This work is dedicated to the public domain.
EOF
