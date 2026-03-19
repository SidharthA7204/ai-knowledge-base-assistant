# AI Knowledge Base Assistant (RAG Chatbot)

This project is an AI-powered chatbot that retrieves information from documents using Retrieval-Augmented Generation (RAG).

Users can upload documents and ask questions. The system retrieves relevant information and generates accurate answers.

## Features
- Document-based question answering
- Semantic search using embeddings
- Context-aware AI responses
- Simple UI using Streamlit

## Tech Stack
- Python
- LangChain
- OpenAI API
- ChromaDB
- Streamlit

## How It Works
1. Documents are converted into embeddings
2. Stored in vector database
3. User query is matched with relevant data
4. LLM generates answer using retrieved context

## Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py


---
