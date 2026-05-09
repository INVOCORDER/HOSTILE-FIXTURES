# Signed Bundle Fixture Corpus

This fixture family defines adversarial signed-bundle scenarios for INVOCORDER v0.3.2.

A signed bundle verifier is not evidence-grade until it can distinguish:

- valid persistent signed bundle
- tampered signed bundle
- public key fingerprint mismatch
- truth overclaim in signature envelope

Required invariant:

- valid signature envelopes verify
- tampered bundles fail
- mismatched public key fingerprints fail
- truth/safety/authorization overclaims fail
- no admissibility claim is made
