# ResearchAgent-
Autonomous AI Research Assistant with MCP Tools, LangGraph Orchestration, Firecrawl Web Crawling, LangSmith Monitoring, and ChromaDB Retrieval


## 🚀 Features
- 🔍 Automated research using agent tools (e.g., Firecrawl)
- 🧠 Local LLM support via Ollama
- 📚 Embedding-based document storage
- 🗄️ Saves structured research data into a database
- 🔌 MCP integration for Claude Desktop

## 🛠️ Tech Stack
- Python
- Ollama (local LLM + embeddings)
- Firecrawl API (web research)
- LangGraph, MCP (agent + tool integration)
- Vector DB - Local database(ChromaDB)

## ⚙️ Setup

### 1. Clone repo
```bash
git clone https://github.com/your-username/ResearchAgent.git
cd ResearchAgent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Start Ollama

```bash
ollama serve
ollama pull nomic-embed-text
ollama pull qwen3
```

### 4. Set environment variables

```bash
export FIRECRAWL_API_KEY=your_key_here
export LANGSMITH_API_KEY=your_key_here
```

### 5. Run Client

```bash
python client.py
```


## 💡 Usage

Ask queries like:

```
research on LLM and save data in my db
```

The agent will:

1. Perform research
2. Process data
3. Store results in the database

## ⚠️ Notes

* Do NOT commit `.env` or API keys
* Requires Ollama running locally
* Firecrawl API key required for web research

## 📌 Future Improvements

* UI dashboard
* Better error handling
* Multi-agent workflows
* Cloud deployment

```

