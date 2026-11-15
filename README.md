<h1 align="center">Hi, I'm Aditi 👋</h1>

<p align="center">
  Software Engineer · MS in ECE (ML/Data Science), USC · 4.0 GPA<br/>
  Mountain View, CA
</p>

<p align="center">
  <a href="https://aditi-tarate.netlify.app/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/aditi-tarate/">LinkedIn</a> ·
  <a href="mailto:adititarate15@gmail.com">Email</a>
</p>

---

## 💫 About Me

I enjoy building systems that solve real problems, especially where machine learning meets infrastructure. I like working through ambiguity and turning complex ideas into something reliable and usable.

I spent three years as a Platform Engineer at Mastercard running PostgreSQL, Oracle and Redis, then finished my master's at USC in May 2026. Lately I've been writing Go and Python, building AI agent tooling, and working on a production access management platform with a small volunteer team.

Outside of code you'll find me cooking, reading, or out exploring nature.

## 🛠️ Experience

**Software Engineer, Easley-Dunn Productions** · Remote · Jul 2026 to present
- Contributing to Cerberus, a Node.js/Express and PostgreSQL access management platform across 8+ services, being deployed to production for 150+ users.
- Owned the Discord API integration for invites, offboarding and user ID resolution, cutting onboarding from about 2 days to 5 minutes.
- Built the login system with a team of four: email/password auth with bcrypt, 7-day JWT sessions and four-tier role-based access control.
- Led containerization with multi-stage Dockerfiles and a 3-service Docker Compose stack, and designed the GitHub Actions to GHCR image pipeline.

**Research Assistant, USC Marshall School of Business** · Los Angeles · Mar to May 2025
- Built Selenium and BeautifulSoup scrapers to extract 100+ shareholder letters.
- Built pdfplumber pipelines that turn raw PDFs into clean, NLP-ready datasets.

**Platform Engineer II, Mastercard** · Pune, India · May 2021 to Jul 2024
- Automated database operations (backups, patching, config updates) as code with Bash, Python, Bitbucket and Chef, cutting manual effort by 50% across 100+ nodes.
- Monitored and debugged production PostgreSQL, Oracle and Redis, resolving locking, connection limit and storage failures.
- Took part in on-call rotations, diagnosing filesystem issues, failed backups and alerting problems.
- Built log analysis and alert reduction tooling in Python and SQL, reducing recurring alerts by 40%.
- Built a SQL-backed Tableau dashboard for capacity planning and worked with 10+ engineering teams on database integrations.
- Started as a Data Engineer Intern, building ETL pipelines and Domo dashboards for real-time ticketing performance used by 5+ teams.

## 🚀 Projects

| Project | What it does | Stack |
|---|---|---|
| [MCP Gateway](https://github.com/aditi-2400/MCP-gateway-in-go) | Security proxy between AI agents and MCP tool servers. Default-deny policy engine, per-agent rate limits and a fail-closed audit log. Protocol layer written from scratch. About 18,000 calls/s with under 0.1 ms added per call. | Go, Prometheus, OpenTelemetry |
| [Computer-Use Automation Agent](https://github.com/aditi-2400/computer-use-automation-agent) | Discovers browser workflows with Playwright, replays them with no model calls, and hands the session to a person when a step gets stuck or needs approval. | Python, Claude API, Ollama, FastAPI |
| [Go Rate Limiter](https://github.com/aditi-2400/ratelimiter) | Open-source library with Token Bucket, Leaky Bucket and two Sliding Window algorithms behind one `Limiter` interface and a pluggable store. | Go |
| [Price Drop & Deal Alert System](https://github.com/aditi-2400/price-drop-deal-alert-system) | Tracks prices and sends alerts through an SQS to Lambda pipeline. Cached FastAPI dashboard with ML buy/wait signals. Full AWS infra from shell scripts. | React, FastAPI, PostgreSQL, Redis, AWS |
| [AI Powered Fairness Auditor](https://github.com/aditi-2400/AI-Powered-Bias-Hunter) | Detects model disparities with Fairlearn and uses a Llama 3.2 agent to explain causes and recommend mitigations. | Python, Llama 3.2, Fairlearn |
| [AnomEdge](https://github.com/aditi-2400/AnomEdge---Edge-AI-for-real-time-industrial-anomaly-response) | Edge AI for industrial anomaly response: Gemma-3 fine-tuned with LoRA, RAG over SOPs and voice alerts. | Python, LoRA, RAG, TTS |

**Open source:** merged a PR into [WeblateOrg/weblate](https://github.com/WeblateOrg/weblate).

## 💻 Tech Stack

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Backend and Systems**<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge)
![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-555555?style=for-the-badge)

**Infra and Tools**<br/>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Chef](https://img.shields.io/badge/Chef-F09820?style=for-the-badge&logo=chef&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code_&_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLMs_&_Agents-555555?style=for-the-badge)

**Databases**<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com?user=aditi-2400&theme=github-dark&hide_border=true" />
  <img height="170" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=aditi-2400&layout=compact&theme=github_dark&hide_border=true" />
</p>

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aditi-2400/aditi-2400/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aditi-2400/aditi-2400/output/github-snake.svg" />
    <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/aditi-2400/aditi-2400/output/github-snake.svg" />
  </picture>
</p>

<p align="center"><i>Still learning. Still building. Still hungry.</i></p>
