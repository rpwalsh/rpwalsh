# Ryan Walsh

## Staff / Principal Systems Engineer  
### Deterministic Systems • Secure Platforms • Graph/Data Modeling • Embedded & Signal-Aware Tooling

I build systems that make ambiguous, high-risk technical domains inspectable, deterministic, and operational.

My work sits at the intersection of systems engineering, graph-based modeling, secure analytics, embedded tooling, and AI-assisted development. I specialize in taking messy real-world constraints — inconsistent data, unclear requirements, fragile workflows, hardware behavior, security requirements, and cross-functional ambiguity — and turning them into software systems that can be reasoned about, tested, visualized, and trusted.

I am most effective when the problem is not yet cleanly defined.

---

## What I Build

I build software platforms that usually include some combination of:

- Data ingestion from inconsistent or semi-structured sources
- Normalization into strongly typed internal models
- Graph-based entity representation
- Deterministic inference or classification
- Visualization of dependencies, bottlenecks, and risk
- Secure or auditable storage
- Hardware-aware or field-system integration
- Tooling that helps humans make better technical decisions

The common thread is not a language or framework.

The common thread is this:

> Turn unclear systems into inspectable systems.

---

## Current Engineering Focus

### Deterministic AI and Non-LLM Reasoning

I am interested in inference systems that do not depend entirely on opaque language-model behavior.

My work explores:

- Graph-based reasoning
- Spectral retrieval
- BM25 / SVD search
- Provenance tracking
- Deterministic answer planning
- Concept learning
- Explainable synthesis
- Local-first cognition engines

The goal is not to replace LLMs everywhere.

The goal is to build systems where reasoning paths can be inspected, replayed, constrained, and trusted.

Relevant work:

- `scce`
- `graphOS`

---

### Secure and Auditable Platforms

I build systems where correctness, traceability, and operational trust matter.

This includes:

- Air-gapped analytics
- Append-only authenticated storage
- Audit chaining
- Native cryptographic primitives
- PIV/CAC-style authentication models
- mTLS service boundaries
- Offline-first user interfaces
- Deterministic execution paths

Relevant work:

- `ImpactX`
- `blockchain-voting-system`

---

### Embedded, RF, and Hardware-Adjacent Tooling

I also work close to hardware: embedded systems, radio tooling, diagnostic systems, and protocol reconstruction.

This includes:

- ESP32 / ESP-IDF systems
- Timing-sensitive modulation
- Controlled waveform generation
- SSTV transmission
- RF experimentation tooling
- Reverse-engineered radio programming software
- Binary layout reconstruction
- USB protocol transport
- Codeplug validation
- Vehicle telemetry and diagnostics

Relevant work:

- `ghostemitter`
- `baofeng_1702b`
- `onboarddiagnosticstool`

---

### Visualization and Decision Systems

A large part of my work is making hidden system behavior visible.

I build interfaces and visual models for:

- Hardware planning
- Power and battery behavior
- Dependency analysis
- Risk visualization
- Graph navigation
- Real-time telemetry
- Operational decision support

I have built production systems using:

- SVG
- Canvas
- WebGL
- Three.js
- D3
- React
- TypeScript
- JavaScript

The interface is not decoration.

The interface is how the system becomes understandable.

---

## Selected Public Systems

### GraphOS

Rust-based operating system project with UEFI bootloader, capability-secured microkernel direction, GPU-composited desktop model, and deterministic on-device cognitive engine.

This project represents my interest in tightly scoped systems where operating environment, interface, cognition, and security model are designed together rather than bolted on after the fact.

Key themes:

- Rust systems programming
- UEFI boot flow
- Capability-oriented architecture
- Deterministic local cognition
- OS-level user experience design
- No-LLM reasoning architecture

---

### SCCE

LLM-independent inference engine using graph reasoning, spectral retrieval, BM25/SVD search, Kneser-Ney grounded synthesis, concept learning, provenance tracking, and deterministic answer planning.

SCCE is an exploration of how to build reasoning systems that can explain why they produced an answer.

Key themes:

- Graph reasoning
- Semantic search
- Retrieval architecture
- Deterministic inference
- Provenance-aware output
- Explainable answer planning
- Concept-level learning

---

### ImpactX

Air-gapped analytical and classification platform with native C99 cryptography, PIV/CAC and mTLS authentication concepts, append-only authenticated storage, audit chaining, HTTPS APIs, and offline-first TypeScript UI.

ImpactX is built around the idea that analytical systems should preserve trust boundaries, support offline operation, and maintain an inspectable chain of custody for decisions and data.

Key themes:

- Secure analytics
- Air-gapped operation
- Native C99 systems code
- Cryptographic validation
- Append-only storage
- Audit chains
- Offline-first UI

---

### Baofeng 1702B CPS

Reverse-engineered Windows CPS and CLI suite for Baofeng DM-1702/1702B radios with codeplug reconstruction, deterministic image synthesis, USB protocol transport, firmware analysis, and validation tooling.

This project reflects my interest in practical reverse engineering: understanding undocumented systems well enough to build safer, testable, inspectable tooling around them.

