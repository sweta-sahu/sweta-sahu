<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=200&section=header&text=Sweta%20Sahu&fontSize=42&fontColor=ffffff&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=764BA2&center=true&vCenter=true&width=650&lines=Software+Engineer+%C3%97+AI%2FML+Engineer;Building+agentic+RAG+%26+multi-agent+systems;Ex-TCS+%7C+M.S.+CS+%40+University+at+Buffalo;Open+to+SDE+%2F+AI+Engineering+roles" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🟢_Open_to_Work-success?style=for-the-badge" />
</p>

<p align="center">
📧 <a href="mailto:sahuswetaa23@gmail.com">sahuswetaa23@gmail.com</a> &nbsp;•&nbsp;
💼 <a href="https://linkedin.com/in/23-sweta-sahu">LinkedIn</a> &nbsp;•&nbsp;
🌐 <a href="https://sweta-sahu.github.io/Portfolio/">Portfolio</a> &nbsp;•&nbsp;
📍 New York, USA
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sweta-sahu&color=764ba2&style=flat-square&label=Profile+Views" />
</p>

---

## 👋 About Me

I'm a software engineer with **~4.5 years of experience** building scalable backend systems and, more recently, **agentic AI / GenAI applications** — the kind that plan, retrieve, and reason across tools rather than just call an LLM once and hope for the best.

I care about systems that are **reliable, explainable, and grounded** — whether that's a multi-agent LangGraph pipeline that has to justify its own retrieval, or a Spring Boot microservice that has to survive a 3am pager alert.

> *Good systems make intelligence usable.*

---

## 🎓 Education

<table width="100%">
<tr>
  <td><b>University at Buffalo, The State University of New York</b></td>
  <td align="right"><i>Buffalo, NY</i></td>
</tr>
<tr>
  <td>M.S., Computer Science and Engineering (AI/ML Specialization) — GPA: 3.867/4.0</td>
  <td align="right"><i>Aug 2024 – Dec 2025</i></td>
</tr>
</table>

<table width="100%">
<tr>
  <td><b>Ramrao Adik Institute of Technology</b></td>
  <td align="right"><i>Navi Mumbai, India</i></td>
</tr>
<tr>
  <td>B.E., Electronics and Telecommunication Engineering — GPA: 3.72/4.0</td>
  <td align="right"><i>June 2017 – June 2021</i></td>
</tr>
</table>

---

## 💼 Experience

### AI Software Engineer, The Research Foundation for SUNY
*Buffalo, NY · Feb 2026 – Jul 2026*

One of two engineers taking a materials-science research platform from prototype to production.

- Architected a multi-agent system in **LangGraph** that combines deterministic routing with an LLM-driven planning loop to autonomously orchestrate 15+ tool-calling steps across research workflows, cutting multi-step query latency ~40%
- Built a **FastAPI** vector-database pipeline that chunks, embeds, and retrieves from technical papers and textbooks, wiring in live tool-based RAG against JARVIS-DFT, Materials Project, and OPTIMADE across 1,000+ documents
- Deployed self-hosted **ALIGNN** and **MACE** models for real-time materials-property prediction — a deliberate tradeoff over third-party APIs to protect data privacy and control cost — with uptime/latency monitored via Grafana
- Built a deterministic confidence-flagging framework (4 validation functions) that automatically catches cross-database conflicts and methodology mismatches, cutting flagged data-inconsistency issues ~50%

### Senior Research Aide, The Research Foundation for SUNY
*Buffalo, NY · Feb 2025 – Dec 2025*

- Architected a fault-tolerant, high-throughput IoT pipeline on **AWS IoT Core, Kinesis, and Lambda**, processing 1M+ telemetry events/day over MQTT/Modbus while holding 99.9% uptime for mission-critical sensor data
- Built a fully automated **SageMaker** retraining pipeline — an S3-triggered Lambda kicks off retraining once enough new data accumulates — improving precision 22% across successive runs
- Cut monthly SageMaker infra cost 63% by moving model hosting from always-on real-time endpoints to event-driven, on-demand inference
- Engineered low-latency **WebSocket** pipelines for real-time analytics supporting 500+ concurrent users with sub-second state updates
- Automated multi-region infra with **Terraform, Docker, and Kubernetes (EKS)**, cutting provisioning time 60%, and enforced 95% test coverage with automated OWASP audits in CI/CD

### Software Developer, Tata Consultancy Services
*Mumbai, India · June 2021 – July 2024*

