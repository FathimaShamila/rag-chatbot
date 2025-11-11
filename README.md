# rag-chatbot
A powerful Retrieval-Augmented Generation (RAG) chatbot that allows you to upload PDF documents and ask questions about their content. Get accurate, source-backed answers with page number citations in real-time.
## 🌟 Features

## 📄 Multi-Page Support:
Upload and process multiple page PDF File.
## 🔍 Intelligent Document Analysis: 
Automatic detection of document types (resume, cover letter, academic paper, etc.)
## 🎯 Semantic Search: 
Uses FAISS vector indexing for fast and accurate information retrieval
## 💬 Interactive Chat Interface: 
Clean, user-friendly Gradio-based web interface
## 📍 Source Tracking: 
Every answer includes source citations with specific page numbers
## 💾 Chat History Export:
Save entire conversation history with timestamps
## 🔄 Context-Aware Responses: 
Maintains conversation context for follow-up questions
## ⚡ Real-Time Processing: 
Fast document indexing and query responses

## 🛠️ Technology Stack

### LLM: 
Google Gemini 2.0 Flash (via API)
### Framework: 
LlamaIndex for RAG pipeline
### Vector Store: 
FAISS for semantic search
### Embeddings: 
HuggingFace sentence-transformers/all-MiniLM-L6-v2
### Interface:
Gradio for web UI
### Language: 
Python 3.8+

## 📋 Prerequisites

Python 3.8 or higher
Google API Key (for Gemini LLM)
