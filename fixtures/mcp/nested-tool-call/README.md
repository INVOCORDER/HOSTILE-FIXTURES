# Nested tool call

Fixture: `nested-tool-call`

Scenario:

Tool output contains evidence of a downstream nested tool action.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
