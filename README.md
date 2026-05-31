# 🤖 RAG Chatbot using LangChain & Groq

A Retrieval-Augmented Generation (RAG) chatbot built using LangChain, Sentence Transformers, Vector Search, and Groq LLMs. This project retrieves relevant context from a knowledge base and generates accurate, context-aware responses using Large Language Models.

## 🚀 Features

* Retrieval-Augmented Generation (RAG)
* Semantic Search using Embeddings
* Context-Aware Question Answering
* LangChain Integration
* Groq LLM Support
* OpenAI LLM Support
* Vector-Based Document Retrieval
* Modular and Extensible Architecture

## 🛠️ Tech Stack

* Python
* LangChain
* Sentence Transformers
* NumPy
* Pandas
* Groq API
* OpenAI API
* Vector Database
* Jupyter Notebook

## 📂 Project Workflow

1. Load documents
2. Split documents into chunks
3. Generate embeddings
4. Store embeddings in vector database
5. Retrieve relevant documents based on user query
6. Pass retrieved context to LLM
7. Generate context-aware response

```text
User Query
    │
    ▼
Retriever
    │
    ▼
Relevant Documents
    │
    ▼
Prompt Construction
    │
    ▼
LLM (Groq/OpenAI)
    │
    ▼
Generated Answer
```

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/RAG-Chatbot-using-LangChain-and-Groq.git
cd RAG-Chatbot-using-LangChain-and-Groq
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file and add:

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

## ▶️ Usage

Run the notebook or Python script and ask questions based on your document collection:

```python
answer = generate_output(
    "What is Retrieval Augmented Generation?",
    rag_retriever,
    llm
)

print(answer)
```

## 📈 Example Query

```text
What is an encoder-decoder architecture?
```

## 📌 Learning Outcomes

* Understanding Retrieval-Augmented Generation (RAG)
* Working with embeddings and vector search
* Integrating multiple LLM providers
* Building context-aware AI applications
* Prompt engineering with LangChain

## 🔮 Future Improvements

* Streamlit Frontend
* FastAPI Backend
* ChromaDB Integration
* FAISS Optimization
* Multi-PDF Support
* Conversation Memory
* Hybrid Search
* Re-ranking Pipeline

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

---

Built with ❤️ using LangChain, Groq, OpenAI, and Python.
