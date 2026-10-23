# Osama Malik

**AI agent engineer working where agents meet infrastructure and security.**
Cost abuse controls, agent guardrails, observability, and the runtime details that keep agent frameworks reliable.

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

Also: **[portfolio-agent](https://github.com/usmamalik345/portfolio-agent)**, my portfolio with an AI agent you can chat with.

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
