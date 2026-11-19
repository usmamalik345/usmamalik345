# Osama Malik, AI Agent Engineer

I build AI agents, RAG, voice agents and LLM cost and security guards. Full stack, .NET, DevOps.

3+ years experience. Onlinx Solutions Jul 2024 to present.

At Onlinx I also build and maintain a production point of sale and inventory platform: ASP.NET Core (.NET 8) backend with MySQL, Dapper and SignalR, Angular 19 frontend, and AWS S3 and Textract, shipped in Docker.

[![Email](https://img.shields.io/badge/Email-usmamalik344%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:usmamalik344@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-osamamalik346-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/osamamalik346)
[![X](https://img.shields.io/badge/X-Osa__ma346-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Osa_ma346)
[![dev.to](https://img.shields.io/badge/dev.to-osamamalik-000000?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/osamamalik)
[![Website](https://img.shields.io/badge/Website-osamamalik.me-222222?style=flat-square)](https://osamamalik.me)
[![Hire](https://img.shields.io/badge/Hire-osamamalik.me-222222?style=flat-square)](https://osamamalik.me/hire/)
[![Blog](https://img.shields.io/badge/Blog-osamamalik.me-222222?style=flat-square)](https://osamamalik.me/blog/)

📍 Islamabad, Pakistan

---

## 🛡️ BleedStop

**[BleedStop](https://github.com/usmamalik345/bleedstop)** is a cost abuse control plane for LLM, SMS and payment APIs, aimed at OWASP LLM10 (Unbounded Consumption). Apps call `POST /decide` before spending money and get `ALLOW`, `LIMIT`, `CHALLENGE` or `DENY` from deterministic per tenant rules, enforced atomically across instances through Redis.

**Measured in the repo** (raw JSON in [`results/`](https://github.com/usmamalik345/bleedstop/tree/main/results)):

- **6,291 decisions/s** at p99 31.9 ms across 3 instances
- Kubernetes rollout restart of 6 pods under load with **0 failed requests**
- Agent guard held out detection of 22.5% at 0% false positives, reported as is

**Stack:** Node and Python SDKs, Express middleware, FastAPI dependency, Redis, Postgres, Prometheus, OpenTelemetry, Docker Compose, Helm chart

[Live demo](https://bleedstop-demo.vercel.app/) · [Project site](https://usmamalik345.github.io/bleedstop/)

---

## 🧰 Tech stack

**AI and agents**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-5A4FCF?style=flat-square) ![Vector DBs](https://img.shields.io/badge/Vector_DBs-FF6F61?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![LiveKit](https://img.shields.io/badge/LiveKit-1F1F1F?style=flat-square) ![Pipecat](https://img.shields.io/badge/Pipecat-2F80ED?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**  
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=white)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**DevOps and cloud**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Security and observability**  
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Prompt injection defense](https://img.shields.io/badge/Prompt_injection_defense-B22222?style=flat-square)

---

## 🧱 Full stack work

- **[doctor-appointment-website](https://github.com/usmamalik345/doctor-appointment-website):** MERN app (MongoDB, Express, React, Node.js) with separate backend, frontend and admin parts; patients sign up, browse doctors by specialization, book and cancel appointments, and admins add doctor profiles.
- **[AI-code-reviewer](https://github.com/usmamalik345/AI-code-reviewer):** Node.js and Express GraphQL (Apollo) server that parses JavaScript with acorn to flag duplicate, complex and oversized functions and return a quality score.
- **[Node.js-Social-Media-REST-API-with-MongoDb](https://github.com/usmamalik345/Node.js-Social-Media-REST-API-with-MongoDb):** Express and Mongoose REST API with auth and user routes, using helmet and morgan.
- **[portfolio-agent](https://github.com/usmamalik345/portfolio-agent):** my live portfolio with an AI agent chat. [Open it](https://osamamalik.me)

---

## 🔀 Open source

Merged pull requests in [Pipecat](https://github.com/pipecat-ai/pipecat/pull/5760) (#5760), [Genkit](https://github.com/genkit-ai/genkit/pull/6346) (#6346), and [Strands](https://github.com/strands-agents/harness-sdk/pull/4313) (#4313). [LiveKit](https://github.com/livekit/agents/pull/7186) (#7186) is open.

---

## 🎯 Focus areas

- **Agent security:** prompt injection detection, spend and abuse limits, tool call guardrails
- **Infrastructure:** Docker, Nginx, Kubernetes, Helm, Redis, Postgres
- **Observability:** Prometheus, OpenTelemetry, evals with published false positive rates
- **Languages:** Python, TypeScript, JavaScript

---

📫 Reach me at [usmamalik344@gmail.com](mailto:usmamalik344@gmail.com), [LinkedIn](https://www.linkedin.com/in/osamamalik346), [X](https://x.com/Osa_ma346), or [dev.to](https://dev.to/osamamalik).

<!-- Optional: add Kubernetes certification line with a Credly/verification link once available. Only add with a public verification URL. -->
