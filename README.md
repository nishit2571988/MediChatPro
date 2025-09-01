
## 🩺 MediChat Pro


**MediChat Pro** is an intelligent medical document assistant built with Streamlit.
It allows users to upload their medical documents (PDF) and interact with them through a chat interface.

The application uses a Retrieval-Augmented Generation (RAG) pipeline to retrieve relevant information from uploaded documents and generate accurate, context-aware answers.

---
## ✨ Key Features

 📄 Upload Medical PDFs Easily upload one or multiple medical PDF documents via a clean and intuitive web interface.

 🧠 Smart Text Processing Automatically extract text from PDFs, split the content into digestible chunks, and convert them into vector embeddings for efficient retrieval.

 ⚡ Vector Search with FAISS Leverages FAISS for fast similarity search across embedded document chunks.

 💬 Conversational Interface Ask your questions in a user-friendly chat interface and get detailed, accurate responses.

 🤖 Contextual Answer Generation Combines document retrieval with an LLM (via OpenAI API) to generate informed and context-rich answers to your queries.

 ---
## 🚀 Tech Stack

- Streamlit – Web UI & application framework 
- FAISS – Vector database for fast similarity search 
- LangChain – Manages the RAG pipeline 
- OpenAI API – For language generation and reasoning pdfplumber / 
- PyPDF2 – For PDF text extraction

---
## 📌 How to Use

  1. Upload one or more medical PDF documents. 
  2. Type in your medical questions through the chat interface. 
  3. Receive reliable, context-aware answers—instantly.

---

## 🔒 Security

- All API keys and sensitive configurations are handled securely using a .env file. 
- For deployment, use Streamlit Cloud secrets or Hugging Face Spaces secrets to keep credentials safe.

---
## 🛠️ Roadmap & Future Enhancements

- ✅ Support for additional document formats (DOCX, TXT)
- ✅ Enhanced user interface with conversation history 
- ✅ Deployment on platforms like Hugging Face Spaces or Streamlit Cloud

---
## 🌐 Live Application

- App: MediChat Pro – Live Demo Experience the demo in action: https://medichatpro-app.streamlit.app/
- See how MediChat Pro makes medical document analysis effortless.

---
## 👨‍💻 Developer
Developed by Nishit Hirpara
