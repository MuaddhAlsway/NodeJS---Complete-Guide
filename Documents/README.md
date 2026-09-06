<div align="center">

<img src="./assets/tech-stack.svg" alt="Node.js Complete Guide technology stack" width="100%" />

# Node.js — The Complete Guide

### Backend Engineer Learning Lab and Technical Documentation

From Node.js fundamentals to secure, tested, real-time, production-ready backend systems.

[![Node.js](https://img.shields.io/badge/Node.js-Backend_Runtime-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-Web_Framework-111827?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Turso](https://img.shields.io/badge/Turso-libSQL-4FF8D2?style=for-the-badge&logo=turso&logoColor=111827)](https://turso.tech/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Language-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827)](https://developer.mozilla.org/docs/Web/JavaScript)

</div>

---

## About This Repository

This repository is my complete learning and documentation system for **Node.js — The Complete Guide** by **Maximilian Schwarzmüller / Academind**.

It is not only a collection of copied course notes. Every lesson is converted into structured technical documentation containing:

- Learning objectives
- Concept explanations
- Internal runtime behavior
- Code walkthroughs
- Architecture and data flow
- Security and performance analysis
- Common mistakes and debugging notes
- Practical exercises and mini-projects
- Active-recall questions
- Memorization guides
- Senior developer takeaways
- Mastery evidence

The goal is to move through this engineering cycle:

```text
Learn → Understand → Explain → Build → Debug → Document → Review → Master
```

## Course Information

| Field | Information |
|---|---|
| Course | Node.js — The Complete Guide |
| Instructor | Maximilian Schwarzmüller / Academind |
| Platform | Udemy |
| Level | Beginner to Advanced |
| Main application | Complete Online Shop |
| API project | Blog REST and GraphQL API |
| Learning method | Project-based engineering and documentation |
| Database adaptation | SQL lessons can also be implemented with Turso/libSQL |
| Repository purpose | Learning notes, implementation evidence, architecture, and mastery |

## Learning Outcomes

By completing this repository, I aim to be able to:

1. Explain the Node.js runtime and event loop.
2. Build HTTP servers with Node.js and Express.
3. Design modular routes, controllers, services, and data-access layers.
4. Render dynamic server-side pages.
5. Model and persist data using SQL and NoSQL databases.
6. Implement secure authentication and authorization.
7. Validate requests and handle operational errors safely.
8. Process file uploads and payments.
9. Design REST and GraphQL APIs.
10. Build real-time features with WebSockets.
11. Test, deploy, observe, and maintain backend applications.
12. Defend architecture decisions using security, performance, reliability, and maintainability constraints.

## Technology Stack

<div align="center">

<img src="./assets/tech-stack.svg" alt="JavaScript, Node.js, Express, EJS, Turso, SQL, MongoDB, GraphQL, WebSockets, Stripe and testing" width="900" />

</div>

| Area | Technologies and concepts |
|---|---|
| Runtime | Node.js, V8, event loop, asynchronous I/O |
| Language | JavaScript, modern ECMAScript, async/await |
| Web framework | Express.js, middleware, routing |
| Rendering | EJS, dynamic HTML, MVC |
| SQL data | SQL, Sequelize concepts, Turso/libSQL adaptation |
| NoSQL data | MongoDB, Mongoose |
| API engineering | REST, GraphQL, HTTP status codes, API contracts |
| Real-time systems | WebSockets, Socket.IO concepts |
| Authentication | Sessions, cookies, password hashing, authorization |
| Payments | Stripe checkout and payment workflows |
| Quality | Validation, testing, error handling, debugging |
| Production | Deployment, environment variables, security, performance |

## Documentation Architecture

Every lesson or chapter has one primary Markdown document. Optional supporting documents can be added when a topic becomes large:

| Document | Purpose |
|---|---|
| `lesson-name.md` | Complete lesson: explanation, review, memorization, recall, and mastery |
| `lesson-memorization.md` | Optional separate memory guide for a large lesson |
| `architecture.md` | Components, ownership boundaries, and data flow |
| `code-walkthrough.md` | Source code explained line by line |
| `exercise.md` | Independent implementation challenge |
| `debugging.md` | Broken behavior, root cause, diagnosis, and permanent fix |
| `security-performance.md` | Security boundaries and performance risks |
| `mastery-review.md` | Final questions, evidence, and mastery score |

## Recommended Repository Structure

```text
nodejs-complete-guide/
├── README.md
├── assets/
│   └── tech-stack.svg
├── Documents/
│   ├── 01/
│   │   ├── introduction-notes.md
│   │   ├── architecture.md
│   │   └── mastery-review.md
│   ├── 02/
│   │   ├── lesson-notes.md
│   │   └── lesson-memorization.md
│   ├── 03/
│   ├── 04/
│   └── ...
├── projects/
│   ├── online-shop/
│   ├── blog-api/
│   └── mini-projects/
├── architecture/
│   ├── request-lifecycle.md
│   ├── event-loop.md
│   ├── mvc.md
│   └── authentication-flow.md
└── reviews/
    ├── weekly-review.md
    └── final-mastery-review.md
```

## Documentation Index

### 01 — Introduction

| Document | Purpose | Status |
|---|---|---|
| [Introduction Notes](./Documents/01/introduction-notes.md) | Answer review, corrected explanations, memorization, active recall, and spaced repetition | Ready |
| Architecture Map | Node.js runtime and basic request lifecycle | Planned |
| Mastery Review | Independent explanation and evidence | Planned |

> The current lesson lives in `Documents/01/`. Create `Documents/02/`, `Documents/03/`, and the following numbered folders as the course grows.

### Future Lessons

Add one row whenever a new lesson document is uploaded:

```markdown
| [Lesson Title](./Documents/02/lesson-name.md) | What the document teaches | Learning |
```

## Eight-Phase Curriculum Roadmap

| Phase | Focus | Required evidence |
|---|---|---|
| 1. Orientation | Node.js purpose and modern JavaScript | Working script and runtime explanation |
| 2. Node Foundations | HTTP, modules, lifecycle, event loop, debugging | Server without Express |
| 3. Web Applications | Express, routing, middleware, templates, MVC | Structured server-rendered application |
| 4. Data Layer | SQL, Sequelize concepts, MongoDB, Mongoose, Turso | Database implementation and comparison |
| 5. Security and Quality | Sessions, authentication, validation, files, pagination, payments | Secure Online Shop workflow |
| 6. API Engineering | REST, async/await, WebSockets, GraphQL | Documented Blog API |
| 7. Production Engineering | Testing, deployment, npm, build tooling | Tested deployment and runbook |
| 8. Modern Runtime | Modern Node.js, TypeScript, Deno, advanced CRUD | Runtime and architecture comparison |

## Lesson Documentation Template

Create each lesson document with this structure:

```markdown
# Lesson Number — Lesson Title

## Learning Objectives
## Concept Overview
## Simple Explanation
## Why This Concept Matters
## How It Works Internally
## Syntax and APIs
## Code Walkthrough
## Architecture and Data Flow
## Common Mistakes
## Security Considerations
## Performance Considerations
## Learning by Doing
## Mini-Project
## Active-Recall Questions
## Memorization Points
## Senior Developer Takeaway
## Final Summary
## Mastery Checklist
## Source Lecture Notes
```

## Lesson Learning Workflow

### Before Watching

1. Read the lesson title and learning objective.
2. Predict which problem the lesson solves.
3. Write what I already know.
4. Identify questions I expect the lecture to answer.

### While Watching

1. Code with the instructor.
2. Pause before each implementation and attempt it independently.
3. Record concepts, decisions, failure cases, and questions.
4. Avoid copying the transcript as the main learning activity.

### After Watching

1. Explain the concept without notes.
2. Rebuild the core behavior from memory.
3. Trace the complete data flow.
4. Break the implementation intentionally.
5. Diagnose and fix the failure.
6. Record security and performance implications.
7. Connect the concept to the Online Shop, Blog API, or another backend project.

## Memorization System

Every technical answer should use this formula:

```text
What is it? → Definition
How does it work? → Mechanism
Why do we use it? → Purpose and application
```

Use the **Cover–Recall–Check** method:

1. Read the correct explanation once.
2. Hide it.
3. Explain it aloud.
4. Write it from memory.
5. Compare and correct it.
6. Repeat until the explanation is natural.

### Review Schedule

| Review | Time |
|---|---|
| Review 1 | Immediately after studying |
| Review 2 | Next day |
| Review 3 | After 3 days |
| Review 4 | After 7 days |
| Review 5 | After 14 days |
| Review 6 | After 30 days |

## Project-Based Learning

### Complete Online Shop

The Online Shop grows with the course:

```text
Raw Node.js
→ Express
→ Routing and middleware
→ Dynamic views
→ MVC
→ Database persistence
→ Authentication
→ Validation and errors
→ File uploads
→ Pagination
→ Payments
→ Testing and deployment
```

### Blog API

The Blog API applies:

- RESTful resource design
- Authentication and authorization
- Async/await
- File uploads
- WebSockets
- GraphQL
- Validation and structured errors
- Tests and deployment

## Mastery Gate

A lesson is not mastered because its video was completed. It is mastered when I can:

- [ ] Explain the concept without notes.
- [ ] Implement the central behavior independently.
- [ ] Trace its architecture and data flow.
- [ ] Debug a broken version.
- [ ] Explain its security boundary.
- [ ] Identify its performance risks.
- [ ] Compare at least one alternative.
- [ ] Apply it to a real project.
- [ ] Provide code, tests, diagrams, or documentation as evidence.

## Progress Tracker

| Section | Topic | Notes | Code | Recall | Project | Status |
|---|---|---:|---:|---:|---:|---|
| 01 | Introduction | ✅ | ✅ | 🔄 | 🔄 | Learning |
| 02 | JavaScript Refresher | ⬜ | ⬜ | ⬜ | ⬜ | Not started |
| 03 | Node.js Basics | ⬜ | ⬜ | ⬜ | ⬜ | Not started |
| 04 | Development Workflow | ⬜ | ⬜ | ⬜ | ⬜ | Not started |

Update this table as lesson documents and implementation evidence are uploaded.

## Senior Developer Takeaway

A beginner asks: **How do I create this route?**

A senior engineer also asks:

1. Who may call it?
2. Is the input validated?
3. Which layer owns the business rule?
4. What happens when a dependency fails?
5. Is the operation secure?
6. Can it handle increased traffic?
7. How are failures logged and observed?
8. How will it be tested?
9. Which data should be returned?
10. Which information must never be exposed?

## Definition of Course Completion

The course is complete when I have:

- Finished and understood the curriculum
- Built the Online Shop and Blog API
- Reconstructed central features without copying
- Added validation, tests, and security controls
- Deployed the applications
- Documented architecture and operational procedures
- Measured one production behavior
- Written a final backend engineering case study

## Author

**Muaddh Alsway**  
Full-Stack Developer progressing toward Senior Software Engineer through project-based learning, architecture analysis, and production engineering.

---

<div align="center">

**Learn deeply. Build independently. Explain clearly. Operate responsibly.**

</div>
