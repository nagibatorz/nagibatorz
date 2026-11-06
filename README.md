# Hi, I'm Zhorzh Zelenkov 👋

### Software Engineer · CS @ UW (B.S. 2024–2028, GPA 3.8)
### RL evals · Data / AI infra · Neuroscience tools · Privacy research

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zhorzh-zelenkov)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nagibatorz)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zzhorzh@cs.washington.edu)

---

### About

Junior at the University of Washington's Paul G. Allen School of Computer Science. I build systems that have to be correct under real load — deterministic evals for frontier models, production data pipelines for millions of sensor readings a day, and real-time control for neuroscience hardware.

Currently: Software Engineering Intern at a Stealth Startup and AI Engineer at Brooks Running, both 20 hrs/week in parallel.

- 🤖 **Stealth Startup — SWE Intern (Oct 2026–Present):** deterministic RL environments and long-horizon coding tasks for evaluating frontier AI agents. Emphasis on verifiability, exploit resistance, and calibrated difficulty. Delivered accepted environments across SWE, ML, optimization, and robotics — each with deterministic generation, exact oracle solvers, programmatic validation, and continuous reward functions. Built a multi-agent orchestration harness (spec → implementation → audit → review → red team) scaling environment production to 5–10 per week per person.
- 🏃 **Brooks Running — AI Engineer (Sep 2026–Present) / AI & Data Engineering Intern (Jun–Sep 2026):** own the production ELT pipeline — automated ingestion of millions of sensor readings daily from S3 into Snowflake, normalizing incompatible formats into a queryable schema (Airflow, dbt via Cosmos, PyArrow, Snowflake). Built a self-serve platform (React, AWS) so non-technical stakeholders can build, deploy, and host internal tools without engineering bottlenecks. Entra RBAC + Firebase for secure, permission-based access.
  - Scaled biomechanics collection from 10-second lab captures to hour-long field recordings across 2000+ runners worldwide.
  - Took over the iOS app after silent data loss in production — root-caused it, added self-healing recovery, lifted session delivery from 10% to 99% (Swift).
  - Replaced manual per-user provisioning (Cognito, TestFlight, backend) with a self-serve signup flow: 30 min engineering time per runner → 0.
  - Established the first structured test protocol with the Run Research team: 15+ previously unreported defects (Swift, XCTest).
- 🧠 **Steinmetz Lab — Software Development Engineer (Nov 2025–Aug 2026):** maintain Ephys Link, a Python Socket.IO server connecting trajectory-planning and brain-atlas tools to five electrophysiology manipulator platforms. Implemented jackhammer mode — real-time motor control via the Socket.IO API, with error handling and position tracking for closed-loop operation, sub-millisecond latency. Made builds reproducible with dependency locking, environment isolation, and static analysis in CI.
- 🔐 **UW Privacy & Security Lab — Research Assistant (Sep 2025–Aug 2026):** "What is a Cookie?" — Best Poster, UW BS/MS Showcase. Built an automated pipeline (Python, Selenium) that detects and interacts with websites, capturing browser cookie states across controlled consent flows on hundreds of sites, then normalizing and comparing cookie metadata to quantify where site behavior diverged from stated consent (Altair).
- 🧩 **Olleey.com — Software Engineer (Jul 2026–Present):** real-time context infrastructure for AI agents — backend for ingesting, processing, and serving contextual data to agent workflows with low-latency retrieval and incremental updates. Built end-to-end: backend services, storage, agent integrations, deployment.

---

### Technical depth — where I've actually used it

**Languages:** Java, Python, TypeScript/JavaScript, Swift, SQL, C/C++/C#, Go, Kotlin, Dart, OCaml, Ruby

**Data & infra:** Airflow, dbt (Cosmos), PyArrow, Snowflake, S3, Lambda, Cognito, PostgreSQL, MySQL, Docker, Linux, CI/CD — production ELT at Brooks, millions of rows/day, schema normalization across incompatible sensor formats.

**AI / RL evals:** deterministic environment generation, oracle solvers, programmatic validation, continuous rewards, exploit-resistant task design, multi-agent orchestration (spec / implement / audit / review / red team) — Stealth Startup.

**Systems / realtime:** Python Socket.IO servers, sub-ms motor control, closed-loop position tracking, five hardware platforms — Ephys Link / Steinmetz Lab.

**Web / mobile:** React, Next.js, Node.js, Spring Boot, Flutter, Swift/XCTest, Firebase, Entra RBAC — self-serve internal-tools platform, iOS biomechanics app, Grono, SENS.

**Coursework:** Data Structures & Algorithms, Machine Learning, Deep Learning, NLP, Operating Systems, Distributed Systems, Linear Algebra, Functional Programming, Programming Languages, OOP

**Practice:** [nagibatorz/DSA](https://github.com/nagibatorz/DSA) — 97+ LeetCode-style problems in Java, each with README + solution, focused on understanding why an algorithm works, not just getting it to pass.

---

### Open Source Contributions

**[VirtualBrainLab/Pinpoint](https://github.com/VirtualBrainLab/Pinpoint)** — neuroscience probe-planning tools
- Jackhammer Mode — real-time motor control via Socket.IO API
- External Tracking Pipeline — probe position tracking
- Code quality: modern C#, type safety

*This section is updated as new contributions land — see the pinned repos below for the latest.*

---

### Featured Projects

| Project | What it does, technically | Stack |
|---------|---------------------------|-------|
| **[Optivise.dev](https://optivise.dev)** | 1st Place Hackathon — AI-driven A/B testing platform with real-time analytics | React · AWS Lambda · TensorFlow |
| **VisualML** | ML visualization tool — 96% accuracy, 40% fewer false positives | Java · Spring Boot · React · Python |
| **Grono** | Reddit-style social platform with GPT moderation & Wilson-score ranking | Next.js · TypeScript · Sanity · OpenAI |
| **SENS** | Android digital wellness app — 200+ beta users, 3+ hrs saved daily | Kotlin · Jetpack Compose |

---

### GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=nagibatorz&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nagibatorz&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</div>

---

### Achievements

- Best Poster, UW BS/MS Showcase — "What is a Cookie?"
- Washington State Opportunity Scholar · Balanced Man Scholar · Kimura Scholar · Hearthstone Housing Foundation Scholar · Renthop Scholar · Bridge4Students Top Scholar · Tom Hicks Scholar
- 1st Place — UW Hackathon · MOVE Fellow — Handshake AI · VP — UW Swim Club

### Languages

English · Ukrainian · Russian (native) · Polish (learning)

---

> Building software that advances science, one commit at a time.
