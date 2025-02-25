# AI Document Assistant - RAG Model

## 📌 Overview

The **AI Document Assistant** is a **Retrieval-Augmented Generation (RAG)** model that allows users to **upload documents** (PDF, Word, or Text) and ask questions about their contents. It leverages **LangChain, Pinecone, and Gemini AI** to provide intelligent, context-aware responses.

---

## 🚀 Features

✅ **Supports Multiple Document Formats** (PDF, TXT, DOCX)\
✅ **AI-Powered Question Answering** with Context Retrieval\
✅ **Fast and Efficient Embeddings** using Google Gemini AI\
✅ **Vector Search with Pinecone** for accurate information retrieval\
✅ **Built with Streamlit for an Interactive UI**

---

## 🛠 Tech Stack

- **Python** 🐍
- **Streamlit** (for UI)
- **LangChain** (for processing and retrieval)
- **Pinecone** (Vector database)
- **Google Gemini AI** (for embeddings & chat model)
- **PyPDFLoader, TextLoader, UnstructuredWordDocumentLoader** (for document parsing)

---

## 📂 Installation Guide

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/your-repo/ai-document-assistant.git
cd ai-document-assistant
```

### 2️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 3️⃣ Set Up API Keys

- Replace `pinecone_key` with your Pinecone API Key.
- Replace `google_api_key` with your Google Gemini API Key.

### 4️⃣ Run the Application

```sh
streamlit run app.py
```

---

## 📖 How to Use

1️⃣ **Upload a document** (PDF, TXT, or DOCX).\
2️⃣ **Enter a question** related to the document.\
3️⃣ **Get an AI-powered answer** based on the document content.

---

## 🎯 Future Enhancements

- 🔊 **Voice Input for Queries**
- 📊 **Support for Excel & CSV File Analysis**
- 🤖 **Integration with GPT-4 for Improved Accuracy**

---



