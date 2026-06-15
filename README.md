# Agentic Chatbot

Minimal scaffold for an agentic chatbot project built around the LangChain and LangGraph ecosystem.

## Overview

This repository is an early-stage Python project intended for experimenting with tool-using chatbots and agentic workflows. The dependency set points to a stack that combines:

- `langchain` and `langgraph` for agent orchestration
- `langchain-openai` and `langchain-groq` for model integrations
- `langchain-community`, `langchain-core`, and `faiss-cpu` for retrieval-oriented workflows
- `tavily-python` for web search
- `streamlit` for a lightweight UI layer

## Project Structure

```text
.
|-- app.py
|-- requirements.txt
`-- src/
    `-- langgraphagenticai/
        `-- main.py
```

## Current State

The repository currently acts as a starter scaffold rather than a finished application. It is a good base for adding:

- a chatbot UI in Streamlit
- a LangGraph state machine
- retrieval with FAISS
- external tools such as Tavily search

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```
