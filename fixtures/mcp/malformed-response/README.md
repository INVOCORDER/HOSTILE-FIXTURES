# Malformed MCP response

Fixture: `malformed-response`

Scenario:

Server returns malformed JSON-RPC response bytes across MCP stdio.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
