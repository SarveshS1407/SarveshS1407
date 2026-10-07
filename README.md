<p align="center">
  <img src="assets/masthead.svg" alt="Sarvesh S - Engineering Journal" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sarveshs007/"><code>LinkedIn</code></a> &nbsp;•&nbsp;
  <a href="mailto:sarveshs1407@gmail.com"><code>Email</code></a> &nbsp;•&nbsp;
  <a href="https://github.com/SarveshS1407"><code>Repositories</code></a> &nbsp;•&nbsp;
  <a href="#featured-case-studies"><code>Case Studies</code></a> &nbsp;•&nbsp;
  <a href="#engineering-log"><code>Log</code></a>
</p>

---

### 📖 The Philosophy

> *"I learn 10x faster by building tools, breaking edge cases, and understanding what happens under the hood than by passively consuming tutorials."*

I am an undergraduate Computer Science student focused on software engineering, developer tools, and interactive web systems. This profile is an open **engineering journal** documenting what I build, how I approach architecture, and what I learn through hands-on technical experiments and hackathons.

---

### ⏱️ Engineering Log

A chronological record of milestones, systems built, and core topics explored:

```
2026 ──┬── [Dependency Graphs] ─ Built GitAssist: AST module extraction & circular import detection pass
       ├── [PRNG Engine] ────── Developed Veritas Mortis: Seeded Mulberry32 procedural case generator
       └── [CI & Testing] ───── Authored 40+ unit/integration tests with GitHub Actions automated CI

2025 ──┬── [Full-Stack Apps] ── Transitioned from toy scripts to multi-tier Next.js & Express architectures
       ├── [Web Audio API] ──── Engineered zero-asset 8-bit sound synthesizers using native browser oscillators
       └── [Team Hackathons] ── Led frontend architecture for CodeMap (React Flow node graphs & WebSockets)
```

---

<h3 id="featured-case-studies">🛠️ Featured Case Studies</h3>

#### 01. [GitAssist](https://github.com/SarveshS1407/GitAssist) &nbsp; `CLI Tool` `Code Analysis` `CI/CD`
> **An offline, privacy-first codebase archaeology tool and dependency visualizer.**

* **The Problem:** Developers joining an unfamiliar codebase struggle to navigate complex file interactions, often inadvertently introducing circular dependencies or breaking unseen downstream modules.
* **Engineering Decisions:**
  * Traverses local directory trees to extract module imports using AST patterns—100% offline with zero cloud telemetry.
  * Implements an algorithmic cycle detection pass to flag circular imports and renders architecture diagrams with Mermaid.js.
  * Computes commit change risk heuristics by cross-referencing Git commit frequency against file complexity.
  * Backed by **47 automated unit & integration tests** running on GitHub Actions CI.
* **Key Learnings:** AST parsing edge cases, file system traversal across symlinks, and test-driven design.

<br />

#### 02. [Veritas Mortis](https://github.com/SarveshS1407/veritas-mortis) &nbsp; `Web Game Engine` `Procedural Generation` `TypeScript`
> **A procedural 1970s neo-noir detective mystery engine built with deterministic state.**

* **The Problem:** Dynamic procedural mystery games often produce contradictory clues, broken evidence timelines, and inconsistent narrative states.
* **Engineering Decisions:**
  * Implemented a deterministic **Mulberry32 PRNG algorithm** to guarantee reproducible crime cases, alibis, and toxicology reports from a single integer seed.
  * Created dynamic forensic investigation tools including a 365nm UV blacklight inspection mode and an interactive deduction matrix.
  * Modeled a 4-tier suspect stress matrix (`Calm → Deflecting → Cornered → Broken`) to govern dialogue trees dynamically.
  * Enforced strict TypeScript domain models and decoupled game loops from UI rendering using Zustand.
* **Key Learnings:** State immutability, mathematical pseudorandom reproducibility, and complex UI performance.

<br />

#### 03. [CodeMap (ImpactLens AI)](https://github.com/Dhyanesh2603/Codemap) &nbsp; `Hackathon Project` `Graph Visualization` `WebSockets`
> **An architectural service dependency visualizer and change-impact prediction platform.**

* **The Problem:** Service dependencies and modular relationships are hard to conceptualize through file lists alone, obscuring the blast radius of pull requests.
* **Engineering Decisions:**
  * Led frontend development during a 24-hour hackathon, rendering interactive, zoomable node graphs with React Flow.
  * Programmed animated ripple paths that light up downstream services when a file is modified to visualize merge risks.
  * Connected real-time WebSocket feeds to synchronize graph states across multi-client inspection sessions.
* **Key Learnings:** Hackathon sprint coordination, canvas coordinate math, and strict API schema contracts with backend peers.

<br />

#### 04. [Project Tycoon v3.0](https://github.com/SarveshS1407/project-tycoon) &nbsp; `Full-Stack` `Simulation` `Web Audio API`
> **An engineering squad management game balancing feature velocity against technical debt.**

* **The Problem:** Concepts like tech debt and team velocity are abstract to students until experienced through a quantifiable simulation loop.
* **Engineering Decisions:**
  * Formulated mathematical simulation algorithms calculating daily output based on engineer skills and compounding code debt penalties.
  * Programmed a retro 8-bit sound synthesizer from scratch using native **Web Audio API** oscillators—zero external audio files required.
  * Built an Express.js 5 REST backend managing player authentication, saved game rosters, and competitive Rival AI CTO rounds.
* **Key Learnings:** Low-level browser audio synthesis, mathematical balance curves, and full-stack session handling.

---

### 🧰 Technical Arsenal

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Languages</b><br /><br />
      • TypeScript<br />
      • JavaScript (ES6+)<br />
      • Python<br />
      • C / C++<br />
      • HTML5 / CSS3
    </td>
    <td width="33%" valign="top">
      <b>Frontend & UI</b><br /><br />
      • React 19<br />
      • Next.js (App Router)<br />
      • Tailwind CSS<br />
      • React Flow (@xyflow)<br />
      • Zustand & Framer Motion
    </td>
    <td width="33%" valign="top">
      <b>Backend & DevOps</b><br /><br />
      • Node.js & Express.js 5<br />
      • REST APIs & WebSockets<br />
      • Git Branching & Merging<br />
      • GitHub Actions CI/CD<br />
      • Web Audio API
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,nodejs,express,git,github,actions,python,html,css" />
  </a>
</p>

---

### 🔬 Currently Exploring

* **Compilers & ASTs:** Writing syntax tokenizers and exploring how tree structures optimize execution.
* **Distributed Systems:** Consensus algorithms, data partitioning, and fault tolerance patterns.
* **Database Internals:** Storage engines, indexing structures (B-Trees vs LSM), and query optimization.
* **Open Source Stewardship:** Following RFC discussions and code review workflows in major OSS ecosystems.

---

### 📈 Activity & Stats

<div align="center">
  <img src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=SarveshS1407&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true" width="48%" />
  <img src="https://github-readme-stats-anuraghazra1.vercel.app/api/top-langs/?username=SarveshS1407&layout=compact&theme=github_dark&hide_border=true" width="48%" />
</div>

---

<p align="center">
  <sub>Documented by <b>Sarvesh S</b> • Open to engineering discussions, internships, and collaborative builds.</sub><br />
  <sub><a href="mailto:sarveshs1407@gmail.com">sarveshs1407@gmail.com</a> • <a href="https://www.linkedin.com/in/sarveshs007/">LinkedIn</a></sub>
</p>
