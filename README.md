
# TravelAgent-AutoGen


# 🧳 AI Travel Planner using AutoGen Agents

This project is a multi-agent conversational AI system built with [AutoGen](https://github.com/microsoft/autogen). It helps users plan a trip using a set of collaborative AI agents with specialized roles (planner, local guide, language expert, and summarizer).

## 🚀 Features

- Four cooperating AI agents using Groq LLMs:
  - Trip Planner Agent
  - Local Activity Agent
  - Language Tips Agent
  - Travel Summary Agent
- Round-robin interaction until a complete itinerary is generated
- Termination condition using keyword "TERMINATE"
- Runs asynchronously in a Colab notebook or any Python async environment

## 📦 Requirements

```bash
pip install -U autogen-agentchat autogen-ext groq nest_asyncio tiktoken
