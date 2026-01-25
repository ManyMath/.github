# ManyMath, LLC

Full-stack software polymaths specializing in cryptography and cryptocurrency infrastructure and protocol engineering.

## What We Do

- Privacy-preserving cryptocurrency infrastructure and protocol engineering
- Cross-platform wallet systems supporting 15+ blockchain networks
- Complex cross-compilation and build systems for cryptographic libraries
- Security auditing for blockchain protocols and decentralized systems
- Advanced cryptographic implementations (RingCT, CoinJoin, zero-knowledge proofs)

## Selected Work

### Stack Wallet — Multi-Currency Privacy Wallet

Core engineering for a production multi-currency privacy wallet from Cypher Stack.

- Core contributor to a production wallet used globally across mobile and desktop
- Ported C++ Monero and Firo and Rust Epic Cash cryptocurrency libraries for Flutter to Windows
- Built system-wide Tor routing with `.onion` node support and Tor-only kill-switch modes
- Submitted upstream Tor-compatibility PRs for Solana, Tezos, and Stellar Flutter packages on pub.dev
- Cryptocurrency integrations: Salvium, Epic Cash, Solana, Litecoin Ordinals, Tezos, Stellar, Particl, Peercoin
- Integration maintenance: Monero, Wownero, Bitcoin, Bitcoin Cash, Litecoin, Firo, Dogecoin, Dash, Zcash, Ethereum, Banano, Nano
- Advanced features: FROST multisig, Tor-only networking, Replace-By-Fee, Solana SPL tokens, Litecoin Ordinals, CashFusion

**Build systems and cryptographic runtime engineering:**

- Architected Windows cross-compilation pipelines for privacy-coin stacks from Linux
- Automated CMake + Cargo + Flutter hybrid build systems
- Android NDK pipelines (arm64-v8a, armeabi-v7a, x86_64) with Rust and C++ integrations

### Tor & Arti — Privacy Network Integration

Cross-platform Tor and Arti networking stacks for Dart/Flutter from Foundation Devices and Cypher Stack.

- Maintainer and contributor to Flutter Tor tooling ([Foundation-Devices/tor](https://github.com/Foundation-Devices/tor), [cypherstack/tor](https://github.com/cypherstack/tor): [`tor`](https://pub.dev/packages/tor) on pub.dev)
- Built SOCKS5 and SSL/TLS socket layers for Tor-routed networking ([`socks_socket`](https://pub.dev/packages/socks_socket) on pub.dev)
- Created Rust-backed Arti bindings for Flutter ([ManyMath/darti](https://github.com/ManyMath/darti), [`arti`](https://pub.dev/packages/arti) on pub.dev)
- Cross-platform support: Android, iOS, Windows, macOS, Linux

### Monero Engineering — wallet2, Rust, WASM

Deep Monero wallet, protocol, and tooling engineering from Cake Labs, Serai DEX, and monero-oxide.

- Major contributor to `monero_c` and Flutter bindings for `wallet2` across all platforms
- Designed and implemented Rust-first Monero wallet cores ([`monero-rust`](https://crates.io/crates/monero-rust) on crates.io)
- Built full wallet pipelines: scanning, key images, decoy selection, fee logic, transaction construction
- Implemented stagenet/testnet transaction creation and output detection engines
- Developed WASM-compatible Monero wallet prototypes and browser-extension experiments

### CashFusion Protocol — Bitcoin Cash Privacy

Full collaborative transaction privacy protocol implementation from Cypher Stack.

- Implemented CashFusion protocol in Dart (fusiondart)
- Blind signatures, Pedersen commitments, Schnorr signing, covert submission flows
- Built session logic, blame validation, and coordinator messaging layers
- Integrated Tor transport and deployed into Stack Wallet

### Security Research & Protocol Auditing

Formal security review and cryptographic auditing from Cypher Stack and Power Up Privacy.

- Comprehensive audit on Serai DEX's `monero-serai` library
- Extended review of `monero-wallet` and `monero-oxide`
- Implementation audits: `CARROT` addressing scheme, Salvium `T-CLSAG`, `rage` encryption library

### Epic Cash & Slate-Based Systems

Epic Cash wallet, networking, and slate protocol engineering from Epic Labs and Cypher Stack.

- Maintained and overhauled flutter_libepiccash across all major platforms
- Implemented Tor networking and EpicBox failover systems and listener infrastructure
- Refactored transaction pipelines, slate parsing, and wallet concurrency models
- Designed test harnesses, example apps, and CI-friendly build systems

### Experimental Systems & R&D

Advanced research and experimental platforms from FiestaBerry and novel, independent productions.

- Built Ren'Py-compatible dialogue and scripting runtime in Flutter (FiestaVN, [`renpy_flutter`](https://pub.dev/packages/renpy_flutter) on pub.dev)
- Designed cryptographic game mechanics and zero-trust gameplay research prototypes
- Developed automated Monero wallet orchestration and testing systems
- Browser-extension wallet research and WASM wallet engines

## Technical Stack

**Core Languages:** Rust, C++, Dart, FFI and cross-language interop

**Cryptography:** RingCT, Schnorr, Pedersen commitments, implementation audits to spec

**Cross-Platform:** Flutter for all major platforms, JavaScript, TypeScript, React, React Native, WASM for browser targets

**Build Systems:** Rustup, Dart, CMake, MXE, MinGW64, NDK

**Privacy Infrastructure:** Tor (Arti), SOCKS5, .onion routing, network-level anonymity and kill-switches

**Blockchain Protocols:** Electrum, JSON-RPC, WebSocket, UTXO management, fee logic, derivation

## Engagement

We offer fixed-scope contracts, retainer engagements, and technical advisory services for privacy-focused blockchain projects.

Visit [manymath.com](https://manymath.com) for more information.
