# Missing tool result

Fixture: `missing-tool-result`

Scenario:

MCP request is captured but matching tool result never arrives.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
