# Conversational RAG With PDF Uploads 🧠📄

This project enables users to upload PDFs and interact with their content using a **Conversational Retrieval-Augmented Generation (RAG)** system, powered by **LangChain**, **Streamlit**, and **Groq's Gemma2-9b-It** model.

---

## Features

- Upload and process multiple PDF documents
- Conversational memory with contextual chat history
- Reformulates user queries using past conversation for improved retrieval
- Embedding-based document search using `all-MiniLM-L6-v2`
- Answer generation via Gemma2-9b-It LLM
- Seamless integration of HuggingFace, LangChain, and ChromaDB

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** for UI
- **LangChain** for chaining and retrieval logic
- **ChromaDB** as the vector store
- **HuggingFace** embeddings (`all-MiniLM-L6-v2`)
- **Groq API** for LLM inference
- **OpenCV** and **PyPDFLoader** for document parsing
