# Tool result with secret-like payload

Fixture: `secret-like-tool-result`

Scenario:

Tool result contains secret-like material that must be redacted while preserving hash evidence.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
