<p align="center">
  <a href="https://shreyansigheware.github.io"><img src="https://img.shields.io/badge/Site-shreyansigheware.github.io-4285F4?style=for-the-badge&logo=githubpages&logoColor=white" alt="Site"/></a>
  <a href="https://github.com/brainupgrade-in"><img src="https://img.shields.io/badge/Team-Brain%20Upgrade-EA4335?style=for-the-badge&logo=github&logoColor=white" alt="Brain Upgrade"/></a>
  <a href="https://www.linkedin.com/in/shreyansigheware"><img src="https://img.shields.io/badge/LinkedIn-shreyansigheware-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.upwork.com/freelancers/~01e1aacb61f14c318a"><img src="https://img.shields.io/badge/Upwork-Hire%20me-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"/></a>
</p>

---

### 👋 Hi, I'm Shreyansi Gheware

I build **LLM applications that answer from your own data**: RAG systems that cite the source behind every answer,
agents that hand off to a human when they should, and the **evaluation sets** that prove they still work after each change.

I'm part of the **[Brain Upgrade](https://github.com/brainupgrade-in)** team in Bengaluru, which builds production agentic AI
and runs a Kubernetes lab platform for engineers learning it.

- 🧪 I provision and support the **Kubernetes and agentic AI lab sandboxes** (AWS EKS, and local model inference on an NVIDIA DGX Spark)
- 📏 I build **evaluation sets**: real inputs scored before and after every change
- 💸 I built the **LLM token-economics dashboard** (Grafana) that tracks tokens and spend per learner
- 🛠️ Six years of hands-on technical work, from GPS device setup (2020) to LLM apps (now)

My rule: an answer the system can't trace to a source isn't an answer.

---

## 🤖 Projects I work on

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [FrontDesk AI](https://github.com/brainupgrade-in/aiagentic-comp-frontdeskai)
**A multi-agent employee support desk, grounded in RAG**

Leave, tickets, expense claims and payslips. A supervisor routes each request to HR, IT, finance or facilities agents, and answers are grounded in a **ChromaDB** vector store so the model doesn't invent policy. It is the reference app for our agentic AI course, deployed per participant on Kubernetes.

🧩 **Pattern:** supervisor plus specialist agents, with retrieval grounding.

`FastAPI` `LangGraph` `LiteLLM` `ChromaDB` `SQLite` `Kubernetes`

</td>
<td width="50%" valign="top">

### 🍛 [ThaliScan / Glucoray](https://thaliscan.glucoray.com)
**AI food scanning that never invents a number**

Photograph a meal and get its carbs. Every answer shows the matched food-table row and its source. I built its **Telegram webhook**, work on the LLM agent and build its **evaluation sets**.

🧩 **Pattern:** data-grounded answers. The table supplies the numbers and the LLM explains them.

`FastAPI` `SQLAlchemy` `Claude API` `Docker Compose` `Telegram`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧭 [AgentGrow](https://agentgrow.io)
**AI agents for a business, with a human approving every message**

Agents draft marketing content, run outreach and report to the owner. Answers are grounded in the business's own content through **ChromaDB**, and each answer links back to the record it came from.

🧩 **Pattern:** retrieval-grounded agents with human-in-the-loop approval.

`LLM agents` `ChromaDB` `RAG`

</td>
<td width="50%" valign="top">

### 👁️ [Nazar AI](https://nazarai.gheware-ai.com)
**Can a phone and a lens a doctor already owns screen for retinopathy?**

A smartphone camera held to a 20-dioptre condensing lens, and whether that image is good enough for a vision-language model to flag retinopathy. The pairing costs a fraction of a fundus camera. A research prototype: no clinical claims.

🧩 **Pattern:** vision-language model on low-cost capture.

`Vision-language models` `PWA`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☸️ [Cloud Labs](https://devops.gheware.com/training/cloud-labs.html)
**Live Kubernetes and agentic AI sandboxes in the browser**

A secure browser terminal onto a live cluster, with gamified deploy objectives. I provision the sandboxes and support live cohorts.

`Kubernetes` `Docker` `AWS EKS / EC2` `k3s`

</td>
<td width="50%" valign="top">

### 🏁 [Hackboard](https://shreyansigheware.github.io/hackboard/)
**Every hackathon this month, filterable to the ones you can enter**

Refreshed daily by a scheduled GitHub Actions job. [Code](https://github.com/shreyansigheware/hackboard).

`Python` `TypeScript` `GitHub Actions`

</td>
</tr>
</table>

More from the team: [agentic-ai-book-examples](https://github.com/brainupgrade-in/agentic-ai-book-examples) (100+ runnable LangChain, LangGraph, RAG and MCP examples) · [aiagentic-comp](https://github.com/brainupgrade-in/aiagentic-comp) (5 days, 119 hands-on labs) · [the full Brain Upgrade portfolio](https://github.com/brainupgrade-in)

---

## 🧱 The stack I work in

| Layer | Tools |
|---|---|
| **🧠 Models** | <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/LiteLLM-gateway-6E56CF?style=flat-square"/> <img src="https://img.shields.io/badge/vLLM-DGX%20Spark-76B900?style=flat-square&logo=nvidia&logoColor=white"/> |
| **🕸️ Orchestration** | <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/> |
| **📚 Retrieval & data** | <img src="https://img.shields.io/badge/RAG-ChromaDB-FF6F00?style=flat-square"/> <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/> |
| **🔧 APIs** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Telegram-webhooks-26A5E4?style=flat-square&logo=telegram&logoColor=white"/> |
| **🛡️ Evals** | <img src="https://img.shields.io/badge/Eval%20sets-before%20%26%20after-8250DF?style=flat-square"/> <img src="https://img.shields.io/badge/Citations-every%20answer-2EA44F?style=flat-square"/> |
| **🔭 Observability** | <img src="https://img.shields.io/badge/Grafana-tokens%20%C2%B7%20cost-F46800?style=flat-square&logo=grafana&logoColor=white"/> |
| **☸️ Runtime** | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-EKS%20%C2%B7%20EC2-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> |

---

## 🔁 How I build a RAG system

| Step | In practice |
|---|---|
| **Ingest with metadata** | File, page or sheet and section on every chunk, so every answer can be cited |
| **Ground it** | Answer only from retrieved context, cite it, and say "not found in the documents" rather than guess |
| **Evaluate it** | A set of real questions scored for correct answer and correct citation, run before every release |
| **Ship it** | FastAPI endpoints in Docker, with tokens and cost on a dashboard |

---

<p align="center">
  <b>Need an LLM app that answers from your own documents?</b> <a href="https://www.upwork.com/freelancers/~01e1aacb61f14c318a">Hire me on Upwork</a>
</p>
