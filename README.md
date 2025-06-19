# 🧠 Built a real-time, context-aware AI agent using n8n as the orchestration tool, integrating OpenAI for language understanding and SerpAPI for real-time web data access

A cloud-hosted, context-aware AI agent that processes natural language prompts, fetches real-time search results, performs calculations, and retains memory — all orchestrated through **n8n's no-code workflow engine**.

---

## 🚀 Project Overview

Delivered a real-time, general-purpose AI Agent that goes beyond traditional LLM capabilities by combining:

* **OpenAI** for natural language understanding
* **SerpAPI** for real-time Google search
* **n8n** for no-code workflow orchestration

The agent can:

* Understand natural language prompts
* Fetch live web-based information
* Perform date and arithmetic calculations
* Retain user-specific context across prompts

---

## 🔍 Why SerpAPI?

OpenAI models are excellent at language reasoning but lack real-time awareness.
SerpAPI bridges that gap by:

* 🔎 Retrieving the latest web content and trends
* 🌐 Handling dynamic queries like “top AI startups 2025” or “latest React.js features”
* 📄 Returning structured results (title, link, snippet)
* 🧠 Supplying OpenAI with real-world context for better summarization

This transforms a static LLM into a **live, adaptive assistant**.

---

## 🧠 Agent Capabilities (One Prompt Example)

```
“Remember my deadline is August 2. Can you please show me the 2 latest React trends? Also, how many days are left until August 2? Additionally, if I offer a 12% discount on ₹18,500, what would be the final price?”
```

The agent will:

* 📌 Store the deadline using **Simple Memory**
* 🔍 Search Google via **SerpAPI**
* ✍️ Summarize results using **OpenAI**
* 🧮 Calculate date differences and math using **Calculator Node**
* 🧾 Return a context-aware, structured response

---

## 🛠️ Architecture Overview

* ⚙️ **n8n (cloud-hosted)** – Visual workflow automation
* 🧠 **OpenAI Chat Model** – Language understanding & generation
* 🌐 **SerpAPI** – Real-time Google Search API
* 🧷 **Simple Memory** – Stores persistent context
* 🧮 **Calculator Node** – Date/time and arithmetic logic

---

## 🎯 Use Case Applications

* 🔬 Real-time research assistants
* 💬 Prompt-based task bots
* 🛎️ Context-aware customer service agents
* 📅 Smart productivity tools
* 🤖 Chatbots with memory + live knowledge access

---

## ⚙️ Getting Started

1. Sign up at [n8n.cloud](https://n8n.io)
2. Import the workflow JSON into your workspace
3. Set up API credentials for OpenAI and SerpAPI
4. Trigger the chat via webhook or manual input
5. Test the agent with natural language prompts

---

## 🔐 Required API Keys

* **OpenAI API Key** – for GPT processing
* **SerpAPI Key** – for Google Search access

---

## 🤖 Author

**Chanchal Kumari** – [LinkedIn Post](https://www.linkedin.com/posts/chanchal-kumari-219aba335_openai-serpapi-n8n-activity-7341350604276953088-hdTc?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFRYx7UBK5hZk8wZseS4vYVgWgFZCllXc-w)

---

## 🏷️ Tags

`OpenAI` `n8n` `SerpAPI` `AI Agent` `Prompt Automation` `Workflow` `NoCode` `GPT`
