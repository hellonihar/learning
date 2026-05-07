A simple chatbot that answers frequently asked questions by retrieving relevant documents (policies, schedules, manuals) and generating concise responses.

Core Features
*****************
Document ingestion: Load a small set of PDFs or text files (e.g., student handbook, HR policies).

Embeddings + vector store: Use Chroma to embed and store document chunks.

Retriever + LLM pipeline: Query embeddings, retrieve top-k chunks, and feed them into an LLM for answer generation.

Basic UI: A minimal web interface (Flask/FastAPI) for asking questions & uploading documents (  text and pdf)


Tech Stack
***************
Python (core logic)

Chroma (vector database)

Groq (LLM)

FastAPI ( web interface)