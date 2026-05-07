# 📘 Level 2 – Applied RAG: Personal Research Assistant

This level builds on the foundation by adding **contextual retrieval, memory, and reranking**.  
The goal is to create a **fullstack research assistant** that can handle multi-turn conversations, prioritize relevant results, and provide citations.

---

## 💡 Application Idea: Personal Research Assistant

A web-based assistant that helps users research topics by:
- Remembering conversation history (session memory).
- Using **hybrid search** (semantic + keyword).
- Reranking retrieved chunks for relevance.
- Delivering contextual answers with citations.

### Example Flow
1. User asks: *“Explain LangChain’s DirectoryLoader issue.”*  
2. Retriever fetches relevant GitHub issues + docs.  
3. Reranker prioritizes the most relevant snippet.  
4. Assistant responds with context + citation:  
   *“The error occurs because `RecursiveCharacterTextSplitter` moved to a new module. See GitHub Issue #1024.”*

---

## 🔑 Core Features
- **Backend (FastAPI/Django/Flask)**  
  - Document ingestion (PDFs, articles, notes).  
  - Embedding + vector store (FAISS/Chroma).  
  - Hybrid retriever (BM25 + embeddings).  
  - Reranker (Cohere Rerank or sentence-transform