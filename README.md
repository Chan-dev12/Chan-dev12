<h1 align="center">Hi, I'm Chanthru 👋</h1>
<h3 align="center">AI Engineer · Agentic systems · RAG evaluation · Computer vision</h3>

<p align="center">
  <img alt="Typing intro" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1200&color=00C2FF&center=true&vCenter=true&width=760&lines=Multi-agent+systems+with+LangGraph;RAG+I+measure%2C+not+just+demo;Vision+models+shipped+as+APIs;LLMs+with+guardrails+in+code" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/chanthru-v/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-chanthru--v-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:chanthru26v@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-chanthru26v%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=Chan-dev12&label=Profile%20views&color=0e75b6&style=flat-square" />
</p>

---

## 👨‍💻 About me

- 🎓 AI & ML student at **Saveetha Engineering College**
- 🤖 I build **agentic AI systems**: supervisor/worker graphs, debate-style agents, tool-scoped agents with real database access
- 📏 I care about **measuring** what I build: ablations, baselines, confidence intervals, test suites
- 🔒 I keep the LLM away from decisions it shouldn't make. **Risk rules, access control and counting all run in code.**
- 💸 Most of my projects run on a laptop or on free tiers (Ollama, Gemini free tier, Render, Vercel, Neon)
- 🔭 Currently building **Mandate** for the PayPal AI Hackathon 2026: spending mandates for AI agents, enforced before any payment call

---

## 🏆 Hackathons

| Result | Event |
|---|---|
| 🥇 **1st Place** | Qtuxathon 3.0, Sairam Engineering College |
| 🥈 **2nd Runner-Up** | AI in Education Hackathon |
| 🚔 **Top 36** | Kaaval AI Police Hackathon |
| 🤖 **Round 2** | Google Gen AI Hackathon |

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### ⚖️ [The Bench](https://github.com/Chan-dev12/F-and-O-project)
Three Gemini agents argue every trade. The **Decision Maker** proposes one, the **Betrayer** argues against it (including your own past losses), and the **Judge** says TAKE / WAIT / SKIP. Hard risk rules run in code first and can't be argued past. You can pause the debate mid-way to ask "what if" questions.

`LangGraph` `FastAPI` `Next.js` `Gemini` `Postgres`

</td>
<td width="50%" valign="top">

### ⏳ [Sabr](https://github.com/Chan-dev12/Sabr)
An agent that recovers failed UPI AutoPay debits. It works out *why* each one failed and retries when the payer actually has money, within NPCI's 4-attempt and pre-debit-notice rules.
**78.5% recovered vs 56.6% for a fixed retry ladder, with 40% fewer presentments.** Covered by 92 tests.

`Python` `Agents` `Payments` · *Razorpay AI Buildathon*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📐 [Calipers](https://github.com/Chan-dev12/Calipers)
RAG built from scratch, plus an evaluation harness that shows which design choices helped. No LangChain, no vector DB, two pip packages. Hybrid BM25 + dense retrieval lifted **NDCG@10 from 0.558 to 0.695**, reported with bootstrap CIs against a human-verified answer key.

`Python` `NumPy` `Ollama` `IR metrics`

</td>
<td width="50%" valign="top">

### 🦺 [RT-DETR PPE Vision API](https://github.com/Chan-dev12/rtdetr-vision-api)
RT-DETR-L fine-tuned on SH17 to detect helmets, vests, gloves and people. It answers questions like *"Is anyone not wearing a helmet?"* through a hand-written reasoning layer where the LLM is never allowed to count.
**mAP50 0.781 · mAP50-95 0.560** on the held-out test split.

`PyTorch` `Ultralytics` `FastAPI` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧩 [Deep Agents](https://github.com/Chan-dev12/Deep_agents)
Multi-agent e-commerce support. A LangGraph supervisor sends each message to one or more of 7 department agents (Finance, Returns, Shipping and others). Each agent has its own scoped tools and answers from the real database.

`LangGraph` `FastAPI` `PostgreSQL + pgvector` `React`

</td>
<td width="50%" valign="top">

### 🎯 [AMYPO Content Engine](https://github.com/Chan-dev12/Ampyo-Hackathon)
A next-lesson recommender that explains each pick in plain English, plus a hallucination checker for AI-written explanations. **+43% Recall@5 over a popularity baseline, claim-level F1 0.975, p95 latency 5.5 ms**, all on CPU.

`LightGBM` `SHAP` `FastAPI` · *HackWithAMYPO 2026*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 [Assistant0](https://github.com/Chan-dev12/ai_agents_with_auth0)
A reference AI agent with Auth0 RBAC and fine-grained authorization. Sensitive tools are triggered by application logic, not by the model, which closes off a whole class of prompt-injection risk.

`LangGraph` `Auth0 FGA` `Ollama` `RAG`

</td>
<td width="50%" valign="top">

### 👁️ [EyeQ-DR-G](https://github.com/Chan-dev12/EyeQ-DR-G)
Detects diabetic retinopathy and glaucoma, and works as a clinical documentation agent that remembers each patient's history to track disease progression across visits.

`Deep Learning` `Agents` `Memory`

</td>
</tr>
</table>

<details>
<summary><b>More builds</b></summary>
<br>

- 🤟 [**SignLink**](https://github.com/Chan-dev12/NxtWave-X-Open-AI): text → Indian / American Sign Language animation pipeline (NxtWave × OpenAI)
- 🕵️ [**DeepFake-Detect**](https://github.com/Chan-dev12/Deep_fake): face cropping with MTCNN + CNN classifier + web app
- 📦 [**Asset Management**](https://github.com/Chan-dev12/Assest-Management): MERN app with JWT roles and a role-aware LangChain + Groq chatbot
- 🚦 **Adaptive AI Traffic Signal**: reinforcement learning + DeepSORT for signal timing
- 🧠 **SecureXam**: AI-powered online exam proctoring
- 🥬 **Perish Guard**: AI + IoT monitoring for perishable goods in transit

</details>

---

## 🛠️ Tech stack

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/tech-stack-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/tech-stack-light.svg">
    <img alt="Tech stack: Python, PyTorch, TensorFlow, OpenCV, scikit-learn, Ultralytics, NumPy, pandas, LangGraph, LangChain, Ollama, Gemini, Anthropic, MCP, Pydantic, FastAPI, PostgreSQL, MongoDB, Node.js, Express, SQLAlchemy, Auth0, React, Next.js, Tailwind, Vite, Docker, Vercel, Render, GitHub Actions, Git" src="./assets/tech-stack-dark.svg" width="100%">
  </picture>
</p>

---

## 📊 GitHub activity

<p align="center">
  <img height="170" alt="GitHub stats" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Chan-dev12&theme=tokyonight" />
  <img height="170" alt="GitHub streak" src="https://streak-stats.demolab.com?user=Chan-dev12&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Chan-dev12/Chan-dev12/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Chan-dev12/Chan-dev12/output/github-contribution-grid-snake.svg">
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/Chan-dev12/Chan-dev12/output/github-contribution-grid-snake.svg">
  </picture>
</p>

---

<p align="center">
  <i>Always up for a hackathon team or a hard AI problem. Reach out on LinkedIn or by email.</i>
</p>
