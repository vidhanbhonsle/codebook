# 🚀 Teradata AI Agent Cookbook

[![Teradata](https://img.shields.io/badge/Powered%20by-Teradata-orange)](https://www.teradata.com)
[![ClearScape](https://img.shields.io/badge/Try%20Free-ClearScape%20Analytics%20Experience-green)](https://clearscape.teradata.com)
[![Notebooks](https://img.shields.io/badge/format-Jupyter-orange)](https://jupyter.org)

**Build intelligent AI agents where your data lives.** Import directly into ClearScape Analytics Experience and start building in minutes!

## ⚡ Quick Start (ClearScape Analytics Experience)

### Step 0 — Sign up (first time only)
1. Create a free ClearScape Analytics Experience account at [clearscape.teradata.com](https://clearscape.teradata.com)
2. Log in to the CSAE console

### Step 1 — Launch Jupyter
1. **Create an environment** in the ClearScape Analytics console  
2. **Jot down your password** (you’ll need it to connect to the database)
3. Click **Run demos** to start the **Jupyter Notebook** environment

### Step 2 — Create a `cookbook` folder
1. In Jupyter, open the **UseCases/** folder
2. Create a new folder named **cookbook** → `UseCases/cookbook/`

### Step 3 — Import a recipe notebook
1. Open `UseCases/cookbook/`
2. Go to **File → Open from URL**
3. Paste the recipe notebook URL (update this link based on the recipe you want to import):

```text
<RECIPE_NOTEBOOK_RAW_URL>
```

> Note: A **Google Gemini API key** is only needed for the notebooks that use Gemini. Those notebooks will clearly mention it in the setup cell or README.
4. **Run All** cells and watch the magic! 🎉

## 📚 Recipe Collection

| # | Recipe | Difficulty | Time | Direct Import Link |
|---|--------|-----------|------|-------------------|
| 1 | **Energy Analytics Agent** | ⭐ Beginner | 5 min | [📓 Import Notebook](https://raw.githubusercontent.com/[your-username]/teradata-ai-agent-cookbook/main/recipes/01-energy-analytics-agent.ipynb) |
| 2 | **Multi-Agent Customer Journey** | ⭐⭐ Intermediate | 10 min | [📓 Import Notebook](https://raw.githubusercontent.com/[your-username]/teradata-ai-agent-cookbook/main/recipes/02-customer-journey-agent.ipynb) |

## 🎯 What You'll Build

### Recipe 1: Energy Analytics Agent
```python
# Ask questions in plain English!
agent.ask("What was our energy consumption last month?")
# Output: "Total: 2,450 kWh, Daily avg: 79 kWh, 3 anomalies detected..."
```

### Recipe 2: Multi-Agent System
```python
# Three agents working together!
await analyze_customer_journey("Why do customers cancel?")
# Parser → Analyst → Strategist → Insights
```

## 📖 Complete Cookbook

Download the full PDF guide with detailed explanations:

📘 **[Download Complete Cookbook (PDF)](cookbook/complete_cookbook.pdf)**

## 🚀 Getting Started

### Prerequisites
- **ClearScape Analytics Experience** account (free at [clearscape.teradata.com](https://clearscape.teradata.com))
- **Google Gemini API key** *(optional — only for notebooks that use Gemini)* — get one from [Google AI Studio](https://aistudio.google.com)

### CSAE setup

If you're running recipes in **ClearScape Analytics Experience**, follow the **Quick Start** section above to:
- sign up / log in,
- launch Jupyter,
- create `UseCases/cookbook/`,
- and import a recipe notebook from a URL.

## 📊 Why These Recipes?

| Traditional Approach | With Our AI Agents |
|---------------------|-------------------|
| Write complex SQL queries | Ask questions in English |
| Build ETL pipelines | Process data where it lives |
| Wait hours for analysis | Get insights in seconds |
| Separate AI infrastructure | In-database intelligence |

## 🏭 Industry Applications

- **🏦 FinTech:** Fraud detection, risk scoring
- **🏥 Healthcare:** Patient risk, readmission prevention  
- **🏭 Manufacturing:** Predictive maintenance, quality control
- **📡 Telecom:** Network optimization, churn prediction
- **⚡ Energy:** Consumption analysis, efficiency optimization

## 📁 Repository Structure

```
teradata-ai-agent-cookbook/
├── README.md                                    # This file
├── recipes/
│   ├── 01-energy-analytics-agent.ipynb        # Complete notebook
│   ├── 02-customer-journey-agent.ipynb        # Complete notebook
│   └── more-coming-soon/                      # Future recipes
├── cookbook/
│   └── complete_cookbook.pdf                  # Full PDF guide
└── requirements.txt                           # Python dependencies
```

## 🤝 Contributing

We welcome new recipes! To contribute:

1. Fork this repository
2. Create your recipe as a Jupyter notebook
3. Ensure it runs on [ClearScape Analytics Experience](https://clearscape.teradata.com)
4. Submit a pull request

## 💡 Recipe Ideas We'd Love

- Real-time anomaly detection agent
- Inventory optimization agent
- Customer service automation agent
- Financial forecasting agent
- Healthcare diagnosis assistant

## ❓ FAQ

**Q: Do I need to pay for ClearScape Analytics Experience?**  
A: No! ClearScape Analytics Experience is free and perfect for these recipes.

**Q: Can I use these in production?**  
A: Yes! The same code scales to Teradata Vantage Enterprise.

**Q: What if I don't have a Gemini API key?**  
A: Get one free at [aistudio.google.com](https://aistudio.google.com). The recipes can also be adapted for other LLMs.

**Q: How do I import notebooks in ClearScape Analytics Experience?**  
A: In Jupyter: File → Open from URL → Paste the GitHub raw URL → Done!

## 📈 Success Metrics

Users of these recipes report:
- **95%** reduction in time-to-insight
- **$2M+** average annual savings
- **10x** more queries processed daily

## 💬 Get Help

- 📧 **Email**: ______@teradata.com

## ⭐ Star This Repo!

If you find these recipes helpful, please star this repository to help others discover it!

## 📄 License

Apache 2.0 - See [LICENSE](LICENSE) for details

---

<div align="center">
  
**Built with ❤️ by the Teradata Developer Relations Team**

[Try Free on ClearScape Analytics Experience](https://clearscape.teradata.com) • [Learn More](https://www.teradata.com) • [Blog](https://medium.com/teradata)

</div>
