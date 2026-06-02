# chatbot
AI-Powered RAG Chatbot using Python, FAISS, LangChain, OpenAI and Streamlit
#AI-Powered RAG Chatbot
A Retrieval-Augmented Generation (RAG) chatbot built using Python, LangChain, FAISS, OpenAI, and Streamlit. This chatbot allows users to upload PDF documents and ask questions based on the document content. The system retrieves the most relevant information from the uploaded PDF and generates accurate answers using an LLM.
# 🚀 Features
Upload PDF documents
Extract text from PDFs
Split documents into manageable chunks
Generate embeddings using Sentence Transformers
Store embeddings in FAISS Vector Database
Retrieve relevant document sections
Generate AI-powered responses using OpenAI
User-friendly Streamlit interface
Display retrieved document chunks for transparency
#🔄 How It Works
Step 1: Upload PDF

Users upload a PDF document through the Streamlit interface.

Step 2: Text Extraction

The system extracts text content from the uploaded PDF.

Step 3: Chunking

Large documents are divided into smaller chunks using LangChain's text splitter.

Step 4: Embedding Generation

Each chunk is converted into vector embeddings using Sentence Transformers.

Step 5: Vector Storage

Embeddings are stored in a FAISS vector database.

Step 6: Retrieval

When a question is asked, the system retrieves the most relevant chunks from the vector database.

Step 7: Response Generation

Retrieved chunks are provided as context to the OpenAI model, which generates an answer.
