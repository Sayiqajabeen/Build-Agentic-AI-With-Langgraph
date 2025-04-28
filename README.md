# Build-Agentic-AI-with-Langgraph
Created 3 tools arxiv, wikipedia, and tavily. Combining all three tools in List &amp; Integrating the LLM. Execute the LLM with tools.AI Assistant is ready now can create entrie application in Langraph.Langgraph do specific tasks like search, summarize, and generate text. 
# Chatbot with Multiple Tool Integrations

## 📖 Overview

This project implements a **multi-tool AI chatbot** that can:
- Answer user queries
- Perform web searches
- Perform file-based Q&A (using uploaded documents)
- Analyze CSV files
- Solve coding-related problems

It uses a combination of **Groq LLMs**, **LlamaIndex** tools, and **LangChain agents** to flexibly route user queries to the appropriate tool.

---

## 🛠 Tech Stack

| Category           | Technology |
|--------------------|------------|
| Backend Framework  | Python, Jupyter Notebook |
| LLM Provider       | Groq (Mixtral, LLaMA3-70B) |
| AI Libraries       | LangChain, LlamaIndex |
| Embedding Model    | Hugging Face Embeddings |
| Tooling/Agents     | LangChain AgentExecutor, Tools |
| File Handling      | PyMuPDF (for PDFs), pandas (for CSVs) |
| Search             | Tavily API (Web Search) |
| Hosting (optional) | Streamlit / Gradio |

---

## 🚀 Features

- **Dynamic tool routing**: Automatically selects the best tool based on the user query.
- **LLM-powered responses**: Uses top-tier models from Groq for high-quality answers.
- **Document Q&A**: Upload PDFs or text documents and ask questions about their content.
- **CSV Analysis**: Query CSV files using natural language.
- **Web Search**: Real-time internet search when necessary.

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Sayiqajabeen/chatbot-multiple-tool.git
cd chatbot-multiple-tool



