# Langgraph introduction

This project demonstrates the ReAct function calling pattern using Langgraph.

## How it works

LLM can choose to call tools if it deems necessary and takes the tool calling response to add to the LLM response.

## Environment variables

Create a `.env` file and fill in:

| Variable | Description |
|---|---|
| `OPENAI_API_KEY` | From [platform.openai.com](https://platform.openai.com) |
| `LANGSMITH_API_KEY` | From [langchain.com/langsmith](https://www.langchain.com/langsmith) |
| `LANGSMITH_PROJECT` | Your LangSmith project name |
| `TAVILY_API_KEY` | From [app.tavily.com](https://app.tavily.com) |

## Usage

### 1. Install dependencies

```bash
uv lock
uv sync
```

### 2. Run ingestion

```bash
uv run python main.py
```
