# Security & Safety Policy — Resetting World

Please report security vulnerabilities privately via **GitHub Security Advisories** in the affected repository (`rw-knowledge`, `rw-protocol`, or `rw-hardware`) rather than public issues.

Critical focus areas:
- **Offline Integrity**: Zero undocumented network callbacks or cloud dependencies.
- **Package Safety**: Safe zip/SQLite extraction without path traversal (`rw-knowledge`).
- **Cryptographic Safety**: Ed25519 verification, CBOR fuzzing, and anti-flooding in DTN relays (`rw-protocol`).
- **Electrical Safety**: Mandatory BMS, fusing, and MPPT limits for LiFePO4/solar setups (`rw-hardware`).
