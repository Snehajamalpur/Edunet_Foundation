# Edunet_Foundation
# Retrieval Augmented Generation (RAG) with Langchain and IBM Granite Models

This repository contains a Google Colab notebook (`RAG_with_Langchain.ipynb`) demonstrating how to implement Retrieval Augmented Generation (RAG) using the Langchain framework with IBM Granite models for embeddings and language generation.

The notebook covers the following steps:

1.  **Environment Setup:** Installing necessary libraries.
2.  **Component Selection:** Choosing an embeddings model (IBM Granite Embedding 30M English), a vector database (Milvus Lite), and a Large Language Model (IBM Granite 3.3-8B Instruct).
3.  **Building the Vector Database:** Downloading a sample document (State of the Union address), splitting it into chunks, and storing the text embeddings in the vector database.
4.  **Querying the Vector Database:** Performing a similarity search to retrieve relevant document chunks based on a user query.
5.  **Answering Questions with RAG:** Automating the RAG pipeline to use the retrieved context to generate a coherent answer to the user's question using the selected LLM.

This notebook provides a practical example of setting up and running a RAG pipeline for question answering over a custom knowledge base.

<img width="1918" height="882" alt="image" src="https://github.com/user-attachments/assets/47151f8f-00f4-4e65-a084-b3cc5d6892b6" />
<img width="1912" height="890" alt="image" src="https://github.com/user-attachments/assets/04fce23b-67a1-40ad-907a-252f02204e45" />
<img width="1913" height="886" alt="image" src="https://github.com/user-attachments/assets/f672391e-581d-40c7-81f0-868206ca369a" />
<img width="1914" height="884" alt="image" src="https://github.com/user-attachments/assets/add71554-c86e-4353-9144-393160678c7e" />
<img width="1916" height="889" alt="image" src="https://github.com/user-attachments/assets/61d81b85-eff8-434d-949b-b6e9c4aa7cf1" />











Absolutely! Here's a clear, concise, and **human-friendly** `README.md` that makes your project both **professional and approachable** — optimized for anyone visiting your GitHub, whether they're a beginner or experienced AI engineer:

---

# 🧠 Retrieval-Augmented Generation (RAG) using Langchain & IBM Granite | Edunet Foundation

Welcome! This repository showcases a practical implementation of **RAG (Retrieval-Augmented Generation)** using [Langchain](https://www.langchain.com/), **IBM Granite Models**, and **Milvus Lite vector database** — built as part of my learning journey with **Edunet Foundation** 🚀.

## 📘 What This Project Does

It answers user questions by:

1. Breaking a document into small chunks,
2. Finding the most relevant chunks using vector search,
3. Using a powerful language model to generate human-like answers based on those chunks.

Think of it like: “smart Google + ChatGPT that reads your PDFs.”

---

## 🛠️ Tech Stack Used

| Component  | Tool/Model Used                   |
| ---------- | --------------------------------- |
| LLM        | IBM Granite 3.3-8B Instruct       |
| Embeddings | IBM Granite Embedding 30M English |
| Vector DB  | Milvus Lite (lightweight, fast)   |
| Framework  | Langchain                         |
| IDE        | Google Colab Notebook             |

---

## 📚 What You'll Learn

In this notebook, you'll:

* ✅ Install and set up Langchain + IBM models
* ✅ Load a custom document (State of the Union)
* ✅ Split the document into readable pieces
* ✅ Store those in a vector database
* ✅ Ask a question & retrieve the most relevant chunks
* ✅ Generate an accurate, AI-powered answer using RAG pipeline

---

## 🔍 Why This Project Matters

RAG is the future of **context-aware AI**. It allows you to build systems that don’t just “guess” but **know** what they’re talking about by pulling in the right information.

Whether you're working on chatbots, customer support, or document Q\&A systems — this project is your entry point.

---

## 🖼️ Screenshots

Here are a few glimpses from the Colab notebook 👇

![Screenshot 1](https://github.com/user-attachments/assets/47151f8f-00f4-4e65-a084-b3cc5d6892b6)
![Screenshot 2](https://github.com/user-attachments/assets/04fce23b-67a1-40ad-907a-252f02204e45)
![Screenshot 3](https://github.com/user-attachments/assets/f672391e-581d-40c7-81f0-868206ca369a)
![Screenshot 4](https://github.com/user-attachments/assets/add71554-c86e-4353-9144-393160678c7e)
![Screenshot 5](https://github.com/user-attachments/assets/61d81b85-eff8-434d-949b-b6e9c4aa7cf1)

---

## 🧠 About Me

I'm **Sneha Jamalpur**, a B.Tech CSE student passionate about building with AI/ML, Cloud, and modern dev tools. This project was completed as part of the **Edunet Foundation AI-ML Bootcamp** with support from IBM SkillsBuild.

👉 [Connect with me on LinkedIn](https://www.linkedin.com/in/sneha-jamalpur)