- Owned backend architecture and production delivery for 3 high-traffic **Spring Boot** microservices, designing 25+ REST APIs and improving production reliability 30%
- Redesigned an event-driven system on **Apache Kafka** that cut inter-service latency ~40%; later diagnosed a consumer-lag incident and resolved it by scaling to a partitioned, parallel consumer group
- Cut database load 45% and response times 60% with **Redis** caching and P95 latency tuning; later tracked down and fixed a production cache-consistency bug caused by delayed invalidation after MongoDB writes
- Led a zero-downtime **PostgreSQL → MongoDB** migration for 20K+ production records, redesigning the schema around the data's actual document shape instead of forcing relational joins it never needed
- Hardened a Digital ID platform with **Keycloak RBAC (OAuth2/OIDC)** across 50+ endpoints and Hibernate Envers for full change traceability, while acting as backend owner/mentor running 10+ code reviews and on-call rotations

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛫 [WanderGenie](https://github.com/sweta-sahu/WanderGenie-ai-travel-assistant)
Agentic trip-planning system with 3 specialized LangGraph agents (Planner, Researcher, Packager-Executor) turning natural-language requests into complete itineraries with maps and booking links.

Built the dual-memory retrieval layer — Supabase pgvector for local insights, Neo4j for relationship-aware POI clustering — with LLM fallback generation for cities with no cached data.

`LangGraph` `FastAPI` `React/TS` `pgvector` `Neo4j`

</td>
<td width="50%" valign="top">

### 🕵️ [Incident Zero](https://github.com/sweta-sahu/Incident-Zero)
Multimodal AI security-investigation platform coordinating 5 specialized MCP servers — CodeScan, LogReasoner, ScreenshotAnalyzer, DiagramExtractor, Patcher — to correlate evidence across code, logs, diagrams, and screenshots.

Built CodeScan/LogReasoner to statically flag hardcoded secrets and SQL injection risk, and parse multi-MB logs for severity-scored attack patterns.

`MCP` `Python` `OCR` `Static Analysis`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 [XAI Trading Copilot](https://github.com/sweta-sahu/Explainable-AI-Trading-Copilot)
Explainable stock-prediction platform — XGBoost + SHAP deployed via AWS SageMaker Serverless Inference for real-time, cost-efficient, auditable predictions.

Built Lambda pipelines ingesting market data (Stooq) and news sentiment (GDELT) for feature engineering, with a React frontend showing SHAP-based plain-English explanations for every call.

`XGBoost` `SHAP` `AWS SageMaker` `React`

</td>
<td width="50%" valign="top">

### 🎓 [Adaptive RL Tutor](https://github.com/sweta-sahu/Adaptive-RL-Tutor)
RL-based algebra tutor — a Double Dueling DQN agent personalizing question/hint selection across 10 skills and a 20-action space.

Engineered a multi-objective reward function balancing correctness, mastery gain, skill-coverage fairness, and engagement (boredom/confidence modeling), with a Streamlit demo for live mastery tracking.

`PyTorch` `DDQN` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔥 [Agni Intel](https://github.com/sweta-sahu/next-day-wildfire-spread-prediction-and-reporting)
Wildfire spread forecasting — fine-tuned Swin-UNet V2 on 13,000+ satellite image samples for next-day spread prediction (0.92 accuracy, 0.95 F1, 0.90 IoU).

Integrated an 8-bit quantized Mistral-7B to auto-generate incident reports grounded strictly in computed burn-area/spread metrics — no hallucinated numbers — delivered as a downloadable PDF for responders.

`PyTorch` `Swin-UNet V2` `FastAPI` `Mistral-7B`

</td>
<td width="50%" valign="top">

### 🖥️ Pintos OS Kernel Extension
Extended a teaching OS kernel in C: an interrupt-safe alarm clock, a priority-donation system supporting nested donation chains, and a 4.4BSD-style multi-level feedback queue scheduler.

Also implemented user-space argument passing, a per-process file-descriptor table, centralized pointer validation before any lock acquisition, and semaphore-based parent-child sync handling zombie/orphaned processes — passed the full test suite.

`C` `Systems Programming`

</td>
</tr>
</table>

---

## 🧬 Tech Stack

### 💻 Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,java,cpp,c,js,ts" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

### 🧠 AI / ML & Agentic Systems
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LangGraph-4B5563?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-6366F1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/XGBoost-EB5E28?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SHAP-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
</p>

### ⚙️ Backend & Real-Time Infra
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,spring,kafka" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge" />
</p>

### 🗄️ Databases & Vector Stores
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white" />
</p>

### ☁️ Cloud & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,git" />
  <img src="https://img.shields.io/badge/GitHub_Actions_CI/CD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

### 🔐 Auth & Security
<p>
  <img src="https://img.shields.io/badge/Keycloak-0071C1?style=for-the-badge&logo=keycloak&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Cognito-512888?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth2%2FOIDC-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OWASP_Top_10-4B32C3?style=for-the-badge" />
</p>

### 📡 Big Data & Streaming
<p>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Kinesis-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
</p>

### 🎨 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react,html,css" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>

### 🛠️ AI-Assisted Development
<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white" />
  <img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge" />
</p>

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-stats-alpha.vercel.app/api?username=sweta-sahu&cc=1a1b27&tc=c0caf5&ic=7aa2f7&bc=1a1b27" height="195" alt="GitHub stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=sweta-sahu&theme=tokyonight" height="195" alt="Top languages by repo" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=sweta-sahu&theme=tokyonight&hide_border=true" height="180" alt="GitHub streak" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=sweta-sahu&theme=tokyonight" height="180" alt="Most used languages by commit" />
</p>

<p align="center">
  <img src="https://github-trophies.vercel.app/?username=sweta-sahu&theme=tokyonight&no-frame=true&row=1&column=6&margin-w=10" alt="GitHub trophies" />
</p>

### 🐛 Contribution Graph

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sweta-sahu/sweta-sahu/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sweta-sahu/sweta-sahu/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/sweta-sahu/sweta-sahu/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

## 🌱 Beyond Code

- ✈️ Traveling and exploring new cultures
- 🍳 Cooking — especially experimenting with new cuisines
- 💃 Dancing — my favorite way to reset after debugging

---

<p align="center">
  <i>Currently exploring AI/ML, Applied AI, Backend, and Full-Stack Engineering roles — let's connect!</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:764ba2,100:667eea&height=120&section=footer" />
</p>
