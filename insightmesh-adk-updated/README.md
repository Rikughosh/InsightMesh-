
# InsightMesh – Multi-Agent BI System with Google ADK

InsightMesh is a CLI-based multi-agent system built using Google's Agent Development Kit (ADK), designed to automate business intelligence workflows.

---

## 🌐 GitHub Repository

🔗 [https://github.com/yourusername/insightmesh-adk](https://github.com/yourusername/insightmesh-adk)

---

## 💻 CLI Agent Installation & Usage

This tool is currently a CLI-based system built with Python.

### 🔧 Installation

```bash
git clone https://github.com/yourusername/insightmesh-adk.git
cd insightmesh-adk
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 🚀 Run Example

```bash
python main.py
```

### 🧪 Test the Agents

Each agent is modular. You can test them like this:

```bash
python agents/ingestion_agent.py      # Fetches and loads data into BigQuery
python agents/analysis_agent.py       # Queries and computes metrics
python agents/insight_agent.py        # Generates business insights
```

### 📦 Deployment (Optional)

Deploy to Google Cloud Run using Docker:

```bash
gcloud builds submit --tag gcr.io/YOUR_PROJECT_ID/insightmesh
gcloud run deploy insightmesh --image gcr.io/YOUR_PROJECT_ID/insightmesh --platform managed
```

---

## 🧠 Learn More

See the architecture diagram in `diagrams/` and the `.gitignore` for build exclusions.
