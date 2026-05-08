# Replay bundle tamper

Fixture: `replay-bundle-tamper`

Scenario:

Replay bundle hash chain is deliberately corrupted and must fail integrity verification.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
