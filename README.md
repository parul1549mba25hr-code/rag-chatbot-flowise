# RAG Chatbot using Flowise

This project is a Retrieval-Augmented Generation (RAG) based chatbot built using Flowise. It allows users to upload documents and interact with them through a conversational interface.

---

## Features

- Upload and process documents (PDF, files)
- Smart text chunking using Recursive Character Text Splitter
- Semantic search using vector embeddings
- Context-aware responses using conversational memory
- Chat interface powered by Mistral AI
- Fast in-memory vector storage for retrieval

---

## Tech Stack

- Flowise AI
- Mistral AI (LLM)
- Google Gemini Embeddings
- LangChain Components
- In-Memory Vector Store

---

## Architecture Overview

1. Document Loader loads the file
2. Text Splitter breaks it into chunks
3. Embeddings convert text into vectors
4. Vector Store stores embeddings
5. Retriever fetches relevant chunks
6. Conversational QA Chain generates answers

---

## Project Workflow

- Load document
- Split into chunks
- Generate embeddings
- Store in vector database
- Retrieve relevant context
- Generate response using LLM

---

## How to Run

1. Import the JSON file into Flowise
2. Configure API keys:
   - Google Generative AI
   - Mistral AI
3. Upload your document
4. Start chatting with your data 🚀

---

## Use Cases

- Document Q&A
- Chat with PDFs
- Knowledge base assistant
- Customer support automation

---

## Screenshot / Demo

(Add your project screenshot here)

---

## Author

Parul

---

## Contribute

Feel free to fork and improve this project!
