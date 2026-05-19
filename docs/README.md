# TIME Coin Protocol Documentation

Technical documentation for the TIME Coin protocol and node software.

> **Operator setup guides** (installation, masternode configuration, CLI reference) live in the [time-masternode repo](https://github.com/time-coin/time-masternode/tree/main/docs).

---

## Documents

| File | Description |
|------|-------------|
| [TIMECOIN_PROTOCOL.md](TIMECOIN_PROTOCOL.md) | Complete protocol specification (§1–§27) including TimeVote, TimeLock, VRF sortition, fee collection, and cryptography rationale |
| [ARCHITECTURE_OVERVIEW.md](ARCHITECTURE_OVERVIEW.md) | System architecture, full transaction/consensus flow, and TimeProof conflict detection |
| [NETWORK_ARCHITECTURE.md](NETWORK_ARCHITECTURE.md) | P2P network layer design, peer management, TLS, and network configuration reference |
| [COMPREHENSIVE_SECURITY_AUDIT.md](COMPREHENSIVE_SECURITY_AUDIT.md) | Full attack-vector analysis (AV1–AV37+) with root causes, fix status, and AI detection coverage |
| [SECURITY-PROTOCOL.md](SECURITY-PROTOCOL.md) | Vulnerability reporting policy, threat analysis, and UTXO attack vectors |
| [CONTRIBUTING-NODE.md](CONTRIBUTING-NODE.md) | Development guidelines and commit conventions for the Rust/blockchain node codebase |
| [ROADMAP.md](ROADMAP.md) | Development roadmap and version history |
| [payment-request-protocol.md](payment-request-protocol.md) | Payment request URI and protocol specification |
| [TIME_Coin_Whitepaper.docx](TIME_Coin_Whitepaper.docx) | Official TIME Coin whitepaper (Word format) |
| [GOVERNANCE.md](GOVERNANCE.md) | On-chain governance: proposal submission, masternode voting, and treasury disbursement without hard forks |
| [QUICK_REFERENCE.md](QUICK_REFERENCE.md) | Developer quick reference — concrete algorithms, wire formats, and protocol parameters for v6 |
| [CLI_GUIDE.md](CLI_GUIDE.md) | `time-cli` command-line RPC client reference with usage examples |
| [QUICKSTART.md](QUICKSTART.md) | Developer quickstart: build, test, and run TIME Coin locally |
| [MASTERNODE_GUIDE.md](MASTERNODE_GUIDE.md) | Masternode setup: tiered collateral configuration, `time.conf`/`masternode.conf`, and registration |
| [LINUX_INSTALLATION.md](LINUX_INSTALLATION.md) | Step-by-step production installation guide for Linux servers |

### Archive

Historical protocol versions are in [`_archive_protocol/`](_archive_protocol/):

| File | Description |
|------|-------------|
| [TIMECOIN_PROTOCOL_V6.md](_archive_protocol/TIMECOIN_PROTOCOL_V6.md) | Protocol v6 (superseded) |
| [TIMECOIN_PROTOCOL_V5.md](_archive_protocol/TIMECOIN_PROTOCOL_V5.md) | Protocol v5 |
| [TIMECOIN_PROTOCOL_V5_backup.md](_archive_protocol/TIMECOIN_PROTOCOL_V5_backup.md) | Protocol v5 backup snapshot |
| [CONSENSUS_UPDATE_SUMMARY.md](_archive_protocol/CONSENSUS_UPDATE_SUMMARY.md) | Summary of consensus changes across versions |
| [CONSENSUS_IMPROVEMENT_PROPOSAL.md](_archive_protocol/CONSENSUS_IMPROVEMENT_PROPOSAL.md) | Original consensus improvement proposal |
