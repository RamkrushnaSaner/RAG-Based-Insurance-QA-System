# 🧠 RAG-Based Insurance QA System

This project implements a **Retrieval-Augmented Generation (RAG)** system for answering insurance-related questions from a policy document.

## 🚀 Features
- Vector-based retrieval using **SentenceTransformer embeddings**
- FAISS for fast similarity search
- Cross-encoder reranking (`BAAI/bge-reranker-base`)
- Extractive + Abstractive summarization
- Completeness checking and auto-expansion

## 📁 Project Structure
rag-project/
│
├── data/
│   ├── original_policy.pdf        # Original policy prospectus (PDF)
│   └── policy_text.txt            # Extracted text from the PDF
│
├── app.py                         # Your full RAG code (Sections 1–12)
├── requirements.txt               # Python dependencies
├── README.md                      # Project description & usage
