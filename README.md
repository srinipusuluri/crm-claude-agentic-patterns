# 🤖 CRM Claude Agentic Patterns

> A visual, interactive guide mapping Claude AI agentic patterns to real-world CRM workflows — with use cases, implementation flows, and integration targets.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-7c3aed?style=for-the-badge&logo=github)](https://srinipusuluri.github.io/crm-claude-agentic-patterns/)
[![Built with Claude](https://img.shields.io/badge/Built%20with-Claude%20AI-c084fc?style=for-the-badge)](https://claude.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)

---

## 📖 Overview

This project demonstrates how **8 major Claude agentic patterns** can be applied across the full CRM lifecycle — from lead capture to customer retention. Each use case includes:

- **Pattern** — which agentic framework to use and why
- **Flow diagram** — step-by-step visual of how the agent operates
- **Implementation details** — signals, reasoning logic, and data sources
- **Integration targets** — real CRM/sales tools to connect

---

## 🗂️ Project Structure

```
crm-claude-agentic-patterns/
├── docs/
│   └── index.html          # Interactive single-page guide (GitHub Pages)
├── README.md               # This file
└── LICENSE
```

---

## 🎯 Use Cases Covered

| # | Use Case | Pattern | CRM Domain |
|---|----------|---------|------------|
| 1 | Intelligent Lead Scoring | ⚙️ ReAct | Sales |
| 2 | Personalized Outreach Drafting | 🔄 Reflection | Sales |
| 3 | Support Ticket Triage & Routing | 🚦 Routing | Support |
| 4 | Deal & Account Intelligence | 📚 RAG | Sales · Analytics |
| 5 | Churn Risk Detection & Response | 🕸️ Multi-Agent | Analytics · Ops |
| 6 | Hyper-Personalized Campaigns | ⚡ Parallelization | Marketing |
| 7 | Automatic CRM Data Entry | 🔧 Tool Use | Ops · Sales |
| 8 | Pipeline & Forecast Analysis | 🧠 Chain-of-Thought | Analytics |
| 9 | Contract & Proposal Generation | 🗺️ Planning | Ops |
| 10 | Escalation & Refund Approvals | 👤 Human-in-the-Loop | Support · Ops |
| 11 | Competitive Battle Card Generation | 🔗 Prompt Chaining | Sales · Marketing |
| 12 | 360° Prospect Research Agent | 🕸️ Multi-Agent + ReAct | Sales · Analytics |

---

## 🧠 Agentic Patterns Reference

### ⚙️ ReAct (Reason + Act)
Interleaves reasoning steps with tool calls. Best for tasks requiring live data lookups where each action depends on the previous observation.

### 🔄 Reflection / Self-Critique
Claude generates output, critiques it against quality criteria, and revises. Best for content quality where first drafts are never good enough.

### 🚦 Routing
A classifier dispatches requests to specialized handlers. Best for high-volume, heterogeneous input streams (e.g. support tickets).

### 📚 RAG (Retrieval-Augmented Generation)
Retrieves relevant documents at runtime before generating. Best for knowledge-intensive tasks over dynamic, large corpora.

### 🕸️ Multi-Agent
Specialized agents collaborate under an orchestrator. Best for long-horizon tasks that benefit from parallel specialized reasoning.

### ⚡ Parallelization
Runs independent subtasks simultaneously. Best for volume workloads where tasks don't depend on each other.

### 🔧 Tool Use / Function Calling
Claude calls typed external APIs directly. Best for structured read/write operations against CRM systems.

### 🧠 Chain-of-Thought
Step-by-step explicit reasoning before answering. Best for analytical tasks where the reasoning trail matters as much as the answer.

### 🗺️ Planning
Decompose goal into ordered steps, then execute. Best for complex, multi-stage workflows like document generation.

### 👤 Human-in-the-Loop (HITL)
Agent pauses at checkpoints for human approval. Best for irreversible, high-stakes, or financially significant actions.

### 🔗 Prompt Chaining
Sequential, deterministic prompt pipeline. Best for structured transformations where each stage has a clear, focused job.

---

## 🚀 Getting Started

### View the Live Guide
👉 **[https://srinipusuluri.github.io/crm-claude-agentic-patterns/](https://srinipusuluri.github.io/crm-claude-agentic-patterns/)**

### Run Locally
```bash
git clone https://github.com/srinipusuluri/crm-claude-agentic-patterns.git
cd crm-claude-agentic-patterns
open docs/index.html
```
No dependencies. Pure HTML/CSS/JS — opens directly in any browser.

---

## 🔌 CRM Integrations Referenced

| Category | Tools |
|----------|-------|
| **CRM Platforms** | Salesforce, HubSpot, Zoho CRM |
| **Sales Engagement** | Outreach, Salesloft, Apollo |
| **Support** | Zendesk, Intercom, Freshdesk |
| **Call Intelligence** | Gong, Chorus |
| **Marketing** | Marketo, Braze, Iterable, HubSpot Marketing |
| **Data Enrichment** | Clearbit, ZoomInfo, Crunchbase |
| **Vector / Memory** | Pinecone, pgvector |
| **Payments / Legal** | Stripe, DocuSign, Ironclad |
| **Analytics** | Mixpanel, Segment, Clari, Tableau |

---

## 🛠️ Built With

- **[Claude AI](https://claude.ai)** — Anthropic's AI assistant (Sonnet 4.6)
- **HTML / CSS / JavaScript** — zero-dependency single-page app
- **GitHub Pages** — free static hosting

---

## 📄 License

MIT © [Srini Pusuluri](https://github.com/srinipusuluri)

---

## 🙌 Contributing

Pull requests welcome! If you have a new CRM use case + agentic pattern mapping, open a PR with:
1. Use case description
2. Pattern choice rationale
3. Flow diagram (text or image)
4. Integration targets
