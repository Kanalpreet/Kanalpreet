<!-- =========================================================
     KANALPREET KAUR | GITHUB PROFILE README
     Repository: https://github.com/Kanalpreet/Kanalpreet
     Requires these three SVG files in the same folder as this README:
       header.svg · terminal.svg · footer.svg
     ========================================================= -->

<div align="center">

<img src="header.svg" width="100%" alt="Kanalpreet Kaur - AI Engineer focused on RAG and agentic systems"/>

<br/><br/>

<img src="terminal.svg" width="720" alt="Terminal intro: whoami, focus, projects and engineering principle"/>

<br/><br/>

<a href="https://www.linkedin.com/in/kanalpreet-kaur-479079327">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://kanalpreet-ai-forge.lovable.app/">
  <img src="https://img.shields.io/badge/Portfolio-Explore-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
</a>
<a href="mailto:kanalpreetk@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</div>

---

## 👋 About Me

I'm a final-year **B.Tech CSE (AI & ML)** student and a **Backend AI Engineering Intern at FlyRank AI**. I'm interested in building practical AI systems that combine LLMs, agentic workflows, and backend engineering to solve real-world problems, with a focus on reliability, evaluation, and responsible automation.

| | |
|---|---|
| 🎓 **Education** | B.Tech CSE (AI & ML), IK Gujral Punjab Technical University · **CGPA: 8.75/10** · Class of 2027 |
| 💼 **Current Role** | Backend AI Engineering Intern @ FlyRank AI |
| 🔬 **Previous Role** | Data Science Intern @ CBA Infotech |
| 🎯 **Interests** | Applied AI, Agentic Systems, RAG, Generative AI, and Backend Engineering |

---

## 🔭 Currently

- 🧾 **Building:** An AI Procurement Agent using LangGraph, FastAPI, and PostgreSQL.
- 🤖 **Exploring:** Agentic AI workflows, LLM-powered applications, and backend AI systems.
- 📐 **Learning:** RAG evaluation, agent orchestration, and AI guardrails.

---

## 💼 Experience

<table>
  <tr>
    <td width="30%" valign="top">
      <strong>Backend AI Engineering Intern</strong><br/>
      FlyRank AI<br/>
      <sub>Jul 2026 – Present</sub>
    </td>
    <td valign="top">
      Building FastAPI backend APIs and contributing to RAG pipelines for AI-powered document retrieval systems.
    </td>
  </tr>
  <tr>
    <td width="30%" valign="top">
      <strong>Data Science Intern</strong><br/>
      CBA Infotech<br/>
      <sub>Add your internship dates</sub>
    </td>
    <td valign="top">
      Worked on data preprocessing, machine learning model development, and data analysis to build predictive solutions.
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 🏦 RegMind AI — Regulatory Compliance Intelligence

> An AI-powered regulatory compliance system designed to identify potential conflicts between RBI regulations and internal organizational policies.

- **Stack:** React · FastAPI · Qdrant · Hybrid RAG
- **Retrieval:** BM25 and dense vector search combined using Reciprocal Rank Fusion (RRF).
- **Risk Analysis:** XGBoost-based compliance-risk classification.
- **Evaluation:** Testing retrieval and generation quality to identify fabricated clause references and improve retrieval reliability.
- 🔗 **Repository / Demo:** Add your project links when available.

### 📊 Student Performance Prediction System

A machine learning project that predicts student performance using a structured data pipeline, model tuning, and a web-based prediction interface.

- **Approach:** Data preprocessing, model training, and hyperparameter tuning using GridSearchCV and cross-validation.
- **Model:** CatBoost.
- **Deployment:** Flask REST API deployed on Render.
- **Repository:** [View on GitHub](https://github.com/Kanalpreet/mlproject)

### 🧾 AI Procurement Agent *(In Progress)*

> An agentic procurement workflow that finds suppliers, requests quotations, compares offers, and seeks human approval before purchase commitments.

- **Stack:** Python · FastAPI · LangGraph · PostgreSQL
- Flags missing or conflicting supplier information instead of guessing.
- Performs cost comparisons using deterministic code.
- Supports persistent workflows and recovery after restarts.
- Requires human approval before purchase commitments.
- Includes repeatable evaluation scenarios for testing failure cases.
- 🔗 **Repository:** Add the link when the project is public.

### 🌾 FarmCulture — AI-Powered Crop Recommendation

A crop recommendation project using machine learning and generative AI to support cultivation decisions based on information such as soil type, rainfall, temperature, and location.

- **Stack:** Python · Random Forest · Gemini API · FastAPI · React · Bootstrap
- **Recognition:** Presented at NIT Hamirpur.
- **Repository:** [View FarmCulture](https://github.com/vanshbhutani1405/FarmCulture)

<details>
<summary><strong>📂 More Machine Learning Projects</strong></summary>

<br/>

| Project | Description | Technologies |
|---|---|---|
| [Book Recommendation System](https://github.com/Kanalpreet/recommendationSystem) | Recommends books using collaborative filtering and cosine similarity. | Python · scikit-learn |

</details>

---

## 🧭 How I Approach AI Systems

```mermaid
flowchart TD
    A[User Request] --> B[LangGraph Workflow]
    B --> C{Tool or Retrieval Needed?}
    C -->|Yes| D[Tools and RAG]
    C -->|No| E[LLM Reasoning]
    D --> F{Human Approval Required?}
    E --> F
    F -->|Yes| G[Human Review]
    F -->|No| H[Return Result]
    G --> H
    H --> I[Evaluation and Logs]
```

**Engineering principles**

1. **Ground outputs in data:** Flag missing information instead of inventing details.
2. **Evaluate early:** Treat failure cases as test cases.
3. **Keep humans involved:** Require approval for consequential or irreversible actions.
4. **Use deterministic code:** Handle calculations and validation in code wherever possible.
5. **Make systems traceable:** Maintain logs and document limitations.

---

## ⚙️ Tech Stack

**AI / LLM / Retrieval**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1D4ED8?style=flat-square)
![RAG](https://img.shields.io/badge/RAG%20%2F%20CRAG-7C3AED?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=googlegemini&logoColor=white)

**Backend & Data**

![Python](https://skillicons.dev/icons?i=python,fastapi,flask,postgres,docker,aws,git&theme=dark)

**Frontend**

![React](https://skillicons.dev/icons?i=react,vite,bootstrap,html,css&theme=dark)

**Machine Learning**

![ML](https://skillicons.dev/icons?i=tensorflow,sklearn,pandas,numpy&theme=dark)

**Languages:** Python · C++ · SQL · C · JavaScript

---

## 📜 Certifications

![LangChain Academy](https://img.shields.io/badge/LangChain_Academy-Intro_to_LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangChain_Academy-Intro_to_LangGraph-1D4ED8?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-Prompt_Engineering-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-AI_Fluency-CC785C?style=for-the-badge)

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Kanalpreet&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub statistics"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kanalpreet&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Most used programming languages"/>

</div>

---

## 🤝 Let's Connect

🎯 **Looking for:** An AI Engineer role where I can own what I build and learn something new every week.

<div align="center">

<a href="https://www.linkedin.com/in/kanalpreet-kaur-479079327">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:kanalpreetk@gmail.com">
  <img src="https://img.shields.io/badge/Email-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://kanalpreet-ai-forge.lovable.app/">
  <img src="https://img.shields.io/badge/Portfolio-Explore_My_Work-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
</a>

<br/><br/>

<img src="footer.svg" width="100%" alt="Building intelligent systems that are evaluated, reliable, and useful."/>

</div>
