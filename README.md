<div align="center">

  # Hi, I'm Sarvesh S 👋
  
  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=1000&color=00E676&center=true&vCenter=true&width=680&lines=Computer+Science+Student+%26+Beginner+Developer+🌱;Learning+Software+Development+by+Building+Projects+💻;Hackathon+Enthusiast+%26+Team+Player+👥;Exploring+React,+Next.js,+TypeScript+%26+Node.js+🚀;Tinkering,+Breaking+Things+%26+Learning+Through+Debugging+🛠️)](https://git.io/typing-svg)

  <p align="center">
    <strong>Undergraduate Computer Science Student • Hands-on Learner • Tech Tinkerer</strong>
  </p>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=SarveshS1407&style=flat-square&color=00E676&label=PROFILE+VIEWS" alt="Profile Views" />
    <a href="mailto:sarveshs1407@gmail.com"><img src="https://img.shields.io/badge/Email-sarveshs1407%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/SarveshS1407"><img src="https://img.shields.io/badge/GitHub-SarveshS1407-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  </p>

</div>

---

### 🌱 About Me & My Learning Journey

Hey there! Welcome to my GitHub. I'm an undergraduate Computer Science student passionate about building software and exploring web technologies. I consider myself an enthusiastic beginner who is eager to learn how real-world applications work from the ground up.

- 📖 **My Learning Style:** While video tutorials and documentation are great starting points, I learn 10x faster when I actually sit down, write code, run into walls, and figure out how to debug errors myself. Every project on my profile started with a question like *"How does Git actually track files?"* or *"How do interactive node graphs work?"*.
- 🤝 **Collaboration & Hackathons:** I love collaborating with friends and classmates. Teaming up for hackathons taught me how to coordinate tasks, use Git branching effectively, agree on API payloads with backend teammates, and build under real deadlines.
- 💡 **Current Focus:** Building solid foundations in core computer science, writing cleaner and more maintainable code, getting comfortable with TypeScript type checking, and exploring full-stack web applications.

---

### 🛠️ Projects I've Built While Learning

Here is a detailed look at the projects I've built or contributed to, the challenges I ran into, and what I learned along the way:

---

#### 👥 1. [CodeMap (ImpactLens AI)](https://github.com/Dhyanesh2603/Codemap) — *Collaborative Hackathon Project*
> **Tools Used:** `Next.js (App Router)` • `TypeScript` • `React Flow (@xyflow/react)` • `Tailwind CSS` • `WebSockets` • `Axios`

- **The Idea:** Built together with 3 friends during a hackathon to help developers visually navigate complex codebases and predict the impact of file changes before merging.
- **What I Worked On (Frontend Lead):**
  - Designed and built the entire Next.js frontend from scratch.
  - Learned how to use **React Flow** to render interactive, zoomable, and pannable architectural node graphs showing relationships between files and services.
  - Built dynamic change impact ripple animations so when a user selects a file, downstream affected services light up in red or green.
  - Created a slide-out Node Details Drawer to display file metrics, symbols, and dependencies, plus a dark-mode commit timeline dashboard.
- **Biggest Learning Curve:** Learning how to manage complex graph UI state, handling real-time WebSocket events without unnecessary component re-renders, and coordinating Git branches and API contracts with my 3 backend teammates.

---

#### ⚡ 2. [GitAssist](https://github.com/SarveshS1407/GitAssist) — *Codebase Archaeology & Explorer*
> **Tools Used:** `Node.js` • `JavaScript (ESNext)` • `REST API` • `Mermaid.js` • `Automated Testing` • `GitHub Actions CI`

- **Why I Built It:** I wanted to understand how Git works behind the scenes and see if I could build a completely offline, zero-cloud tool to inspect and audit codebases directly on my local machine.
- **What I Implemented:**
  - Built an ingestion scanner that walks directory trees and computes language statistics, line counts, and Git commit logs.
  - Explored basic AST and regex parsing to extract imported modules, detect circular dependencies, and render interactive topology diagrams using Mermaid.js syntax.
  - Added a change risk score heuristic based on commit frequency and file complexity.
  - Practiced writing my very first comprehensive automated test suite — wrote **47 unit and integration tests** using Node's test runner and configured GitHub Actions CI to run them automatically on every push.
- **Biggest Learning Curve:** Writing thorough tests to handle edge cases like broken symlinks or missing `.git` folders, and figuring out how to parse dependency imports reliably.

---

#### 🏙️ 3. [Project Tycoon v3.0](https://github.com/SarveshS1407/project-tycoon) — *Full-Stack Simulation Game*
> **Tools Used:** `React 19` • `Express.js 5` • `Tailwind CSS v4` • `Vite` • `Web Audio API` • `HeroUI`

- **Why I Built It:** I wanted to try building a full-stack project where frontend state and backend logic interact continuously through game mechanics. The game simulates managing a developer squad and balancing daily coding velocity against technical debt, team morale, and budget burn.
- **What I Implemented:**
  - Designed mathematical simulation formulas to calculate daily work output based on developer skill specialties and accumulated code debt penalties.
  - Built an Express.js 5 REST API server to handle user authentication sessions, save/load team rosters to persistent JSON storage, and track high scores.
  - Implemented a custom retro sound synthesizer using the browser's native **Web Audio API** (creating 8-bit arpeggios, click sounds, and warning chimes without heavy external audio libraries).
  - Built an interactive head-to-head PvP arena mode where the player's team competes against a simulated Rival AI CTO.
- **Biggest Learning Curve:** Managing complex React state across nested components and learning how audio oscillators work in the Web Audio API.

---

#### 🩸 4. [Veritas Mortis](https://github.com/SarveshS1407/veritas-mortis) — *Procedural Detective Mystery Engine*
> **Tools Used:** `Next.js 16` • `React 19` • `TypeScript` • `Tailwind CSS` • `Framer Motion` • `Zustand`

- **Why I Built It:** I wanted to challenge myself to write strict TypeScript and explore procedural generation algorithms. I've always loved mystery stories, so I built a 1970s neo-noir detective thriller game where every case is generated dynamically.
- **What I Implemented:**
  - Used a deterministic seeded PRNG algorithm (**Mulberry32**) so each mystery case has reproducible clues, suspects, autopsy reports, and alibis based on a seed number.
  - Built interactive investigation tools: a 365nm UV blacklight mode to reveal luminescent fingerprints, autopsy toxicology chromatography charts, and a deductive yarn-board matrix where players link evidence pins to suspects.
  - Created a 4-tier suspect composure breakdown system (Calm → Deflecting → Cornered → Broken) that tracks stress levels during interrogations.
  - Added smooth typewriter dialogue animations and atmosphere using Framer Motion.
- **Biggest Learning Curve:** Dealing with TypeScript interfaces for deeply nested game objects, getting comfortable with Next.js 16 App Router structures, and managing global game state with Zustand.

---

### 💻 Technologies I'm Learning & Tinkering With

> *I don't claim to be an expert in any of these — these are the tools and libraries I have actively built projects with and am continuing to practice every day:*

<div align="center">

#### Languages I Work With
![TypeScript](https://img.shields.io/badge/TypeScript-Practicing_%26_Learning-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+_Everyday-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-Basics_%26_Scripting-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-Semantic_Markup-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Flexbox_%26_Grid-1572B6?style=flat-square&logo=css3&logoColor=white)

#### Frontend & UI
![React](https://img.shields.io/badge/React-Components_%26_Hooks-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-App_Router_Basics-000000?style=flat-square&logo=next.js&logoColor=white)
![React Flow](https://img.shields.io/badge/React_Flow-Interactive_Node_Graphs-FF0072?style=flat-square&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Utility_Styling-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-UI_Transitions-0055FF?style=flat-square&logo=framer&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Fast_Bundler-646CFF?style=flat-square&logo=vite&logoColor=white)

#### Backend, State & Tooling
![Node.js](https://img.shields.io/badge/Node.js-Server_Runtimes-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-REST_API_Endpoints-000000?style=flat-square&logo=express&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-State_Management-443E38?style=flat-square&logo=react&logoColor=white)
![Git](https://img.shields.io/badge/Git-Branching_%26_Merging-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-Basic_CI_Pipelines-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Automated Testing](https://img.shields.io/badge/Automated_Testing-Unit_%26_Integration-C21325?style=flat-square&logo=jest&logoColor=white)

</div>

---

### 🎯 What I'm Focused on Learning Next

- 🧠 **Data Structures & Algorithms:** Practicing problem-solving patterns (arrays, strings, trees, dynamic programming) to build stronger computer science fundamentals.
- 🗄️ **Databases & Data Modeling:** Transitioning from JSON-file stores to real relational and NoSQL databases like PostgreSQL and MongoDB.
- 📐 **Clean Architecture & Design Patterns:** Learning how to write code that is clean, modular, and easy for other developers to read and extend.
- 🤝 **More Team Projects & Hackathons:** Eager to team up with others, learn from experienced programmers, and contribute to open-source software.

---

### 📊 GitHub Activity & Real-Time Stats

<div align="center">
  <img src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=SarveshS1407&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="Sarvesh's GitHub Stats" width="49%" />
  <img src="https://github-readme-stats-anuraghazra1.vercel.app/api/top-langs/?username=SarveshS1407&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="47%" />
</div>

<div align="center">
  <br>
  <img src="https://streak-stats.demolab.com/?user=SarveshS1407&theme=radical&hide_border=true" alt="GitHub Streak" width="97%" />
</div>

---

<div align="center">
  <sub>Thanks for stopping by! I'm always open to feedback, code reviews, advice from experienced developers, and building cool projects together.</sub>
</div>
