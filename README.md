# Rishidar D. (Rishi)

Security-focused software engineer. I build verification-first tooling — systems where an AI or a user can *propose*, but deterministic code, policy, and cryptography *decide* — and I do independent, authorized bug-bounty research on the side.

Every project below carries a `## Status` section stating what is implemented, tested, live-verified, experimental, or historical. Nothing here claims production readiness unless demonstrated.

## Current engineering work

- **[sealbox](https://github.com/Rishidar-lab/sealbox)** — TypeScript CLI that seals a file to Shelby storage with a canonical, Ed25519-signed manifest and verifies it independently. v0.3.0; 174 tests, CI green. Upload path live-verified; live retrieval blocked on an upstream anonymous-tier limit (stated honestly as `PARTIAL`).
- **[nexescrow](https://github.com/Rishidar-lab/nexescrow)** — Non-custodial milestone escrow on EVM (Solidity 0.8.26, Foundry, Next.js). 57 Foundry tests incl. reentrancy PoC and fuzz invariants; testnet-only, unaudited; Demo 1 hardening (EIP-712 intents, resolver modules) is an open, unmerged PR stack. BOT Chain testnet evidence is kept separate from network assumptions.
- **Morphia** (private, hosted alpha v0.2.1) — orchestration for authorized security engagements: code-owned tool registry, live scope enforcement, human approval gates, signed execution receipts, evidence provenance. Not production-hardened for multi-tenant use.
- **[postalmind-ai](https://github.com/Rishidar-lab/postalmind-ai)** — bilingual (Tamil/English) public-interest evidence tooling; deployed and CI-smoke-tested.

## Research

- **[quantum-foundations-lab](https://github.com/Rishidar-lab/quantum-foundations-lab)** — executable lab rebuilding 3-qubit teleportation from the postulates so maths, code, tests and interpretation cross-check (v0.1.0, CI green).
- **[proof-of-reasoning](https://github.com/Rishidar-lab/proof-of-reasoning)** — *historical, failed hypothesis*: a 2026 design for a consensus-scored reasoning subnet, preserved with a criticism matrix and the lessons that moved later work toward deterministic verification.
- Protocol-architecture research corpus (Bitcoin, Ethereum, Monero, Babylon, Nexus and others) is maintained privately; nothing is published from it yet.

## Selected smaller builds

Hackathon-week reference implementations, each with CI and a stated scope ceiling:
[actionharbor](https://github.com/Rishidar-lab/actionharbor) (policy-gated action ledger, 379 tests) ·
[controldeck](https://github.com/Rishidar-lab/controldeck) (governance-vs-orchestration demo) ·
[sourcelens](https://github.com/Rishidar-lab/sourcelens) (evidence-grounded RAG) ·
[shiftpilot-ai](https://github.com/Rishidar-lab/shiftpilot-ai) (NL→deterministic scheduling, hosted) ·
[pi-runner](https://github.com/Rishidar-lab/pi-runner) (C++→WASM game, deployed).

## Historical / learning

[safecheck-pharos](https://github.com/Rishidar-lab/safecheck-pharos) (hackathon submission, 2026-07) · [defi-vibecoding-data-analysis](https://github.com/Rishidar-lab/defi-vibecoding-data-analysis) (Arbitrum Trailblazer dataset) · [online-food-ordering-cpp](https://github.com/Rishidar-lab/online-food-ordering-cpp) (academic). Archived placeholder repositories are marked as such and are candidates for deletion.

## Stack (as evidenced in the repositories above)

TypeScript / Node.js · Python / FastAPI · Solidity / Foundry · Next.js / React · C++ → WebAssembly · PostgreSQL · Docker · GitHub Actions.

## Authorship and AI assistance

Rishidar-lab is the owner, originator, and sole human creator of these projects unless a repository states otherwise. AI assistants (including Anthropic Claude) are used as development tools for research, coding, review, testing, and documentation; direction, acceptance of output, and responsibility remain with Rishidar-lab. Third-party code and data retain their own licenses.

## Contact

[Bugcrowd](https://bugcrowd.com/parzival) · [X / Twitter](https://twitter.com/RishidarD84283) · [Email](mailto:rishidar2000@gmail.com)
