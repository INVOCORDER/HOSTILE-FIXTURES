# Reordered response

Fixture: `reordered-response`

Scenario:

MCP responses arrive out of request order.

Expected discipline:

- MachineActionRecord objects exist
- OmissionRecord exists
- ReplayBundle exists
- BundleIntegrityResult exists
- no truth claim
- no safety claim
- no authorization claim
- no admissibility claim