Key themes:

- Reverse engineering
- Binary layout reconstruction
- Protocol transport
- Radio programming tooling
- Validation and test coverage
- C# / .NET systems tooling

---

### GhostEmitter

ESP32 / ESP-IDF RF experimentation platform for controlled waveform generation, SSTV transmission, hardware-level radio interfacing, timing-precise modulation, and gesture-triggered control.

GhostEmitter is a field-system project focused on low-level embedded control and timing-sensitive signal behavior.

Key themes:

- ESP32
- ESP-IDF
- Embedded C
- RF tooling
- Timing-sensitive modulation
- SSTV
- Hardware interface control

---

### Blockchain Voting System

Cryptographically verifiable election platform with Express/Prisma backend, React/Vite frontend, blockchain-style audit visualization, vote verification, and election playback.

This project explores auditability and replayability in civic-scale systems.

Key themes:

- Cryptographic verification
- Election integrity
- Audit visualization
- Replayable state
- TypeScript full-stack systems
- Trust-preserving workflows

---

### Onboard Diagnostics Tool

Browser-native OBD2 diagnostics console for ELM327 Bluetooth adapters with live PID streaming, DTC read/clear, VIN/calibration access, vehicle profiles, charts, and raw ECU command execution.

This project applies telemetry, diagnostics, and interface design to real-world vehicle systems.

Key themes:

- Vehicle telemetry
- Live diagnostics
- PID streaming
- Browser-native tooling
- Root-cause analysis
- Real-time charts

---

## Professional Background

Most recently, I served as an L5 Senior Software Engineer at Meta through Spectraforce, operating as the sole technical owner of an internal power-planning and modeling platform for wearable and mixed-reality hardware development.

That work involved:

- Ingestion of fragmented planning data
- Normalization into structured entities
- Graph-based modeling
- Forecasting workflows
- Visualization of power, thermal, and battery constraints
- OLED emissive power analysis
- AI-assisted engineering workflows using Claude and MCP
- Cross-functional communication with engineering, product, and leadership stakeholders

The work was full-stack, but the important part was not the stack.

The important part was turning an ambiguous hardware-planning domain into a working decision-support system.

Earlier work includes engineering and architecture roles across fintech, telecom, public-sector systems, 3D visualization, power-industry analytics, IoT testing platforms, and large-scale web applications.

---

## Engineering Principles

### Determinism over magic

I prefer systems whose behavior can be inspected, replayed, and tested.

Opaque systems are sometimes useful, but production systems need constraints, traces, and failure modes humans can understand.

---

### Models before interfaces

A strong interface depends on a strong model.

I care deeply about internal representations: entity models, state models, graph structures, schemas, contracts, and data flow.

If the model is wrong, the UI eventually lies.

---

### Visualization as reasoning

Charts, graphs, diagrams, and spatial interfaces are not cosmetic.

They are tools for exposing hidden relationships.

Good visualization reduces cognitive load and makes complex systems governable.

---

### Security as architecture

Security is not a feature added at the end.

For serious systems, trust boundaries, audit chains, identity, storage behavior, and failure modes belong in the architecture from the beginning.

---

### Hardware changes software

Systems connected to real hardware have different rules.

Timing, latency, power, signal behavior, calibration, protocol quirks, and physical constraints matter.

Software that ignores the physical world eventually breaks against it.

---

## Technical Domains

- Systems architecture
- Data modeling
- Graph-based systems
- Deterministic inference
- Secure analytics
- Embedded systems
- RF tooling
- Reverse engineering
- Visualization systems
- Telemetry platforms
- Internal platforms
- AI-assisted development workflows

---

## Languages and Tools

Languages:

- Rust
- C
- Go
- TypeScript
- JavaScript
- Python
- C#
- PHP
- Kotlin

Systems and frameworks:

- React
- Node.js
- Express
- Prisma
- Three.js
- D3
- Canvas
- SVG
- ESP-IDF
- .NET / WPF
- Docker
- Kubernetes
- Azure
- AWS

Concepts:

- Graph modeling
- Retrieval systems
- Deterministic inference
- Cryptographic auditability
- mTLS
- Append-only storage
- Embedded control
- RF experimentation
- Protocol reconstruction
- Real-time telemetry
- Visualization-driven decision support

---

## What I Am Looking For

I am interested in Staff, Principal, or high-impact contract roles involving serious systems work.

Best-fit environments include:

- Internal platform engineering
- AI infrastructure and deterministic reasoning systems
- Secure analytics platforms
- Hardware-adjacent software
- Embedded or telemetry systems
- Developer productivity systems
- Graph/data modeling platforms
- Mission-critical decision-support tools

I am especially interested in roles where the problem is ambiguous, the stakes are real, and the system needs to become understandable before it can become reliable.

---

## Contact

- LinkedIn: https://www.linkedin.com/in/uiarchitect/
- Website: https://www.walshtechgroup.com
- GitHub: https://github.com/rpwalsh
- Email: reactarchitect@outlook.com
