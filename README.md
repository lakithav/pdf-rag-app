# 📄 PDF RAG Application

A Retrieval-Augmented Generation (RAG) app that answers questions 
from a provided PDF document — built entirely with free tools.

## 🛠️ Tech Stack
- **LangChain** — RAG pipeline & document processing
- **FAISS** — Vector similarity search
- **HuggingFace** — Sentence embeddings (all-MiniLM-L6-v2)
- **Groq API (Llama 3.3)** — Free LLM for answer generation
- **Google Colab** — Free cloud runtime

## 🚀 How It Works
1. PDF is loaded and split into chunks
2. Chunks are embedded and stored in a FAISS vector store
3. User question is embedded and matched to relevant chunks
4. Matched chunks + question are sent to Llama 3.3 via Groq
5. Answer is returned grounded in the document

## ▶️ How to Run
1. Open the notebook in Google Colab
2. Run all cells in order
3. Enter your free Groq API key when prompted
4. Upload your PDF and start asking questions
