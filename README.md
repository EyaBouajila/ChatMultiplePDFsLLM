# Chat with Multiple PDFs using Gemini 💁
![Screenshot 2025-02-02 122017](https://github.com/user-attachments/assets/1c139ea2-a66f-46d9-b5cd-47db0bd51c17)
![Screenshot 2025-02-02 123246](https://github.com/user-attachments/assets/51e8b362-7a0d-49f6-9592-0a73c01542d5)


## Overview
This project enables users to upload multiple PDF documents and interact with them using a conversational AI assistant. It extracts text from PDFs, processes it using embeddings, and allows users to ask questions based on the document content. If an answer is not available in the provided context, the system explicitly states it instead of giving incorrect responses.

## Features
- Upload multiple PDFs for analysis
- Extracts and processes text from PDFs
- Stores document embeddings using FAISS
- Conversational AI that answers user queries based on document content
- Uses Google Gemini AI for natural language processing

## Technologies Used
- Programming Language: Python
- Framework: Streamlit
- Embeddings: HuggingFace Instruct Embeddings
- Vector Database: FAISS
- LLM Model: Google Gemini AI
- PDF Processing: PyPDF2
- Environment Management: Python-dotenv
