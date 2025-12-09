DocChat-AI
AI-Powered Document Retrieval and Q&A System

Project Overview
DocChat-AI is an AI-driven document retrieval and question-answering system that allows users to quickly access information from large collections of documents. Using vector embeddings and a language model, it converts text data into feature-rich representations for semantic search across PDFs, DOCX, and TXT files. Users interact via a chat interface, asking natural language questions and receiving context-aware answers.

This project helps solve information overload by providing accurate answers without manually searching documents. Its modular design allows easy expansion to different domains, such as agriculture, research, or corporate knowledge bases. DocChat-AI improves productivity, streamlines knowledge management, and demonstrates the power of AI in document-driven workflows.

Features
Semantic search across multiple document types (PDF, DOCX, TXT)

Chat-based natural language interface

Embedding-based document retrieval (feature engineering)

Modular and easy to extend to new domains

Simple setup with Python and Gradio

Tech Stack
Backend: Python

LLM / RAG: OpenAI or local LLM models + vector embeddings

UI: Gradio

Data Storage: Local files / vector database (FAISS or similar)

Installation
Clone the repository:

bash
git clone <your-repo-url>
cd DocChat-AI
(Optional) Create and activate a virtual environment:

bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
Install dependencies:

bash
pip install -r requirements.txt
Run the app:

bash
python app.py
Open your browser at http://127.0.0.1:7860 to interact with DocChat-AI.

Usage
Upload your documents (PDF, DOCX, TXT) to the system

Ask natural language questions in the chat interface

Receive relevant, context-aware answers based on your documents

Contributors
Krishna Murari Chaudhary, Vernika Khatri, Sneha Yadav

License
This project is licensed under MIT License.

