PDF Chatbot 🤖
This application allows users to upload PDF files and ask questions based on the content of the uploaded documents. It utilizes LangChain, Google Generative AI for embeddings, and FAISS for efficient document search, all served through a user-friendly Streamlit interface.

Features
Upload Multiple PDFs: Extracts text from PDF files.
Text Chunking: Splits extracted text into manageable chunks.
Vector Search: Uses FAISS for efficient similarity searches over PDF content.
Conversational AI: Powered by Google Generative AI for generating answers to user questions.
Interactive Chat: Ask questions directly within the app and get answers based on the uploaded PDF documents.
Technology Stack
Python 3.10+: The programming language used.
Streamlit: For building the web interface.
LangChain: For text chunking and question-answering logic.
FAISS: To perform fast similarity searches on text embeddings.
Google Generative AI: For embeddings and chatbot response generation.
PyPDF2: To extract text from PDF files.