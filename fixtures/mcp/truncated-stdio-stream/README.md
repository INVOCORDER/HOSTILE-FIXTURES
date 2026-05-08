# Truncated stdio stream

Fixture: `truncated-stdio-stream`

Scenario:

MCP stdio stream terminates mid-frame.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
