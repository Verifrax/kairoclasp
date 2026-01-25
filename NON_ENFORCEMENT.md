# Non-Enforcement Declaration

KAIROCLASP is a **timestamping primitive**, not an enforcement mechanism.

## What KAIROCLASP does

- Timestamps input data
- Outputs deterministic timestamp hash
- Returns exit code indicating success/failure of timestamping

## What KAIROCLASP does NOT do

- Validate content correctness
- Enforce time-based rules
- Verify timestamp accuracy
- Make trust decisions
- Block or allow actions

## Enforcement responsibility

Enforcement is the responsibility of:
- The calling system (CICULLIS, MK10-PRO, etc.)
- The policy layer above KAIROCLASP
- Human decision-makers

## Liability

KAIROCLASP output indicates "this was timestamped" — nothing more.
Timestamping does not imply accuracy, correctness, or validity.
