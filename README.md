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
