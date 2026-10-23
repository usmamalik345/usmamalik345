# Osama Malik

**AI agent and full stack engineer working where agents meet infrastructure and security.**
Cost abuse controls, agent guardrails, observability, and the runtime details that keep agent frameworks reliable, plus the web apps and APIs around them.

[![Email](https://img.shields.io/badge/Email-usmamalik344%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:usmamalik344@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-osamamalik346-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/osamamalik346/)
[![Portfolio](https://img.shields.io/badge/Portfolio-usmamalik345.github.io-222222?style=flat-square&logo=githubpages&logoColor=white)](https://usmamalik345.github.io/portfolio-agent/)

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
- **[portfolio-agent](https://github.com/usmamalik345/portfolio-agent):** my live portfolio with an AI agent chat. [Open it](https://usmamalik345.github.io/portfolio-agent/)

---

## 🔀 Open source contributions (merged)

| Project | Pull request |
|---|---|
| [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) | [#5760](https://github.com/pipecat-ai/pipecat/pull/5760) Keep function call timeout armed across intermediate results |
| [strands-agents/harness-sdk](https://github.com/strands-agents/harness-sdk) | [#4313](https://github.com/strands-agents/harness-sdk/pull/4313) Make `AgentResult.to_dict` JSON serializable with bytes |
| [genkit-ai/genkit](https://github.com/genkit-ai/genkit) | [#6346](https://github.com/genkit-ai/genkit/pull/6346) Fix OpenAI plugin embedding validation for `encodingFormat: 'base64'` |
| [phasespace-labs/palinode](https://github.com/phasespace-labs/palinode) | [#166](https://github.com/phasespace-labs/palinode/pull/166) Exit non zero on CLI error paths |
| [linagora/tmail-flutter](https://github.com/linagora/tmail-flutter) | [#4808](https://github.com/linagora/tmail-flutter/pull/4808) Regression tests for reply-to fallback |
| [simolus3/drift](https://github.com/simolus3/drift) | [#3850](https://github.com/simolus3/drift/pull/3850) Docs: CLI and DevTools in FAQ |

**In review:** [pipecat #5791](https://github.com/pipecat-ai/pipecat/pull/5791) (OpenAI Responses cancel race) · [livekit/agents #7186](https://github.com/livekit/agents/pull/7186) (bound EndCallTool wait) · [swarms #2284](https://github.com/kyegomez/swarms/pull/2284) (optional swarm description)

---

## 🎯 Focus areas

- **Agent security:** prompt injection detection, spend and abuse limits, tool call guardrails
- **Infrastructure:** Docker, Nginx, Kubernetes, Helm, Redis, Postgres
- **Observability:** Prometheus, OpenTelemetry, evals with published false positive rates
- **Languages:** Python, TypeScript, JavaScript

---

📫 Reach me at [usmamalik344@gmail.com](mailto:usmamalik344@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/osamamalik346/).

<!-- Optional: add Kubernetes certification line with a Credly/verification link once available. Only add with a public verification URL. -->
