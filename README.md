Breast Cancer Chatbot - RAG Project
Project Overview
This project is a Breast Cancer Chatbot built using Retrieval-Augmented Generation (RAG).
The chatbot allows users to ask questions about breast cancer and receive accurate, context-aware responses based on trusted medical literature, including PDF articles from PubMed.

The project is designed to grow over time: new PDF documents or research articles can be added to improve the knowledge base, making the chatbot more robust and up-to-date.

⚡ Features
RAG-based chatbot for breast cancer information
Context-aware answers with references to source PDFs
Supports adding new PDF research articles to grow knowledge
Built with LangChain for easy RAG pipeline management
Uses a vector store for efficient document retrieval
🛠 Technologies & Tools Used
Large Language Model (LLM): Mistral-7B-Instruct-v0.2 via HuggingFace for text generation
HuggingFace Pipeline: Runs the model with controlled parameters
LangChain: Wraps the HuggingFace pipeline (HuggingFacePipeline) to build the RAG pipeline, manage prompts, and connect the retriever
Vector Store: FAISS for storing embeddings and fast document retrieval
PDF Loader & Text Splitter: PyPDFLoader and RecursiveCharacterTextSplitter for preprocessing PDFs from PubMed
Gradio: Interactive chatbot interface for submitting questions and receiving answers
