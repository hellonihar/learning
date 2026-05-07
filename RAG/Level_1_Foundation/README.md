# 📘 Level 1 – Foundation: FAQ Assistant

This level introduces the **basics of Retrieval-Augmented Generation (RAG)** by building a simple FAQ assistant.  
The goal is to demonstrate how embeddings, vector search, and a language model can be combined to answer questions from a small set of documents.

---

## 🎯 Application Idea: FAQ Assistant

A chatbot that retrieves answers from a **student handbook, HR policies, or company guidelines** and generates concise responses.

### Example Flow
1. User asks: *“What is the leave policy?”*  
2. Retriever fetches relevant handbook section.  
3. LLM generates: *“Employees are entitled to 20 days of annual leave as per HR policy.”*

---

## 🔑 Core Features
- **Document ingestion**: Load PDFs or text files.  
- **Embeddings + vector store**: Use FAISS or Chroma to embed and store chunks.  
- **Retriever + LLM pipeline**: Query embeddings, retrieve top-k chunks, and feed them into an LLM.  
- **Basic UI**: CLI or minimal FastAPI/Flask interface.  

---

## 🛠️ Tech Stack
- **Python** (core logic)  
- **FAISS/Chroma** (vector database)  
- **OpenAI/Groq/Claude API** (LLM)  
- **FastAPI** (optional web interface)  

---

## 📂 Project Structure
