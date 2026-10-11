# Sathwik Giddi

**Backend and AI systems engineer.**

I build backend services and the AI systems on top of them. Python and FastAPI for the API layer, Go and TypeScript for services that have to stay up, PostgreSQL and Redis for the data, Docker, Kubernetes and Terraform for shipping it.

Most of my work lives in the failure path: what happens when a dependency is slow, a schema drifts, or a token expires mid-request.

Open to backend internships, platform roles and applied AI work. [Email](mailto:sathwikgiddi01@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sathwik-giddi) · [LeetCode](https://leetcode.com/sathwikcreates)

## Now

**Software Engineering Intern, Backend** at Intellious Technologies, June 2026 to present. Six microservices, 219 REST endpoints, 22 integration and API test suites.

Building a retrieval agent that answers from voice. Speech is the input I have the least patience for, so the refusal path gets built before the happy path.

## Selected systems

**DeployX** — a multi-tenant deploy platform. It discovers a customer environment, models how the services and databases depend on each other, validates compatibility, then emits Terraform, Helm, IAM policies, health checks and smoke tests behind a canary with an automated rollback path.

**RemoteOps** — a multi-organization access-control console. Tenant isolation, JWT rotation with token-reuse detection, and audit and penetration-testing harnesses, so the security claims are checkable rather than asserted.

**Cannvue** — an AI interview platform. Real-time interview flow over WebSockets and WebRTC, answer evaluation, proctoring and multilingual text to speech. Used by 50+ users across 2 institutes (self-reported).

**StartupVerse** — a distributed startup simulator. A deterministic business rules engine with five AI functions on top, including multi-agent debate and RAG memory, live company events over WebSockets, and a deterministic fallback when the AI provider is unavailable.

**Legal LLM** — Llama 2-7B fine-tuned with LoRA and QLoRA on a corpus of legal contracts. PDF extraction and semantic chunking feed structured summaries. 92% ROUGE-L and 500 ms inference on an EC2 g4dn.xlarge (self-reported).

**Sonara** — a local-first voice assistant. faster-whisper for speech to text, Piper for text to speech and voice activity detection, all on-device, built around the cost of not paying a cloud provider per utterance.

Engineering notes on all 13 systems, covering what each one does under failure, are in the [portfolio repository](https://github.com/Sathwik-giddi/portfolio).

## How I work

1. Find work done by hand that repeats every week.
2. Build the smallest version that removes it.
3. Put it in front of users within days.
4. Measure. Keep what moves the number. Delete the rest.

**Write the test that would have caught it.** 22 test suites on the Intellious services exist because a regression in timesheets or payroll is expensive.

**Latency is a feature.** Chunking, indexes and caching are product decisions, not afterthoughts.

**Ship on a cadence.** Weekly sprints at Azmth. Predictable releases beat large reveals.

## Writing

Notes from the failure paths: idempotency keys and the retry storm, JWT rotation and token reuse detection, RAG that degrades instead of lying, canary deploys and rollback paths, multi-tenant RBAC, schema drift detection.

## Stack

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=232f3e" alt="AWS" />

## Certified

- SAP Certified Back-End Developer, ABAP Cloud (October 2026)
- Fabric Analytics Engineer Associate, Microsoft (August 2026)
- Cloud Infrastructure 2025 Certified, AI Foundations Associate, Oracle (October 2025)
- Enterprise Design Thinking Practitioner, IBM SkillsBuild (December 2025)
- Agentforce Specialist, Salesforce (August 2025)

## GitHub

<img src="https://github-readme-stats.vercel.app/api?username=Sathwik-giddi&show_icons=true&theme=tokyonight&rank=1" alt="GitHub statistics" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sathwik-giddi&layout=compact&theme=tokyonight" alt="Top languages" width="30%" />

<p><sub>Every number on this profile is measured or self-reported, and labelled as one of the two. Last update: <!-- LAST_UPDATED -->2026-10-11<!-- /LAST_UPDATED --></sub></p>