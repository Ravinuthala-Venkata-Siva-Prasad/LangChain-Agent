# LangChain Agent Development

A hands-on learning repository covering the fundamentals of **LangChain, LLM integration, tools, messages, structured output, and middleware**.

This repository contains practical Jupyter notebooks that demonstrate how to build and work with LangChain-based AI applications.

## 📚 Topics Covered

### 1. LangChain Introduction

Introduction to LangChain and its core concepts.

**Notebook:** `1.Langchainintro.ipynb`

### 2. Model Integration

Learn how to integrate different LLM providers with LangChain, including OpenAI, Groq, and Google Gemini.

**Notebook:** `2.modelintegration.ipynb`

### 3. Tools

Learn how LangChain tools work and how an LLM can use tools to perform specific tasks.

**Notebook:** `3.tools.ipynb`

### 4. Messages

Understand different message types used in LangChain, including human messages, AI messages, and tool messages.

**Notebook:** `4.messages.ipynb`

### 5. Structured Output

Learn how to use Pydantic models to receive structured responses from LLMs.

Topics include:

* Pydantic `BaseModel`
* `Field`
* Structured output
* Schema-based responses

**Notebook:** `5.Structured_output.ipynb`

### 6. Middleware

Learn how middleware can be used to control and extend LangChain agents.

Topics include:

* Agent middleware
* Summarization middleware
* Token management
* Conversation context management

**Notebook:** `6.Middleware.ipynb`

## 🛠️ Technologies Used

- Python
- LangChain
- LangChain Core
- LangChain Community
- LangChain OpenAI
- LangChain Groq
- LangChain Google Gemini
- Pydantic
- Python-dotenv
- Jupyter Notebook
- uv – Python package and project management
- Antigravity – development environment
- Git & GitHub

## 📁 Project Structure

```text
LangChain-Agent/
│
├── 1.Langchainintro.ipynb
├── 2.modelintegration.ipynb
├── 3.tools.ipynb
├── 4.messages.ipynb
├── 5.Structured_output.ipynb
├── 6.Middleware.ipynb
│
├── main.py
├── requirements.txt
├── pyproject.toml
├── .gitignore
└── README.md
```

## 🚀 Installation

Clone the repository:

```bash
git clone <[YOUR-GITHUB-REPOSITORY-URL](https://github.com/Ravinuthala-Venkata-Siva-Prasad/LangChain-Agent)>
```

Navigate to the project directory:

```bash
cd LangChain-Agent
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment on Windows:

```bash
.venv\Scripts\activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project directory and add your API keys:

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_google_api_key
```

**Never commit your `.env` file or expose API keys publicly.**

## ▶️ Running the Notebooks

Open the project in VS Code or Jupyter Notebook and run the notebooks in order:

```text
1 → LangChain Introduction
2 → Model Integration
3 → Tools
4 → Messages
5 → Structured Output
6 → Middleware
```

Following this order helps build the concepts step by step.

## 🎯 Learning Goals

This repository is designed to build a practical understanding of:

* LangChain fundamentals
* LLM integration
* Tool calling
* Message handling
* Structured LLM responses
* Pydantic schemas
* Agent middleware
* Context and token management

## 👨‍💻 Author

**Ravinuthala Venkata Siva Prasad**

M.Tech – Artificial Intelligence

Interested in:

* Generative AI
* Artificial Intelligence
* Machine Learning
* LLM Applications
* AI Agents
* RAG
* LangChain

## ⭐ Future Improvements

* Add RAG implementation
* Add vector databases such as FAISS and Chroma
* Build an end-to-end AI agent
* Add FastAPI deployment
* Add LangServe integration
* Add Agentic AI workflows

---

⭐ If you find this repository useful, consider giving it a star!
