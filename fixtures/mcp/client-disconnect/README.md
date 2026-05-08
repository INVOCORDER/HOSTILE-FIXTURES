# Client disconnect

Fixture: `client-disconnect`

Scenario:

MCP client disconnects before response capture completes.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
