# ⚡ n8n AI Workflows Collection

> **Author:** [Vinit Metange](https://www.linkedin.com/in/vinit-metange/) | AI Product Leader

[![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-orange)](https://n8n.io) [![AI](https://img.shields.io/badge/AI-Agents%20%7C%20RAG%20%7C%20LLMs-blue)](https://n8n.io/workflows/categories/ai/) [![Practice](https://img.shields.io/badge/Type-Practice_Projects-green)]()

---

## 📚 About This Repository

A hands-on collection of **n8n automation workflows** for AI agents, RAG pipelines, customer support bots, and enterprise automations. Built as practice projects to explore no-code/low-code AI orchestration alongside Python-based agentic systems.

> *Companion to my Python AI agent projects — same patterns, different implementation paradigm.*

---

## 🤖 AI Agent Workflows

| Workflow | Description | Tools Used |
|----------|-------------|------------|
| `ai-research-agent.json` | Automated web research + summarization agent | GPT-4o, Brave Search, Google Sheets |
| `rag-document-qa-bot.json` | RAG chatbot for document Q&A | OpenAI, Pinecone, Google Drive |
| `multi-agent-task-router.json` | Routes tasks to specialized sub-agents | GPT-4o, LangChain nodes |
| `llm-eval-pipeline.json` | Automated LLM response evaluation workflow | OpenAI, Airtable |
| `ai-content-generator.json` | AI-powered blog/LinkedIn post generator | GPT-4o, WordPress, LinkedIn |

---

## 📊 Business Automation Workflows

| Workflow | Description | Tools Used |
|----------|-------------|------------|
| `crm-lead-enrichment.json` | Auto-enrich leads with AI scoring | HubSpot, OpenAI, Clearbit |
| `email-triage-agent.json` | AI email categorization and auto-responder | Gmail, GPT-4o |
| `slack-support-bot.json` | Intelligent Slack support bot with RAG | Slack, OpenAI, Notion |
| `hr-resume-screener.json` | AI-powered resume screening workflow | Gmail, OpenAI, Airtable |
| `social-media-scheduler.json` | AI content repurposing and scheduling | OpenAI, Buffer, LinkedIn |

---

## 🔗 Data & Integration Workflows

| Workflow | Description | Tools Used |
|----------|-------------|------------|
| `pdf-extractor-pipeline.json` | Extract and structure data from PDFs | OpenAI, Google Drive, Sheets |
| `whatsapp-ai-chatbot.json` | WhatsApp business chatbot with AI | WhatsApp, OpenAI, PostgreSQL |
| `vector-db-ingestion.json` | Automated document ingestion to vector DB | Pinecone, OpenAI, Dropbox |
| `market-research-agent.json` | Automated competitor and market analysis | Brave Search, GPT-4o, Notion |

---

## 🚀 Getting Started with n8n

```bash
# Self-hosted option
npx n8n

# Or use n8n Cloud
# Visit: https://app.n8n.cloud
```

### Import a Workflow
1. Open n8n editor
2. Click **Import** > **From File**
3. Select any `.json` workflow from this repo
4. Configure your API credentials
5. Activate the workflow

---

## 📁 Repository Structure

```
n8n-ai-workflows-collection/
├── ai-agents/
│   ├── ai-research-agent.json
│   ├── rag-document-qa-bot.json
│   └── multi-agent-task-router.json
├── business-automation/
│   ├── crm-lead-enrichment.json
│   ├── email-triage-agent.json
│   └── slack-support-bot.json
├── data-integration/
│   ├── pdf-extractor-pipeline.json
│   └── vector-db-ingestion.json
├── templates/
│   └── base-ai-agent-template.json
└── README.md
```

---

## 💡 Learning Resources

- [n8n Official Docs](https://docs.n8n.io)
- [n8n Community Workflows](https://n8n.io/workflows/)
- [n8n AI Workflows Guide](https://docs.n8n.io/advanced-ai/)
- [OpenAI API Docs](https://platform.openai.com/docs)

---

## 🔗 Related Projects

- [agentic-ai-context-engineering](https://github.com/VinitMetange/agentic-ai-context-engineering) — Python-based agentic AI patterns
- [rag-knowledge-assistant](https://github.com/VinitMetange/rag-knowledge-assistant) — Production RAG system
- [GenAI_Agents](https://github.com/VinitMetange/GenAI_Agents) — Forked GenAI agent tutorials

---

> *These workflows are practice implementations. Inspired by the n8n community and adapted for enterprise AI use cases.*
