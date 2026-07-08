<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=36&duration=4000&pause=2000&color=A78BFA&center=true&vCenter=true&width=650&height=80&lines=Hey%2C+I'm+Matheus+Garcez" alt="Matheus Garcez" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Java+Backend+Developer;Building+REST+APIs+with+Spring+Boot;Neural+Networks+%2B+Genetic+Algorithms+%2B+Compilers;Open+to+Java+Backend+Opportunities" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Location-Uberl%C3%A2ndia%2C%20Brazil-4C1D95?style=flat-square&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/Open%20To-Java%20Backend%20Jr-8B5CF6?style=flat-square&logo=coffeescript&logoColor=white"/>
<img src="https://img.shields.io/badge/English-Advanced-6D28D9?style=flat-square&logo=googletranslate&logoColor=white"/>

<br/><br/>

<a href="https://linkedin.com/in/matheus-garcez-172377249"><img src="https://img.shields.io/badge/LinkedIn-Connect-6366F1?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:matheus.garcez09@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/cherohn/job-matcher"><img src="https://img.shields.io/badge/Job%20Matcher-Try%20it-7C3AED?style=for-the-badge&logo=python&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=cherohn&style=flat-square&color=8b5cf6&label=Profile+Views"/>
<img src="https://img.shields.io/github/followers/cherohn?style=flat-square&color=7c3aed&label=Followers&logo=github"/>

</div>

<br/>

---

## About Me

```yaml
name: Matheus Garcez
role: Java Backend Developer
location: Uberlandia, MG, Brazil
focus: REST APIs · Backend Systems · Applied Machine Learning
philosophy: "Understand what's happening under the hood, not just the API surface."
```

I got into programming because I wanted to understand how things work — not just use them.

That curiosity led me to build a compiler from scratch (every grammar rule and semantic check written by hand with JFlex and CUP), implement neural networks without touching a single ML library, and evolve AI agents that learn to play games purely through survival pressure.

Along the way I picked up Java, Spring Boot, PostgreSQL, and the habit of not stopping until I understand what's happening under the hood.

Today I build REST APIs and backend systems, and I'm working on an AI-powered platform for IT professionals — which means I also deal with architecture decisions, database modeling, and shipping things that actually have to work.

**Open to Java backend opportunities — CLT or PJ, any work model.**

<br/>

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=java,py,js,ts&theme=dark"/>

**Backend & Data**

<img src="https://skillicons.dev/icons?i=spring,hibernate,postgres,redis,mysql&theme=dark"/>

**Tooling & DevOps**

<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,postman,linux,maven&theme=dark"/>

</div>

<br/>

---

## Featured Projects

<details>
<summary><b>🟣 E-commerce API — Spring Boot 3 · PostgreSQL · Redis · Docker · GitHub Actions</b></summary>
<br/>

Production-style e-commerce backend focused on data integrity under concurrency and financial correctness.

