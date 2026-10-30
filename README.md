<div align="center">

# Hi, I'm Naina Sharma 👋

**AI / GenAI Engineer in the making · Full-stack builder · CSE @ Manipal University Jaipur (2027)**

I build LLM-powered applications that are grounded, auditable and safe to run, from RAG assistants and agent tooling to OCR pipelines deployed in production.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naina-sharma-9b21982b2/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nainarksharma@gmail.com)
[![Live Project](https://img.shields.io/badge/Live%20Project-expenzetracker.site-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white)](https://expenzetracker.site)

</div>

---

## 🧭 About me

- 🎓 B.Tech in Computer Science & Engineering at **Manipal University Jaipur** (CGPA 8.32)
- 🤖 Focused on **GenAI**: RAG, tool calling, MCP servers, structured LLM output and evaluation
- 🛡️ I care about **reliability**: every LLM output I ship is validated, grounded in a source, or approved by a human
- 🚀 Comfortable end to end, from the model layer to FastAPI backends to deployment on Linux and AWS
- 🏐 Off the keyboard: captain of the MUJ Girls Volleyball Team

---

## 🚀 Featured projects

### 🧠 [WorkPilot AI](https://github.com/Nainzee/WorkPilot-AI): Meeting workflow automation
Turns meeting transcripts into tasks, owners, deadlines and decisions, then lets teams ask questions across meetings.
- Extraction pipeline that checks every item against a **verbatim source quote**
- **RAG assistant** for cross-meeting Q&A with cited sources
- Custom **MCP server (5 tools)**: the agent can only read and propose, and every write needs manager approval (**0 unapproved writes across 15 safety tests**)
- Low-confidence flags, duplicate and conflict detection, role-based dashboards and audit logging (**flags catch 90% of extraction errors**)

`LangChain` `RAG` `MCP` `Pydantic` `ChromaDB` `SQLite` `Streamlit`

### 🧭 [Career Transition Copilot](https://github.com/Nainzee/Career-Transition-Copilot): Career switch feasibility
Scores how ready someone is to move into a new role, and explains why.
- **O\*NET ETL pipeline**: 96,000+ records distilled into 927 occupations and 258 skills
- Explainable **0 to 100 readiness score** with two-stage matching that fully scores only the top 12 of 927 roles
- In-memory resume parser with **PII scrubbing**
- Grounded LLM insights that only see computed scores, reject ungrounded output, and fall back **Gemini → Groq → Ollama → templates**, so it runs with zero API keys

`Python` `sentence-transformers` `Gemini` `Groq` `Ollama` `Plotly` `Streamlit`

### 💸 [AI Expense Tracker](https://github.com/Nainzee/AI-Expense-Tracker): Receipt scanner and payment tracker ([live](https://expenzetracker.site))
A private, multi-user finance app deployed to production.
- Runs a **vision-language model (Qwen2.5-VL) alongside Tesseract OCR**, cross-checks both, and validates line items against the printed total
- AI advisor that answers spending questions through **validated analytics functions, not generated SQL**
- Bank and UPI statement import (CSV, Excel, PDF) with duplicate detection and receipt matching
- **JWT auth, PBKDF2-HMAC-SHA256 hashing, one SQLite database per user**
- Deployed on **AWS Lightsail** behind Nginx with Let's Encrypt HTTPS and a self-restarting systemd service

`FastAPI` `React` `Tesseract` `Ollama` `Nginx` `AWS`

> More repos: [AI-Dataset-Insight-Generator](https://github.com/Nainzee/AI-Dataset-Insight-Generator) · [hotel-management-system](https://github.com/Nainzee/hotel-management-system)

---

## 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**GenAI & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
`RAG` `MCP` `Tool Calling` `Prompt Engineering`

**Machine Learning & Vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
`sentence-transformers` `DistilBERT` `Tesseract` `TrOCR`

**Backend, Data & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS%20Lightsail-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Fundamentals:** Data Structures & Algorithms · DBMS · Operating Systems · OOP · Machine Learning

---

## 🏅 Experience & leadership

- **Student Coordinator & Web Developer**, SIGBED – MUJ ACM Student Chapter (May 2023 – Jun 2024)
  Built and maintained the chapter website (**700+ member sign-ups**) and coordinated **5 technical events** reaching **300+ participants**.
- **Class Representative**, CSE-F, MUJ (2023 – present)
- **Hackathons:** Smart India Hackathon (SIH) · Deloitte Capstone Project · MUJ HackX
- **Certifications:** Introduction to LLMs & Hugging Face (Coursera) · Data Structures & Algorithms (CodeChef) · Object Oriented Programming (GeeksforGeeks)

---

## 📊 GitHub activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Nainzee&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nainzee&theme=tokyonight&hide_border=true&layout=compact" alt="Top languages" />

</div>

---

## 📫 Let's connect

I'm open to **internships and entry-level roles in GenAI, ML and backend engineering**. If you're building something with LLMs, agents or applied AI, I'd love to talk.

📧 [nainarksharma@gmail.com](mailto:nainarksharma@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/naina-sharma-9b21982b2/)
