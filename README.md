<div align="center">

<img src="https://avatars.githubusercontent.com/u/270877885?v=4" alt="ELITEA Logo" width="120" />

# ELITEA – AI That Works the Way You Do

**Build intelligent agents. Automate complex workflows. Chat with AI that actually understands your work.**

[![Website](https://img.shields.io/badge/Website-elitea.ai-blue?style=flat-square)](https://elitea.ai)
[![Documentation](https://img.shields.io/badge/Docs-elitea.ai/docs-blue?style=flat-square)](https://elitea.ai/docs)
[![Issues](https://img.shields.io/github/issues/EliteaAI/elitea_issues?style=flat-square&label=Community%20Issues)](https://github.com/EliteaAI/elitea_issues)
[![SDK](https://img.shields.io/badge/SDK-Python-green?style=flat-square)](https://github.com/EliteaAI/elitea-sdk)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](https://www.apache.org/licenses/LICENSE-2.0)

</div>

---

## What is ELITEA?

ELITEA is an enterprise AI platform that puts powerful generative AI capabilities directly into your team's hands — without the complexity. It gives you a single workspace to build AI agents, design automated pipelines, chat with your data, and connect your favorite tools.

Whether you're a developer, analyst, or product manager, ELITEA helps you offload routine tasks to intelligent assistants and focus on what matters: creativity and results.

---

## ✨ Key Features

### 🤖 Agents
Build virtual AI assistants tailored to specific tasks. Combine instructions, external toolkits (Jira, GitHub, Confluence, Slack, and 60+ more), and language models to create digital teammates that take action — not just answer questions.

### 🔗 Pipelines
Design visual, automated workflows that connect agents, decisions, and integrations. From data processing to multi-step approvals, pipelines bring consistency and efficiency to your most complex processes.

### 💬 Chat
A natural conversational interface that brings together your agents, pipelines, and language models. Ask complex questions, trigger workflows, and get results — all in one place.

### 📦 Artifacts
Shared, temporary storage for your workflows. Agents can create, read, update, and delete text-based files — preserving context and passing information between steps seamlessly.

### 🔑 Credentials
Centrally store and manage API keys, tokens, and sensitive authentication data. Securely reuse credentials across agents and pipelines without ever exposing them in your configurations.

### 🧰 Toolkits
Extend what your agents can do. Connect to external services, create custom tool configurations, and integrate ELITEA into the systems your team already uses.

### 🔍 Indexing
Turn your documents, repositories, and knowledge sources into searchable indexes. Give agents grounded, factual context using semantic search — so they work with your data, not just their training.

### 🌐 MCPs
Connect ELITEA to local or remote MCP servers to bring additional tools and real-time context into your agents and pipelines. Supports both on-machine and hosted MCP integrations.

### 🤝 Community
Share what you've built. Publish agents, pipelines, and toolkits to the ELITEA community — or discover and reuse what others have created. Collaboration is built in.

---

## 🗂️ Repository Overview

| Repository | Description | Language |
|---|---|---|
| [EliteaUI](https://github.com/EliteaAI/EliteaUI) | React-based web application — the main ELITEA user interface | JavaScript |
| [elitea-sdk](https://github.com/EliteaAI/elitea-sdk) | Python SDK for building agents & integrating 60+ toolkits | Python |
| [elitea_core](https://github.com/EliteaAI/elitea_core) | Core platform plugin with platform-level functionality | Python |
| [elitea.github.io](https://github.com/EliteaAI/elitea.github.io) | Landing page & full documentation site | TypeScript |
| [elitea_issues](https://github.com/EliteaAI/elitea_issues) | Community issue tracker — report bugs & request features | — |
| [bootstrap](https://github.com/EliteaAI/bootstrap) | Platform bootstrap & deployment tooling | Python |
| [indexer_worker](https://github.com/EliteaAI/indexer_worker) | Document and code indexing worker service | Python |
| [runtime_engine_litellm](https://github.com/EliteaAI/runtime_engine_litellm) | LLM runtime engine based on LiteLLM | Python |
| [tracing](https://github.com/EliteaAI/tracing) | Observability and tracing for platform services | Python |
| [pylon](https://github.com/EliteaAI/pylon) | Platform gateway and routing layer | Python |

---

## 🚀 Getting Started

### Use the Platform
> The fastest way to get started — no installation required.

1. Visit [elitea.ai](https://elitea.ai) and sign up
2. Create your first Agent with a system prompt and a toolkit
3. Chat with it, or wire it into a Pipeline

### Use the SDK (Developers)
```bash
pip install elitea-sdk
```

Build and run agents locally using the Python SDK with LangGraph-based orchestration and 60+ pre-built toolkits:

```python
from elitea_sdk.runtime.langchain import Assistant

agent = Assistant(config={...})
response = agent.invoke({"input": "Create a Jira ticket for the login bug"})
```

📖 [SDK Documentation →](https://github.com/EliteaAI/elitea-sdk)

---

## 📚 Resources

| Resource | Link |
|---|---|
| 🌐 Website | [elitea.ai](https://elitea.ai) |
| 📘 Full Documentation | [elitea.ai/docs](https://elitea.ai/docs) |
| 🐛 Bug Reports & Feature Requests | [elitea_issues](https://github.com/EliteaAI/elitea_issues/issues) |
| 💬 Community Discussions | [GitHub Discussions](https://github.com/EliteaAI/elitea_issues/discussions) |

---

## 🐛 Found a Bug or Have an Idea?

We actively track bugs, feature requests, and community feedback through our public issue tracker.

👉 **[Browse open issues](https://github.com/EliteaAI/elitea_issues/issues)** — see what's being worked on, vote on features, or open a new one.

---

## 📄 License

Most ELITEA repositories are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
See individual repositories for specific license details.

---

<div align="center">

Built with ❤️ by the ELITEA team &nbsp;|&nbsp; [elitea.ai](https://elitea.ai) &nbsp;|&nbsp; [Docs](https://elitea.ai/docs) &nbsp;|&nbsp; [Issues](https://github.com/EliteaAI/elitea_issues)

</div>
