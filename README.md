# Agentic Chatbot

[![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python)](https://python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-latest-1C3C3C?logo=langchain)](https://langchain.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-latest-1C3C3C?logo=langchain)](https://langchain-ai.github.io/langgraph/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1-FF4B4B?logo=streamlit)](https://streamlit.io/)

A production-ready scaffold for an agentic chatbot powered by LangChain and LangGraph, featuring FAISS vector search for document retrieval, Tavily web search integration for real-time information, and a Streamlit-based chat interface — all in a modular, extensible architecture.

## Features

- **Agentic reasoning** — ReAct agent pattern for tool selection and execution
- **Vector search** — FAISS-powered document retrieval from local knowledge bases
- **Web search** — Tavily API integration for real-time internet queries
- **Streaming responses** — real-time token-by-token LLM output
- **Modular architecture** — pluggable tools and configurable agent behaviors
- **Streamlit UI** — clean, responsive chat interface
- **Session management** — conversation history and context persistence

## Tech Stack

- **Python 3** — Core programming language
- **LangChain** — LLM integration and tool-calling framework
- **LangGraph** — Stateful multi-agent orchestration
- **FAISS** — Vector similarity search
- **Tavily** — Web search API
- **Streamlit** — Web UI framework

## Getting Started

```bash
git clone https://github.com/giovanniromero-dev/agentic-chatbot.git
cd agentic-chatbot
pip install -r requirements.txt
# Configure your .env with API keys
streamlit run app.py
```

---

Built with dedication by [Giovanni Romero](https://github.com/giovanniromero-dev)
