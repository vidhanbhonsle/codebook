# 🚀 Teradata AI Agent Cookbook

[![Teradata](https://img.shields.io/badge/Powered%20by-Teradata-orange)](https://www.teradata.com)
[![ClearScape](https://img.shields.io/badge/Try%20Free-ClearScape%20Analytics%20Experience-green)](https://clearscape.teradata.com)
[![Notebooks](https://img.shields.io/badge/format-Jupyter-orange)](https://jupyter.org)

**Build intelligent AI agents where your data lives.** Code recipes from beginner to advanced, import directly into ClearScape Analytics Experience and start building in minutes.

---

## 📚 Recipe Collection

| # | Recipe | Difficulty | Source | Import |
|---|--------|-----------|--------|--------|
| 1 | **Simple Data AI Agent** | ⭐ Beginner | GitHub | [📓 Import](https://raw.githubusercontent.com/vidhanbhonsle/codebook/refs/heads/main/recipes/01-simple-data-agent.ipynb) |
| 2 | **Energy Analytics Agent** | ⭐ Beginner | GitHub | [📓 Import](https://raw.githubusercontent.com/vidhanbhonsle/codebook/refs/heads/main/recipes/02-energy-analytics-agent.ipynb) |
| 3 | **Multi-Agent Customer Journey** | ⭐⭐ Intermediate | GitHub | [📓 Import](https://raw.githubusercontent.com/vidhanbhonsle/codebook/refs/heads/main/recipes/03-multi-agent-customer-journey) |
| 4 | **No-Code Data Agent** | ⭐⭐ Intermediate | ClearScape Analytics Experience | See [path below](#recipes-4-7-pre-installed-in-clearscape-analytics-experience) |
| 5 | **Customer Lifetime Value Agent** | ⭐⭐ Intermediate | ClearScape Analytics Experience | See [path below](#recipes-4-7-pre-installed-in-clearscape-analytics-experience) |
| 6 | **LangChain SQL Agent (Gemini)** | ⭐⭐⭐ Advanced | ClearScape Analytics Experience | See [path below](#recipes-4-7-pre-installed-in-clearscape-analytics-experience) |
| 7 | **LangChain SQL Agent (Bedrock)** | ⭐⭐⭐ Advanced | ClearScape Analytics Experience | See [path below](#recipes-4-7-pre-installed-in-clearscape-analytics-experience) |

---

## ⚡ Quick Start (ClearScape Analytics Experience)

### Step 0 — Sign up (first time only)
1. Create a free account at [clearscape.teradata.com](https://clearscape.teradata.com)
2. Log in to the ClearScape Analytics Experience dashboard

### Step 1 — Launch Jupyter
1. **Create an environment** in the dashboard  
2. **Jot down your password** (needed to connect to the database)
3. Click **Run Demos** to launch Jupyter Notebook environment

### Step 2 — Open a recipe notebook

#### Recipes 1-3 (from GitHub)
1. In Jupyter, navigate to **UseCases/**
2. Create a new folder named **`cookbook`**
3. Open `UseCases/cookbook/`
4. Go to **File → Open from URL**
5. Paste the notebook URL from the table above
6. **Run All** cells 🎉

#### Recipes 4-7 (pre-installed in ClearScape Analytics Experience)
These notebooks are already in your environment, just navigate to:

| Recipe | Path |
|--------|------|
| #4 No-Code Data Agent | `VantageCloud_Lake/Getting_Started/Teradata_AgentBuilder/Teradata_AgentBuilder_Getting_Started.ipynb` |
| #5 CLV Agent | `VantageCloud_Lake/UseCases/Customer_Lifetime_Value_Agent/Customer_Lifetime_Value_Agents.ipynb` |
| #6 LangChain (Gemini) | `UseCases/Data_Analyst_AI_Agent_Gemini/Data_Analyst_AI_Agent_Gemini.ipynb` |
| #7 LangChain (Bedrock) | `UseCases/Generative_Question_Answering_GenAI_Bedrock/AWS_Bedrock_LangChain_Text_to_SQL.ipynb` |

---

## 🎯 What You'll Build

### Recipe 1: Simple Data AI Agent
```python
# OpenAI function calling + Teradata SQL
response = agent.ask("What month had the most orders?")
# → "September, with 902 orders"
```

### Recipe 2: Energy Analytics Agent
```python
# Google ADK agent with Gemini
await call_agent_async("Show me energy spikes in March")
# → Summary stats, anomalies, recommendations
```

### Recipe 3: Multi-Agent Customer Journey
```python
# Three specialized agents collaborating
await analyze_customer_journey("Why do customers cancel?")
# QueryParser → DataAnalyst → Strategist → Insights
```

### Recipe 4: No-Code Data Agent
Build AI agents **visually** using Flowise + Teradata MCP Server — no Python required.

### Recipe 5: Customer Lifetime Value Agent
Four specialized agents (Explorer, Insights, Strategist, Visualizer) working together for CLV analysis.

### Recipe 6-7: LangChain SQL Agents
Text-to-SQL with **LangChain** framework — choose Google Gemini or Amazon Bedrock as your LLM.

---

## 🛠️ Technologies Covered

| Recipe | LLM | Framework | Key Teradata Feature |
|--------|-----|-----------|---------------------|
| #1 | OpenAI GPT-4o | OpenAI SDK | teradatasql, DBC catalog |
| #2 | Google Gemini | Google ADK | teradataml |
| #3 | Google Gemini | Google ADK | nPath, Sessionize |
| #4 | Any (via LiteLLM) | Flowise | MCP Server |
| #5 | Any (via LiteLLM) | Flowise | MCP Server, visualization |
| #6 | Google Gemini | LangChain | SQLDatabase |
| #7 | Amazon Bedrock | LangChain | SQLDatabase |

---

## 📖 Complete Cookbook

Download the full PDF guide with detailed explanations, architecture diagrams, and pro tips:

📘 **[Download Complete Cookbook (PDF)](cookbook/ai_agent_cookbook.pdf)**

---

## 📊 Why Build Agents on Teradata?

| Traditional Approach | With AI Agents on Teradata |
|---------------------|---------------------------|
| Write complex SQL queries | Ask questions in English |
| Move data to AI platforms | Process data where it lives |
| Wait hours for analysis | Get insights in seconds |
| Separate AI infrastructure | In-database intelligence |

---

## 🏭 Industry Applications

- **🏦 Financial Services:** CLV analysis, churn prediction, fraud detection
- **🏥 Healthcare:** Patient risk scoring, readmission prevention  
- **🏭 Manufacturing:** Predictive maintenance, quality control
- **📡 Telecom:** Network optimization, customer journey analysis
- **⚡ Energy:** Consumption analytics, efficiency optimization

---

## 📁 Repository Structure

```
teradata-ai-agent-cookbook/
├── README.md
├── recipes/
│   ├── 01-simple-data-agent.ipynb           # OpenAI
│   ├── 02-energy-analytics-agent.ipynb      # Google ADK + Gemini
│   └── 03-multi-agent-customer-journey.ipynb # Multi-agent + nPath
├── cookbook/
│   └── ai_agent_cookbook.pdf                # Complete PDF guide
```

> **Note:** Recipes 4-7 are available directly in ClearScape Analytics Experience (see paths above).

---

## 🔑 API Keys

| Recipe | Required Keys |
|--------|--------------|
| #1 | OpenAI API key |
| #2, #3 | Google Gemini API key ([get free](https://aistudio.google.com)) |
| #4, #5 | Configured in ClearScape Analytics Experience (LiteLLM) |
| #6 | Google Gemini API key |
| #7 | AWS credentials + Bedrock access |

---

## ❓ FAQ

**Q: Do I need to pay for ClearScape Analytics Experience?**  
A: No! ClearScape Analytics Experience is free and perfect for these recipes.

**Q: Can I use these in production?**  
A: Yes! The same code scales to Teradata Vantage Enterprise.

**Q: How do I import notebooks from URLs?**  
A: In Jupyter: **File → Open from URL** → paste the raw GitHub URL → Done!

---

## 💬 Get Help

- 📧 **Email**: _____@teradata.com

---

## ⭐ Star This Repo!

If you find these recipes helpful, please star this repository to help others discover it!

---

## 📄 License

Apache 2.0 - See [LICENSE](LICENSE) for details.

---

<div align="center">
  
**Built with ❤️ by Teradata Developer Relations Team**

[Try Free](https://clearscape.teradata.com) • [Teradata.com](https://www.teradata.com) • [Developer Portal](https://developers.teradata.com) • [Blog](https://medium.com/teradata)

</div>
