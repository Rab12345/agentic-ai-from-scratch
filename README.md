# Agentic AI From Scratch

A hands-on implementation of **Agentic AI systems**, starting from the fundamentals and progressively building toward production-oriented agent architectures.

The goal of this repository is to understand what happens **under the hood** when building AI agents rather than relying entirely on high-level frameworks.

## What This Project Covers

* LLM fundamentals for agentic systems
* Tool calling / function calling
* Agent loops and decision-making
* State and memory
* Retrieval-Augmented Generation (RAG)
* Multi-tool agents
* Agent evaluation
* Error handling and guardrails
* Human-in-the-loop workflows
* Multi-agent architectures
* MCP and tool interoperability
* Production-oriented agent architecture

## Architecture

The project starts with a simple agent loop:

```text
User
  ↓
LLM
  ↓
Decide whether a tool is required
  ↓
Tool
  ↓
Tool Result
  ↓
LLM
  ↓
Final Response
```

The architecture will progressively evolve as additional capabilities are introduced.

## Project Structure

```text
agentic-ai-from-scratch/
│
├── notebooks/
│   ├── 01_tool_calling.ipynb
│   ├── 02_agent_loop.ipynb
│   ├── 03_memory.ipynb
│   └── ...
│
├── src/
│   └── ...
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Technology

* Python
* Hugging Face
* LLMs
* RAG
* Vector databases
* LangChain
* LangGraph
* MCP
* Google Colab

Additional technologies will be introduced as the project evolves.

## Learning Approach

The project intentionally starts **without high-level agent frameworks**.

The first implementations will build the fundamental agent loop directly so that the underlying concepts are clear before introducing frameworks such as LangChain and LangGraph.

## Status

**In Progress**

This repository is being developed incrementally, with each stage introducing a new component of an agentic AI system.

## Author

**Rabi Mishra**

Data Scientist | Machine Learning | Marketing Analytics | Generative AI | Agentic AI
