# 🤖 Agent Practice

This repository contains a Jupyter Notebook that demonstrates how to build a **basic AI agent using LangChain**.

---

## 📌 About

This project focuses on creating an **intelligent agent** that can:

* Understand user input
* Use tools (like image processing)
* Reason step-by-step
* Generate final responses

The agent follows the **ReAct architecture**:

* **Reason** → Think about the problem
* **Act** → Use tools (functions/APIs)
* **Observe** → Use results to continue reasoning ([Hugging Face][1])

---

## 🧠 Features

* Simple agent built using **LangGraph**
* Uses **LLM (GPT-4o / similar)** for reasoning
* Tool integration (example: extracting text from images)
* Multimodal capability (text + image input)
* Step-by-step agent workflow

---

## ⚙️ Setup

1. Clone the repository:

```bash
git clone https://github.com/amjathhussain31/agent-practice.git
cd agent-practice
```

2. Install dependencies:

```bash
pip install -U langchain_openai langchain_core langgraph
```

3. Add your API key:

```python
import os
os.environ["OPENAI_API_KEY"] = "your_api_key"
```

---

## 📓 Notebook Content

The notebook includes:

* Setting up LangChain and LangGraph
* Initializing LLM (ChatOpenAI)
* Creating a custom tool (image → text extraction)
* Building an agent workflow
* Running the agent step-by-step

---

## ▶️ Usage

Open the notebook:

```bash
jupyter notebook
```

Run each cell to see:

* How the agent processes input
* How it calls tools
* How it generates final output

---

## 🛠️ Tech Used

* Python
* LangChain
* OpenAI / LLM APIs

---
