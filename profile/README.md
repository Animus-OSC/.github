<p align="center">
  <img src="./assets/readme-hero.svg" width="100%" alt="Animus Open Source University — systems, research and world" />
</p>

# Animus OSC

**Open-source engineering for human-controlled systems, reproducible AI infrastructure, and secure connectivity.**

Animus is an engineering laboratory and open-source university. We build systems where authority, evidence, failure boundaries, and reproducibility are explicit enough to inspect and test.

**Public entry point:** `kapakka.org`  
**Public code:** [Animus DataLab Python SDK](https://github.com/Animus-OSC/animus-datalab-sdk)

## What is public today

### Animus DataLab SDK

A typed, zero-runtime-dependency Python SDK for governed ML and research workflows.

- dataset and immutable-version registration
- experiment/run lifecycle and project-scoped dispatch
- integrity-aware artifact streaming
- signed CI provenance
- bounded non-blocking telemetry
- predictable failure semantics
- Python 3.10-3.14, PEP 561 typing and Apache-2.0 licensing

Repository: [Animus-OSC/animus-datalab-sdk](https://github.com/Animus-OSC/animus-datalab-sdk)

### Animus DataLab

Governed ML infrastructure built around explicit **Control Plane / Data Plane** separation, reproducible execution, lineage, audit, bounded artifact handling, and security-sensitive deployment boundaries.

The current public GitHub code surface is the SDK above. Server-side implementation remains private while interfaces and release boundaries are graduated deliberately.

### Animus Link

Secure-connectivity and managed-access engineering around explicit authority, encrypted transport, lifecycle reconciliation, runtime evidence, and failure visibility.

Public product/research context is published through the Animus/Kapakka web surface. Protocol research and product runtime are kept distinct: pre-release research is not presented as a production protocol release.

## Research directions

### AOS / Personal Cell

A local-first personal-computing direction in which models, devices, and external services are replaceable capabilities beneath a persistent user-controlled layer. Research focuses on encrypted continuity, minimum-sufficient disclosure, explicit capabilities, and useful offline operation.

### University & Adventure

Animus University connects primary sources, explanations, notebooks, simulations, engineering work, and spatial/interactive learning. Adventure is one representation inside that system, not the definition of the engineering program.

### Engineering systems

Private R&D explores document-governed delivery, bounded autonomous software engineering, capability-scoped computation, reproducible media production, and evidence-gated release workflows. Private repositories stay private until their publication boundary is intentional and reviewable.

## Engineering contract

**Evidence before claims.** Implemented behavior, release candidates, research hypotheses, and target architecture are labeled separately.

**User authority over model authority.** AI can propose, explain, and create; it does not become identity, policy, or permission by itself.

**Explicit state ownership.** Control planes own authoritative state; execution environments report runtime evidence.

**Partial failure remains visible.** Degraded states should be diagnosable and reconcilable rather than silently collapsed into success/failure booleans.

**Open by graduation, not by optics.** Public work should be safe to publish, understandable, reproducible, and useful to others.

**Release evidence is revision-specific.** Tests, provenance, rollback, compatibility, and operational documentation belong to the product surface.

## Repository status model

We use these labels conceptually across public communication:

- **Public / released** — source and interfaces are intentionally published.
- **Public snapshot** — useful evidence, but not necessarily the canonical active development repository.
- **Private active development** — implementation is not a public dependency.
- **Research / pre-release** — architecture and experiments may change; no production-readiness claim is implied.
- **Target architecture** — a design direction, not an assertion of deployed behavior.

## Contributing and security

Public repositories carry repository-local contribution, release, compatibility, and security documentation. Read those boundaries before changing contracts or depending on implementation details.

Security-sensitive issues should follow the reporting path documented in the relevant repository rather than being disclosed in a public issue first.

## Public surfaces

- `kapakka.org` — public Animus entry point
- [Animus DataLab Python SDK](https://github.com/Animus-OSC/animus-datalab-sdk) — current public code surface
- [Maksim Sotnikov / grewanderer](https://github.com/grewanderer) — lead engineering profile and public systems evidence

---

<sub>ANIMUS · human-controlled systems · explicit authority · reproducible evidence · open by graduation</sub>
