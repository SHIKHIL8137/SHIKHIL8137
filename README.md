<div align="center">

# Hi, I'm Shikhil K S 👋

**Software Engineer · Full Stack Developer**

React · Node.js · TypeScript · Databases · AI/RAG systems
📍 Kerala, India · Open to relocation

[![Portfolio](https://img.shields.io/badge/Portfolio-shikhil.kavlien.store-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://shikhil.kavlien.store)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shikhil-k-s-870392215)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:connect.shikhil@gmail.com)

</div>

---

## 👨‍💻 About

I'm a Software Engineer building full-stack web applications. My day-to-day stack is **React, TypeScript, Node.js and MongoDB**.

Outside work I build developer tooling, document-retrieval (RAG) systems and self-hosted infrastructure. I like problems where the boring parts decide whether software is trustworthy: data models, validation, background jobs, access control, tests and deployment.

## 🛠️ Tech stack

| | |
|---|---|
| **Professional, day to day** | ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) |
| **Built in projects** | ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?logo=socketdotio&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?logo=webrtc&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![AWS](https://img.shields.io/badge/AWS_EC2-232F3E?logo=amazonwebservices&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint&logoColor=white) |
| **RAG and AI (projects)** | Qdrant · ChromaDB · embeddings · semantic retrieval · retrieval evaluation · Ollama · Docling · Tika · pdfplumber · OCR |
| **Exploring** | LangGraph and agent workflows · Kafka and BullMQ · gRPC · Kubernetes · Jenkins pipelines |

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [DevWorkspace](https://devworkspace.kavlien.store)
**Project context for AI coding agents**

A CLI that keeps a project's structure, engineering knowledge and verification rules in the repo, so agents don't rediscover the codebase every session.

- Deterministic project analysis (no AI call needed)
- Facts and tasks stored with the code, plus verification gates
- Optional Graphify, Agent Skills and Ponytail integrations
- Unit, integration and end-to-end tests; deployed with Docker Compose and Nginx

`TypeScript` `Node.js` `React` `Vite` `Docker` `Nginx`

[🔗 Project site](https://devworkspace.kavlien.store)

</td>
<td width="50%" valign="top">

### [Document RAG](https://rag-sample.kavlien.store)
**Question answering over PDFs**

Ask questions about PDF documents and get answers that cite their sources.

- Document extraction pipeline and vector search with Qdrant
- Local inference with Ollama
- QA tests for answer relevance, retrieval precision, missing-information handling and latency
- Experimental OCR for scanned pages (Qwen2.5-VL, Tesseract fallback)

`Python` `FastAPI` `Qdrant` `Redis` `Ollama`

[🔗 Live demo](https://rag-sample.kavlien.store)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Kavlien Databases
**Self-hosted database provisioning**

One management workflow for PostgreSQL, MongoDB, Redis, Qdrant and Chroma instances.

- Docker-based provisioning with per-instance isolation
- Health checks, persistent storage, credential handling
- Backups and restore workflows planned

`Docker` `PostgreSQL` `MongoDB` `Redis` `Qdrant`

🔒 Private repository

</td>
<td width="50%" valign="top">

### [HomeLab Control Center](https://github.com/SHIKHIL8137/HomeLab-Control-Center)
**Read-only home server dashboard**

Host metrics, Docker containers, registered projects, health and audit history.

- Login, sessions and CSRF protection
- Authenticated, allowlisted Docker proxy; secrets delivered as files
- Preflight command that validates deployment config
- Status: release candidate, tested locally, not yet deployed

`TypeScript` `Node.js` `Docker`

[🔗 Repository](https://github.com/SHIKHIL8137/HomeLab-Control-Center)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [DevConnect](https://github.com/SHIKHIL8137/DevConnect)
**Freelancer and client collaboration**

Messaging, calls, projects and payments in one place.

- Microservice-style backend using Clean Architecture and the Repository Pattern
- Real-time chat and audio/video with Socket.io and WebRTC
- Razorpay payments and invoice generation
- Deployed on GCP with Nginx (demo currently offline)

`React` `Node.js` `MongoDB` `Socket.io` `WebRTC` `Razorpay`

[🔗 Repository](https://github.com/SHIKHIL8137/DevConnect)

</td>
<td width="50%" valign="top">

### [iDeal](https://github.com/SHIKHIL8137/iDeal)
**Second-hand iPhone marketplace**

A complete server-rendered store with payments and admin reporting.

- Authentication, sessions, cart, checkout and order flows
- Razorpay with payment retry handling; PDF invoices
- Admin dashboard (Chart.js) for sales and inventory
- Location-based delivery charges; deployed on AWS EC2 with Nginx

`Node.js` `Express` `EJS` `MongoDB` `Razorpay` `AWS`

[🔗 Repository](https://github.com/SHIKHIL8137/iDeal)

</td>
</tr>
</table>

## 💼 Experience

**Full Stack Developer Trainee, Brototype** (Kochi, Aug 2024 – Nov 2025)
MERN program focused on building and deploying full-stack applications. Several projects above started here.

## 🎯 What I'm working toward

- **Backend and data:** database design and query optimization, background jobs and event-driven patterns
- **AI tooling:** retrieval quality and evaluation for RAG, developer tools that give AI agents durable context
- **Delivery:** automated testing and repeatable deployments
- **Self-hosting:** keeping my own infrastructure secure and observable

## 📫 Let's connect

I'm open to software engineering opportunities, full-stack development, backend engineering and interesting technical collaborations.

<div align="center">

[![Email](https://img.shields.io/badge/Email-connect.shikhil@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:connect.shikhil@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shikhil--k--s-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shikhil-k-s-870392215)
[![Portfolio](https://img.shields.io/badge/Portfolio-shikhil.kavlien.store-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://shikhil.kavlien.store)
[![DevWorkspace](https://img.shields.io/badge/DevWorkspace-live-2ea44f?style=flat-square)](https://devworkspace.kavlien.store)
[![Document RAG](https://img.shields.io/badge/Document_RAG-demo-2ea44f?style=flat-square)](https://rag-sample.kavlien.store)

</div>
