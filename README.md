<!-- ================= HEADER ================= -->

<h1 align="center">🚀 CrowdWisdom AI Outreach Automation</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=24&duration=2600&color=00F7FF&center=true&vCenter=true&width=900&lines=AI-Powered+Lead+Generation+Pipeline;MCP+%2B+n8n+%2B+OpenRouter+Automation;Production-Ready+Influencer+Outreach+System" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MCP-Antigravity-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LLM-OpenRouter-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge"/>
</p>

---

# 🧠 Project Overview

This project is an **end-to-end AI-powered lead generation and personalized outreach system** built for CrowdWisdomTrading.

The system automatically:

- 🔍 Discovers trading influencers (50K+ subscribers)  
- 🤖 Generates personalized outreach emails using AI  
- 📊 Stores and tracks leads  
- 🔗 Supports MCP-based triggering  
- ⚡ Runs on scalable n8n automation  

---

# 🎯 Business Objective

Identify high-quality trading influencers and generate **context-aware personalized outreach** to request platform feedback and potential collaboration.

---

# ⚙️ Tech Stack

### 🔧 Automation Layer
- n8n workflow automation  
- MCP (Antigravity bridge)  
- Webhook-based orchestration  

### 🔎 Lead Intelligence
- Tavily / Serper Search API  
- Lead extraction & filtering  
- Platform-based routing  

### 🤖 AI Layer
- OpenRouter LLM  
- Prompt-engineered personalization  
- Structured JSON output parsing  

### 💾 Data Layer
- n8n Data Tables  
- Lead lifecycle tracking  
- Execution logging  

---

# 🎬 Full Demo

👉 **Watch the complete walkthrough**

<p align="center">
  <a href="https://www.loom.com/share/bf14d1a93fc5432da76730518505086c">
    <img src="https://img.shields.io/badge/▶️%20Watch%20Demo-Loom-ff4c4c?style=for-the-badge"/>
  </a>
</p>

🔗 Direct Link:  
https://www.loom.com/share/bf14d1a93fc5432da76730518505086c

---

# 🎬 Animated System Architecture

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=2600&color=00F7FF&center=true&vCenter=true&width=900&lines=End-to-End+AI+Lead+Generation+Pipeline;MCP+→+n8n+→+AI+Outreach+Automation;Scalable+Production-Ready+Architecture" />
</p>

## 🧠 System Architecture (Production Flow)

flowchart LR

A[User / MCP Antigravity Form] --> B[n8n Webhook Trigger]

B --> C[Input Validation & Config]
C --> D[Tavily / Serper Lead Search]

D --> E[Extract & Normalize Leads]
E --> F{Leads Found?}

F -- Yes --> G[Process Each Lead]
F -- No --> Z[Log: No Leads Found]

G --> H[OpenRouter GPT Model]
H --> I[Generate Personalized Outreach]

I --> J[Save Lead to Data Table]
J --> K[Update Lead Status]

I --> L{LinkedIn Available?}
L -- Yes --> M[Send LinkedIn Connection]
L -- No --> N[Skip]

K --> O[Execution Logs]
M --> O
N --> O
Z --> O


---
# ✨ Core Features

✅ MCP → n8n real-time trigger  
✅ Multi-platform lead discovery  
✅ AI-personalized outreach generation  
✅ Structured JSON parsing  
✅ Lead status tracking  
✅ LinkedIn conditional routing  
✅ Failure-safe Tavily handling  
✅ Production-ready logging  

---

# 🧪 Sample AI Outreach

**Input Lead**

- Name: Raj Traders  
- Platform: YouTube  
- Subscribers: 120K  

**Generated Email**

> **Subject:** Loved your trading insights, quick feedback?  
>
> Hi Raj,  
>
> I came across your YouTube content on trading strategies — really liked your clear breakdown of market structure.  
>
> We’re building tools at CrowdWisdomTrading to help traders make better data-backed decisions, and I would genuinely value your expert feedback.  
>
> Would you be open to a quick look and sharing your thoughts?  
>
> Best regards,  
> CrowdWisdomTrading Team

---

# 🛡️ Error Handling Strategy

The system is designed to be **resilient in production environments**.

### 🚨 Tavily Failure Handling
- Detects empty or failed responses  
- Logs failure event  
- Prevents workflow crash  
- Gracefully exits lead loop  

### 🔄 AI Output Guardrails
- Structured JSON enforced  
- Output parser validation  
- Fallback handling enabled  

### 📉 No-Leads Scenario
- Conditional IF node  
- Status logged  
- Workflow completes safely  

---

# 📊 Lead Status Lifecycle

| Stage | Description |
|------|-------------|
| 🔍 discovered | Lead found via search |
| 🤖 email_generated | AI outreach created |
| 📩 ready_for_contact | Prepared for CRM |
| 🔗 linkedin_sent | Connection attempted |
| ✅ completed | Fully processed |

---

# 🚀 How to Run

1. Import the workflow JSON into n8n  
2. Configure API keys:
   - Tavily / Serper  
   - OpenRouter  
3. Activate the workflow  
4. Trigger via MCP form or webhook  
5. Monitor executions in n8n dashboard  

---

# 📁 Repository Structure
workflows/
├── CrowdWisdom Lead Generator.json
└── mcp workflow.json
README.md


---

# 🧠 Design Highlights

- Built with **modular node architecture**  
- Optimized for **low-latency lead processing**  
- Supports **horizontal scaling in n8n**  
- Clean separation of MCP and core pipeline  
- Recruiter-friendly observability  

---

# 🙌 Author

**Mayank Yadav**

- Automation & AI Workflow Developer  
- Focus: n8n • AI Agents • Growth Automation  

---

# ⭐ If you found this interesting

Consider giving the repo a star — it helps a lot!

---



