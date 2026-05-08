# Malformed MCP request

Fixture: `malformed-request`

Scenario:

Client sends malformed JSON-RPC request bytes across MCP stdio.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
