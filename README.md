# Fin_Agentic_Chatbot

An AI-powered Finance Chatbot built using **LangGraph**, **LangChain**, **FastAPI**, and **RAG (Retrieval-Augmented Generation)**. The project is designed with a modular architecture to support conversational AI, financial document retrieval, and future agentic workflows.

---

## 📌 Features

- 🤖 AI-powered finance chatbot
- 📚 Retrieval-Augmented Generation (RAG)
- 💬 Conversational chat interface
- 📄 Financial document ingestion
- 🔍 Semantic search over financial documents
- 🧠 Agent-based reasoning using LangGraph
- 🗄️ PostgreSQL for application data
- 📦 Vector Database for embeddings
- 🐳 Docker support

> **Note:** This project is under active development. Additional features will be added incrementally.

---

# Project Structure

```text
Fin_Agentic_Chatbot/
│
├── README.md
├── .gitignore
├── .env.example
├── requirements.txt
├── pyproject.toml
├── docker-compose.yml
│
├── frontend/                     # Streamlit
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── app.py                    # FastAPI entry point
│   ├── api/                      # REST APIs
│   ├── services/                 # Business logic
│   ├── schemas/                  # Request/Response models
│   ├── config/                   # Configuration
│   └── core/                     # Utilities & middleware
│
├── agent/
│   ├── graph.py                  # LangGraph workflow
│   ├── state.py
│   ├── nodes/                    # Agent nodes
│   ├── prompts/                  # Prompt templates
│   ├── tools/                    # Custom tools
│   └── memory/                   # Conversation memory
│
├── rag/
│   ├── ingestion/                # Document ingestion
│   ├── retrieval/                # Retrieval logic
│   ├── pipelines/                # RAG pipelines
│   └── embeddings/               # Embedding utilities
│
├── database/
│   ├── postgres/                 # PostgreSQL
│   ├── vector_db/                # Chroma / Qdrant / PGVector
│   └── redis/                    # Cache & session storage
│
├── data/
│   ├── raw/                      # Uploaded documents
│   ├── processed/                # Processed documents
│   └── embeddings/               # Generated embeddings
│
├── tests/
│
├── scripts/                      # Utility scripts
│
└── docs/                         # Project documentation
```

---

# Technology Stack

| Layer | Technology |
|--------|------------|
| Frontend | Streamlit |
| Backend | FastAPI |
| Agent Framework | LangGraph |
| LLM Framework | LangChain |
| Embedding Model | OpenAI / Ollama |
| Vector Database | Chroma / Qdrant / PGVector |
| Database | PostgreSQL |
| Cache | Redis |
| Containerization | Docker |

---

# Current Development Goals

- Build a modular backend architecture
- Implement a basic RAG pipeline
- Create a finance chatbot with conversational memory
- Support document upload and indexing
- Integrate LangGraph agent workflows
- Prepare the project for future multi-agent expansion

---

# Future Enhancements

- Multi-agent architecture
- Financial calculator tools
- Portfolio analysis
- Stock market data integration
- SQL agent
- Evaluation with RAGAS & LangSmith
- Authentication & user management
- Streaming responses
- Deployment on Kubernetes

---

## License

This project is for learning and experimentation with Agentic AI, RAG, and modern LLM application development.
