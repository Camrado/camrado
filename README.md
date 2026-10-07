# Hi, I'm Kamal Yalchin 👋

Software engineer working on aviation software, and final-year Computer Science student at the French-Azerbaijani University (dual degree with the University of Strasbourg).

- 🛫 **Software Engineer at R.I.S.K. Company**, Air Navigation Department. Co-architecting the migration of a 30-year-old WPF application (20+ aeronautical modules) to an ASP.NET Core modular monolith, and building flight procedure design and validation tools
- ⚡ Built an automated dataset auditing pipeline at work that cut manual verification from **5+ hours to under 5 minutes**
- 🚀 **Co-founder & CTO of [Progresium](https://progresium.com)**, a focus-first task manager whose "Lock In" mode blocks distracting apps and sites across synced devices
- 🎓 **Ranked 1st of 168** university-wide at UFAZ, Presidential Scholar of Azerbaijan
- 🔭 Currently going deeper into OS internals, concurrency, parallel programming and distributed systems
- 🏆 ICPC 2025 Azerbaijan Regional Contest (High Achievement Award), 3x national hackathon finalist

---

## 🛠️ Tech stack

**Languages:** C#, C/C++, Python, TypeScript, JavaScript, SQL  
**Backend:** ASP.NET Core, EF Core, Clean Architecture, CQRS (MediatR), modular monolith, Hangfire, RabbitMQ, Node.js, Express.js  
**Security:** JWT, OAuth 2.0 / OpenID Connect, role- and policy-based authorization  
**Data:** PostgreSQL, MongoDB  
**Cloud & DevOps:** Microsoft Azure, Azure CI/CD, Docker, Kubernetes, Linux, Git  
**Frontend:** Angular, Vue 3

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="40" alt="C#"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" width="40" alt=".NET"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40" alt="C"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" alt="C++"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" alt="Python"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" alt="TypeScript"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" alt="PostgreSQL"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg" width="40" alt="RabbitMQ"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" alt="Docker"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" width="40" alt="Kubernetes"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azure/azure-original.svg" width="40" alt="Azure"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" alt="Linux"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg" width="40" alt="Angular"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" width="40" alt="Vue"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" alt="Git"/>
</p>

---

## 📌 Products I've built

### Progresium · [progresium.com](https://progresium.com)

Focus-first productivity SaaS. I architected and built the backend.

- [ProgresiumToDo](https://github.com/Camrado/ProgresiumToDo): .NET 10 Clean Architecture API with CQRS (MediatR), PostgreSQL + EF Core, JWT and Google OAuth, subscriptions/billing, Hangfire background jobs and Scalar API docs

### SkipSmart

Attendance tracking PWA for UFAZ students, taken from idea to production by me. Reached **200+ active users**, over 30% of the student body.

- [skipsmart-backend-core](https://github.com/Camrado/skipsmart-backend-core): core API on .NET 10 + PostgreSQL, built to handle bursts of concurrent check-ins at lecture start
- [skipsmart-frontend](https://github.com/Camrado/skipsmart-frontend): mobile-first Vue 3 PWA that stays responsive during peak check-in minutes
- [skipsmart-backend-timetable](https://github.com/Camrado/skipsmart-backend-timetable): Python (Flask) service that pulls the university timetable from Edupage for schedule-aware attendance logic

### IELTS Telegram Bot

Telegram bot for IELTS preparation that turns vocabulary practice into a daily habit.

- [ielts-telegram-bot](https://github.com/Camrado/ielts-telegram-bot): AI-generated vocabulary flashcards with spaced repetition, bulk word import and interactive grammar quizzes, built with Python, PostgreSQL (asyncpg) and the OpenAI API

---

## ⚙️ Systems & low-level

| Project | What it is | Stack |
|---|---|---|
| [minima-vm](https://github.com/Camrado/minima-vm) | 16-bit register virtual machine from scratch: memory, registers, stack, instruction set, two-pass assembler, disassembler, trace/step execution | C |
| [build-your-own-shell](https://github.com/Camrado/build-your-own-shell) | POSIX-compliant shell with builtins, external programs, I/O redirection, pipelines and quoting (CodeCrafters challenge) | C# |
| [mini-scheduler](https://github.com/Camrado/mini-scheduler) | CPU scheduler simulator: capacity-bounded priority scheduling with preemption, min/max heaps, deterministic tie-breaking, full timeline logging | C |
| [cpp-chess-engine](https://github.com/Camrado/cpp-chess-engine) | Terminal chess engine with full rules enforcement on a polymorphic piece hierarchy, no type-branching | C++17 |

## 🤖 AI & hackathon projects

| Project | What it is | Stack |
|---|---|---|
| [amcham-access-bank-chatbot](https://github.com/Camrado/amcham-access-bank-chatbot) | Multilingual RAG support agent with sentiment-aware escalation, anomaly detection and an admin dashboard, built in 5 hours at the AmCham x AccessBank hackathon | Python, FastAPI, OpenAI |
| [methane-guard](https://github.com/Camrado/methane-guard) · [frontend](https://github.com/Camrado/methane-guard-frontend) | Methane leak monitoring over Azerbaijan: hyperspectral satellite detection plus a live map dashboard for inspection dispatch and severity analytics | PyTorch, Spring Boot, JavaScript, Leaflet |
| [pd-handwriting-detection](https://github.com/Camrado/pd-handwriting-detection) | Parkinson's detection from digitizer handwriting: EfficientNetB3 features, leakage-safe feature selection, two-stage ensemble. 77.8% accuracy, AUC 0.80 (10-fold CV, 72 subjects) | TensorFlow, scikit-learn |
## 🧰 Small tools

- [promptmap](https://github.com/Camrado/promptmap): Chrome extension that turns long AI conversations into navigable documents
- [yt-shorts-blocker](https://github.com/Camrado/yt-shorts-blocker): Android app that blocks YouTube Shorts without blocking YouTube (Kotlin)

---

## 📊 GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Camrado&show_icons=true&include_all_commits=true&rank_icon=github&theme=radical" alt="GitHub stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Camrado&layout=donut&langs_count=8&theme=radical" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Camrado&theme=radical" alt="GitHub streak" />
</p>

---

## 🤝 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kamal-yalchin/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kamal.yalchin@gmail.com)
