# GenAI Projects – LangChain Chatbot & AI Finance Agent

A collection of practical **Generative AI applications** built with LangChain and Gemini, covering conversational memory, message management, tool calling, structured output, streaming, and batch processing.

## 🚀 Projects

### 1. Chatbot with LCEL & Message History

A conversational chatbot built using **LCEL (LangChain Expression Language)** with persistent message history and context management.

**Features**

* LCEL Chain
* `ChatGoogleGenerativeAI`
* Message History
* Message Trimming
* Context-aware conversations

```text
User → LCEL Chain → Gemini → Message History
                         ↑
                  Trim Messages
```

---

### 2. AI Finance Agent with Yahoo Finance

An AI agent that answers queries such as **"Find the latest news about an asset"** using a Yahoo Finance tool.

**Features**

* `create_agent()` from `langchain.agents`
* Yahoo Finance Tool
* `ChatGoogleGenerativeAI`
* `InMemorySaver` Checkpointer
* `SummarizationMiddleware`
* Structured Output
* Streaming
* Batch Processing

```text
User Query
    ↓
AI Agent
    ↓
Yahoo Finance Tool
    ↓
Gemini
    ↓
Structured Response
```

## 🛠️ Tech Stack

**Python · LangChain · LCEL · Gemini · AI Agents · Yahoo Finance · Tool Calling · Structured Output · Memory · Middleware**

## 🎯 Key Outcomes

* Built conversational **LCEL-based chatbot** with message history management.
* Built a **tool-using financial AI agent** with memory and summarization.
* Implemented **structured output, streaming, and batch processing**.
