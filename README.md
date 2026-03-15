##Searchable PDF Question Answering System

This project builds an AI-powered system that allows users to ask questions from research papers in PDF format. The system converts PDF documents into embeddings, stores them in a vector database, and retrieves the most relevant information to answer user queries.

The project demonstrates how raw documents can be transformed into an intelligent searchable system using modern AI tools.

##Project Objective

The objective of this project is to convert raw PDF documents into a searchable knowledge base so that users can ask natural language questions and receive accurate answers directly from the documents.

##Technologies Used

Python
LangChain
ChromaDB (Vector Database)
HuggingFace Embeddings
Google Gemini API
Streamlit
PyPDF

##Project Workflow

1. Download research paper PDFs from the given links.
2. Load the PDF documents using a PDF loader.
3. Split the documents into smaller chunks for processing.
4. Convert text chunks into embeddings using HuggingFace models.
5. Store embeddings in ChromaDB vector database.
6. Use LangChain to retrieve relevant document chunks.
7. Generate answers using the Gemini language model.
8. Provide a simple Streamlit interface where users can ask questions.

##Features

Ask questions from research papers
Semantic search using embeddings
Vector database storage for fast retrieval
LLM-based answer generation
Simple user interface using Streamlit

##Installation

Clone the repository

git clone https://github.com/TanyaRawat223/pdf-qa-system.git
cd pdf-qa-system

##Install dependencies

pip install pypdf
pip install chromadb
pip install streamlit
pip install langchain
pip install langchain-community
pip install langchain-huggingface
pip install langchain-google-genai
