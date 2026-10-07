<p align="center">
  <img src="assets/monogram.svg" alt="Monogram" width="48" height="48" />
</p>

# Sarvesh S.

Computer Science Engineering student focused on building dependable software and understanding core systems from first principles.

This repository serves as an open engineering journal—documenting projects built, design decisions made, and technical topics explored.

```text
Focus:     Full-Stack Development · Systems Tooling · Architecture
Location:  India (UTC +05:30)
Links:     linkedin.com/in/sarveshs007 · sarveshs1407@gmail.com
```

<img src="assets/rule.svg" alt="Separator" width="100%" />

## Engineering Log

An ongoing record of technical growth, architectural explorations, and software built.

### 2026
* **Dependency & Change Impact Modeling** — Investigated Directed Acyclic Graph (DAG) structures to predict downstream regression risks during Git merges; built interactive visualizers for module trees.
* **Procedural Engine Architecture** — Explored pseudo-random number generator (PRNG) state cycles and decoupled component lifecycles using strict TypeScript typing.
* **Testing & Continuous Integration** — Implemented comprehensive automated test runners (40+ unit and integration tests) and configured GitHub Actions CI pipelines for zero-cloud local tools.

### 2025
* **Audio Synthesis on the Web** — Experimented with the browser native Web Audio API; synthesized sound waves and procedural audio effects without external binary assets.
* **Full-Stack Application Design** — Transitioned from toy scripts to multi-tier web services, designing clean REST endpoints and client-side reactive state management.
* **Hackathon Engineering** — Competed in collaborative sprints; practiced interface contract negotiation, branch-based team workflows, and building under hard deadlines.

<img src="assets/rule.svg" alt="Separator" width="100%" />

## Featured Work

Selected technical case studies highlighting problem definitions, engineering decisions, and architectural tradeoffs.

---

### Case 01: [GitAssist](https://github.com/SarveshS1407/GitAssist)
> *An offline, privacy-first codebase archaeology tool and module dependency analyzer.*

* **Problem:** Developers joining an unfamiliar or legacy repository often struggle to understand structural dependencies and frequently introduce circular imports or break unmapped downstream services.
* **Engineering:**
  * Designed an AST and pattern scanner that traverses local directory trees to extract module imports without transmitting source code over the network.
  * Implemented an algorithmic cycle detection pass to flag circular dependencies before code execution.
  * Computed change risk heuristics by cross-referencing commit churn rates against file complexity.
  * Authored a 47-test suite using Node's native test runner to guarantee deterministic execution across edge cases.
* **Impact & Learnings:** Learned how to traverse AST nodes, handle file system edge cases (symlinks, permission barriers), and enforce regression protection through GitHub Actions.

---

### Case 02: [Veritas Mortis](https://github.com/SarveshS1407/veritas-mortis)
> *A procedural 1970s neo-noir detective thriller game engine built with seeded deterministic state.*

* **Problem:** Dynamic narrative engines frequently suffer from state inconsistency, where randomly generated clues, alibis, and timelines contradict each other.
* **Engineering:**
  * Utilized the **Mulberry32 PRNG** algorithm to build a deterministic generation pipeline, guaranteeing reproducible investigative cases given an identical integer seed.
  * Modeled a 4-tier suspect stress matrix (`Calm → Deflecting → Cornered → Broken`) to govern dialogue trees dynamically.
  * Enforced strict domain contracts in TypeScript across deeply nested case objects and decoupled UI rendering from game state via Zustand.
* **Impact & Learnings:** Deepened appreciation for state immutability, mathematical pseudo-random determinism, and building complex interactive workflows without memory leaks.

---

### Case 03: [CodeMap (ImpactLens AI)](https://github.com/Dhyanesh2603/Codemap)
> *An architectural dependency visualizer and change-impact prediction platform.*

* **Problem:** Microservice relationships and modular imports are difficult to conceptualize through file trees alone, obscuring the ripple impact of pull requests.
* **Engineering:**
  * Led frontend development for a collaborative hackathon project, implementing interactive node graphs using React Flow.
  * Programmed animated dependency highlight paths that dynamically illustrate which downstream services are impacted when a selected file is altered.
  * Integrated real-time WebSockets to synchronize graph inspection across multi-client review sessions.
* **Impact & Learnings:** Practiced rapid interface design under strict 24-hour hackathon constraints, mastered canvas viewport transformation mathematics, and established clear API schema contracts with backend peers.

---

### Case 04: [Project Tycoon v3.0](https://github.com/SarveshS1407/project-tycoon)
> *A full-stack software development simulation game modeling technical debt and team dynamics.*

* **Problem:** Abstract concepts like technical debt, burnout, and feature velocity are difficult for students to conceptualize without quantitative systems modeling.
* **Engineering:**
  * Designed mathematical simulation curves calculating daily squad output based on developer skill distribution, morale decay, and compounding debt penalties.
  * Programmed an 8-bit sound synthesizer from scratch using the browser's native **Web Audio API** oscillators and gain nodes—eliminating external audio asset bloat.
  * Developed an Express.js 5 backend REST service managing player sessions, game saves, and competitive AI rounds.
* **Impact & Learnings:** Learned the mechanics of low-level browser audio synthesis, state reconciliation in simulation loops, and clean RESTful session persistence.

<img src="assets/rule.svg" alt="Separator" width="100%" />

## Technical Toolkit

A focused overview of languages, frameworks, and foundational tools used across active codebases.

* **Languages:** TypeScript · JavaScript (ES6+) · Python · C/C++ · HTML5 / CSS3
* **Frontend & UI:** React 19 · Next.js (App Router) · Tailwind CSS · React Flow · Zustand · Framer Motion
* **Backend & Systems:** Node.js · Express.js 5 · RESTful APIs · WebSockets · Web Audio API
* **Engineering Practices:** Git (Branching & Workflows) · GitHub Actions (CI/CD) · Automated Unit & Integration Testing · Markdown / Mermaid.js

<img src="assets/rule.svg" alt="Separator" width="100%" />

## Currently Exploring

Topics and engineering domains currently under study:

* → **Compilers & ASTs:** Writing parsers and understanding how programming languages tokenize and execute instructions.
* → **Distributed Systems Fundamentals:** Consensus mechanisms, replication strategies, and failure modes in multi-node architectures.
* → **Relational Database Internals:** Index structures (B-Trees), query planning, and transactional ACID guarantees beyond file-based stores.
* → **Open-Source Contribution:** Studying well-maintained repositories to understand idiomatic conventions, RFC processes, and collaborative stewardship.

<img src="assets/rule.svg" alt="Separator" width="100%" />

## Notes & Colophon

This journal reflects honest, iterative engineering work. Projects represent concrete problem explorations rather than polished commercial offerings. 

* **Correspondence:** [sarveshs1407@gmail.com](mailto:sarveshs1407@gmail.com)
* **Professional Profile:** [linkedin.com/in/sarveshs007](https://www.linkedin.com/in/sarveshs007/)
* **Source Code:** [github.com/SarveshS1407](https://github.com/SarveshS1407)

<sub>Document set in system default typography. Updated October 2026.</sub>
