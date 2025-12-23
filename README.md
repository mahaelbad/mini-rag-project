# Mini RAG Project

A simple **Retrieval-Augmented Generation (RAG)** project that answers questions from documents using embeddings and similarity search.

---

## 📝 Project Description

This project demonstrates a basic pipeline of a RAG system:

1. Users can upload text documents (PDF, TXT, DOCX).
2. Documents are split into smaller chunks.
3. Each chunk is converted into embeddings (numeric representations).
4. User queries are converted into embeddings and matched with the closest chunks.
5. A Large Language Model (LLM) generates an answer based on the retrieved chunks.

---

## ⚡ Features

- Convert text to embeddings using `Sentence Transformers`
- Calculate similarity between user query and text chunks
- Retrieve relevant content from documents
- Generate accurate answers with LLM

---

## 🛠️ Tech Stack

- **Python**  
- **NumPy**  
- **Sentence Transformers** (for embeddings)  
- **FAISS** (optional, for vector search)  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/mini-rag-project.git
cd mini-rag-project
