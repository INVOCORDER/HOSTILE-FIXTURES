# MCP Hostile Fixture Corpus

This fixture family defines adversarial MCP boundary scenarios for INVOCORDER v0.2 runtime support.

A v0.2 MCP boundary recorder is not valid until it can process these fixture classes without overclaiming.

Required invariant:

- capture request boundary facts when available
- capture response boundary facts when available
- declare omissions when capture is malformed, truncated, missing, redacted, crashed, or outside scope
- preserve hash-chain continuity
- emit replay bundle
- emit bundle integrity result
- never claim truth
- never claim safety
- never claim authorization
- never claim admissibility
