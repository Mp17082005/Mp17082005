<h1 align="center">Mahesh Kumar Pandey</h1>

<p align="center">
  <b>AI Engineer</b> — Agentic systems, RAG pipelines, and LLM infrastructure in production.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mahesh-pandey17/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:maheshkumarpandey17@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Hyderabad,_India-1D9E75?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
</p>

---

### About

I build **agentic AI systems that run in production**, not demos.

Currently an AI Engineer at **Infinall.ai**, where I work on multi-agent orchestration (LangGraph DAGs with Postgres checkpointing, Celery + Redis, SSE streaming), a provider-agnostic LLM gateway with multi-deep fallback chains across OpenAI / Azure / Claude, and per-call credit metering that closed a live cost leak after an audit found **64% of output tokens were unmetered**. Deployed on **AWS EKS** via GitHub Actions and Docker.

Previously a Software Developer Intern at **Bhoomy Informatics**, building FastAPI services with dynamic MongoDB schemas and benchmarking PostgreSQL / MongoDB / Redis / Cassandra / Neo4j for a search personalisation architecture.

- Selected for **Amazon ML Summer School 2025** — top 5% of applicants nationwide
- **Top 5 percentile**, Adobe GenSolve Hackathon 2025
- Most repos below are things I shipped end to end: backend, model layer, and UI

---

### Tech

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML** &nbsp;
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-6E56CF?style=flat-square)

**Backend** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**Data** &nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

**Frontend & Cloud** &nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### Selected work

| Project | What it does | Stack |
|---|---|---|
| **[Exam Prep Companion](https://github.com/Mp17082005/minor_project)** | RAG study assistant — ingests PDF/DOCX/PPTX, chunks to Qdrant with BGE embeddings, answers from your notes, the live web, or the raw model. Includes an AI assignment grader with teacher and student dashboards. | FastAPI · Qdrant · LangChain · Gemini · React |
| **[Slack AI Data Bot](https://github.com/Mp17082005/slack_automation)** | Ask your database a question in plain English from Slack. Gemini writes the SQL, a guard layer rejects anything that isn't a scoped `SELECT`, results come back as a chart plus a CSV download button. | FastAPI · LangChain · PostgreSQL · Slack Block Kit |
| **[Hyp7.0 — Delivery & Transit Mesh](https://github.com/Mp17082005/hyp7.0)** | Three synchronised apps (rider, delivery driver, ride driver) over one matching engine that detects route overlap and merges a grocery drop with a passenger trip when the shared path is cheap enough. | React · TypeScript · Leaflet · Custom matching engine |
| **[FindYourPath](https://github.com/Mp17082005/sih-2025)** | Smart India Hackathon 2025 — multilingual document assistant. Admins upload notices and circulars, users chat against them in any language. | React · Vite · Express · TypeScript |
| **[ProjectFlow](https://github.com/Mp17082005/smart-project-management)** | Jira-style project management — Kanban and list views, role-based admin panel, live activity log, JWT auth, real-time updates over sockets. | React · TypeScript · Express · MongoDB · Socket.IO |
| **[Smart Camera Analytics](https://github.com/Mp17082005/camera_analytics)** | Motion-gated YOLOv8 person detection on a live webcam feed — background subtraction filters static frames so only real intruders trigger a Telegram alert with a photo. | Python · OpenCV · YOLOv8 · Telegram API |

More in the repo list — hackathon builds, a recurring date-picker component with 39 passing Jest tests, a participatory village-planning map, and ML notebooks.

---

### Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Mp17082005&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=7F77DD&icon_color=1D9E75" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mp17082005&layout=compact&hide_border=true&langs_count=8&title_color=7F77DD" alt="Top languages">
</p>

---

<p align="center">
  <i>Open to AI / ML engineering roles. Reach me on <a href="https://www.linkedin.com/in/mahesh-pandey17/">LinkedIn</a>.</i>
</p>