| | |
|---|---|
| **Concurrency** | Optimistic Locking on stock updates — conflicts resolved with 409 Conflict |
| **Consistency** | Transactional order creation: if item 3 of 5 fails, stock from items 1 and 2 rolls back automatically |
| **State machine** | Order transitions modeled as a single Map — no if/else scattered across services |
| **Cache** | Redis on aggregated reports only — never on stock, which changes on every sale |
| **Financial math** | BigDecimal for all monetary values — Float/Double rounding errors are unacceptable in money |
| **CI/CD** | GitHub Actions running build and tests on every push |
| **Repository** | [github.com/cherohn/ecommerce-api](https://github.com/cherohn/ecommerce-api) |

</details>

<details>
<summary><b>🟣 Task Manager API — Spring Boot 3 · JWT · PostgreSQL · Docker</b></summary>
<br/>

REST API focused on getting authentication and authorization right.

| | |
|---|---|
| **Auth** | Stateless JWT — no server-side session, scales horizontally without sticky sessions |
| **IDs** | UUID instead of sequential Long — prevents data volume exposure and enumeration attacks |
| **Security** | BCrypt with automatic salt per record — rainbow table attacks unviable by design |
| **Access control** | Role-based (USER/ADMIN) — users manage their own tasks, admin sees all |
| **Tests** | JUnit 5 + Mockito covering critical business rules |
| **Docs** | Swagger UI + ready-to-use Postman collection |
| **Repository** | [github.com/cherohn/task-manager](https://github.com/cherohn/task-manager) |

</details>

<details>
<summary><b>🟣 AI Game Agents — Pong · Flappy Bird · Dino</b></summary>
<br/>

Three projects, three different ML paradigms — built deliberately to understand why you'd choose one over another.

| Project | Approach | What it taught me |
|---|---|---|
| [Pong AI](https://github.com/cherohn/Pong-IA) | Feedforward NN + backpropagation | How gradient-based learning adjusts weights from real-time error signals |
| [Flappy Bird AI](https://github.com/cherohn/FlappyBirdIA) | Genetic algorithm | How populations evolve with no error signal — only survival |
| [Dino AI](https://github.com/cherohn/Dino-IA-Java) | Neuroevolution | How competing agents in parallel converge faster than sequential generations |

All three implemented in pure Java, zero ML libraries.

</details>

<details>
<summary><b>🟣 Compiler Pipeline — Java · JFlex · CUP</b></summary>
<br/>

Full compiler front-end built from first principles.

| | |
|---|---|
| **Lexical analysis** | JFlex — tokenization via DFA-backed scanner |
| **Syntactic analysis** | CUP — LALR(1) parser generated from a context-free grammar |
| **Semantic analysis** | Custom Java logic — type checking and scope validation |
| **Goal** | Understand what happens between source code and execution |
| **Repository** | [github.com/cherohn/compiler-pipeline-java](https://github.com/cherohn/compiler-pipeline-java) |

</details>

<details>
<summary><b>🟣 Job Matcher — Python · Groq AI · Serper · Gmail</b></summary>
<br/>

Desktop tool that automates job searching and scores resume fit using AI.

| | |
|---|---|
| **Function** | Searches Google for jobs, scores fit between each posting and your resume via Groq AI, emails top matches automatically |
| **Design** | Uses your own API keys — no subscription, no middleman |
| **Security** | Credentials protected with Windows DPAPI |
| **Distribution** | Packaged as a standalone Windows executable (PyInstaller) |
| **Repository** | [github.com/cherohn/job-matcher](https://github.com/cherohn/job-matcher) |

Built because manually reading dozens of job postings to find out one wants Angular when you're backend is a terrible use of time.

</details>

<details>
<summary><b>🟣 Other Projects</b></summary>
<br/>

| Project | Stack | Description |
|---|---|---|
| [Spring Boot REST API](https://github.com/cherohn/Spring-Basic-REST-API) | Spring Boot · JPA · OpenAPI | Clean layered architecture reference implementation |
| [Appointment System](https://github.com/cherohn/AppointmentSystem-Java-JDBC) | Java Swing · JDBC · MySQL | Student enrollment CRUD desktop app |
| [Asteroids](https://github.com/cherohn/Asteroids-Java) | Java · JavaFX | Arcade game with real-time collision detection |
| [Snake](https://github.com/cherohn/Cobrinha-Java) | Java Swing | Snake with threaded game loop and Semaphore sync |
| [Finance App](https://github.com/cherohn/Finance-App) | Spring Boot · JPA · PostgreSQL | User profile API foundation for a finance backend |

</details>

<br/>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=cherohn&theme=redical&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=ffffff&hide_border=true" width="100%"/>

</div>

<br/>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/cherohn/cherohn/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

<br/>

---

## Current Focus

```yaml
building:
  - REST APIs with Spring Boot 3 (JWT, Redis, Docker, CI/CD)
  - AI-powered platform for IT professionals

exploring:
  - Messaging with Kafka and RabbitMQ
  - Spring Batch for batch processing
  - AWS fundamentals

open_to:
  - Java Backend Developer roles (Junior — CLT or PJ, any work model)
```

<br/>

---

<div align="center">

"Understand what's happening under the hood, not just the API surface."

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=A78BFA&amp;height=120&amp;section=footer" width="100%"/>

</div>
