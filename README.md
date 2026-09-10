# RAG AI Assistant

A local AI chatbot built with **Retrieval-Augmented Generation (RAG)**: it answers questions from its own Markdown documents, fully offline — no cloud, no API keys.

## Stack

- **Python** + **FastAPI** — backend API
- **PostgreSQL + pgvector** (Docker) — vector database for semantic search
- **Ollama** — local models: `nomic-embed-text` (embeddings) and `qwen3:1.7b` (chat)
- **Gradio** — chat UI
- **pytest** — integration tests

## Setup

```
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```
