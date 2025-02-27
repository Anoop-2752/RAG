# 📚 RAG-Based PDF QA System

![RAG](https://img.shields.io/badge/RAG-Retrieval--Augmented--Generation-blue)  
A **Retrieval-Augmented Generation (RAG) system** that allows users to query PDF documents using **DeepSeek**, **Groq API**, and **FAISS** for efficient vector search. This system enhances traditional language models by incorporating document retrieval to provide more accurate, context-aware answers.

---

## 🧠 What is RAG (Retrieval-Augmented Generation)?  
RAG is an advanced AI technique that combines **retrieval-based search** with **generative AI models**. Instead of relying purely on pre-trained knowledge, RAG dynamically fetches relevant documents (e.g., PDFs) and uses them as context to generate responses. This ensures:
- **More accurate answers** based on up-to-date information
- **Better context understanding** by grounding responses in real documents
- **Improved scalability** for enterprise applications  

---

## 🚀 Features
✅ **Upload PDFs** and extract text automatically  
✅ **Vectorize documents** using **FAISS** for efficient retrieval  
✅ **Query system** via a user-friendly Streamlit UI  
✅ **Integrates with DeepSeek & Groq API** for accurate response generation  
✅ **Fast & scalable** with optimized embeddings  

---

## 🏗️ Technologies Used  

### 1️⃣ **DeepSeek (LLM)**
- **DeepSeek** is a **powerful large language model (LLM)** optimized for understanding and generating human-like responses.
- Used to **enhance document-based QA** by improving text comprehension and summarization.

### 2️⃣ **Groq API**
- **Groq** provides a **high-speed inference engine** optimized for LLMs.
- It allows **low-latency, real-time responses** while maintaining accuracy.

### 3️⃣ **FAISS (Facebook AI Similarity Search)**
- **FAISS** is an **open-source library** by Meta for **efficient similarity search**.
- It enables **fast document retrieval** by storing and searching through **vector embeddings**.

### 4️⃣ **LangChain**
- **LangChain** is a **framework** for building LLM-based applications.
-  It simplifies **document retrieval, embedding creation, and pipeline integration**.

---
### 📊 **How it Works**
1️⃣ **PDF Parsing**: Extracts text from PDF files using pdfplumber.

2️⃣ **Vector Embeddings**: Converts text into high-dimensional vectors using Hugging Face's sentence-transformers.

3️⃣ **FAISS Indexing**: Stores vectors in FAISS for fast nearest-neighbor search.

4️⃣ **Query Execution**: User inputs a question, and FAISS retrieves the most relevant document chunks.

5️⃣ **DeepSeek & Groq API**: The retrieved chunks are sent to DeepSeek, which generates a precise, contextualized answer.


---

### 🎯 **Future Improvements**
🚀 **Multi-PDF Support** – Query across multiple PDFs at once

🚀 **Hybrid Search** – Combine semantic search with keyword-based search for better accuracy

🚀 **Fine-Tuning LLM** – Train DeepSeek on domain-specific datasets

🚀 **Deploy on Cloud** – Host on AWS, GCP, or Azure for scalability





