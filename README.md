# 🧠 Retrieval-Augmented Generation with LLMs

This  demonstrates a simple yet powerful implementation of **RAG (Retrieval-Augmented Generation)** using LLMs and vector databases. RAG enhances the capabilities of language models by allowing them to **retrieve factual information** from an external knowledge base before generating responses.

## 🚀 Overview

🔍 This notebook (`RAG_DEMO.ipynb`) showcases how to:
- Ingest custom documents
- Convert text into embeddings
- Store and search using a vector database (e.g., FAISS/Chroma)
- Answer questions using a Large Language Model (LLM) combined with retrieval

## 🛠️ Tech Stack

| Component         | Tool/Library                    |
|------------------|----------------------------------|
| Language Model    |  HuggingFace                    |
| Embedding Model   |  HuggingFace Transformers       |
| Vector Store      | FAISS                           | 
| Orchestration     | LangChain                       |
| Notebook          | Jupyter / Google Colab          |
| Language          | Python                          |



## 📌 Features

- Document ingestion and chunking
- Embedding generation and vector storage
- Semantic search using user queries
- Prompt construction with retrieved context
- LLM-based response generation

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/swalhasakeer/RAG-Generation-With-LLMs.git
cd RAG-Generation-With-LLMs
```

## 🔐 Environment Variables

For LLM access (OpenAI, etc.), set your API key:

```bash
export OPENAI_API_KEY="your-api-key-here"
```
Or in notebook:

```python

import os
os.environ["OPENAI_API_KEY"] = "your-api-key-here"
```

## 🙌 Acknowledgements

This project was made possible with the help of the following open-source tools and libraries:

- [LangChain](https://www.langchain.com/)
- [OpenAI](https://platform.openai.com/) 
- [FAISS](https://faiss.ai/) 




