# Server crash mid-call

Fixture: `server-crash-mid-call`

Scenario:

MCP server exits before returning tool result.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
