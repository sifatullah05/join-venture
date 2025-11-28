# AI-Powered Chatbot for Financial Policy Document

This repository contains an AI-powered chatbot designed to answer questions about a **financial policy document**. The chatbot uses **Deep Learning (BERT)** for question answering and **Machine Learning** (via **Sentence Transformers**) for embedding-based search of document sections.

The chatbot is capable of:
- **Understanding questions in both English and Bengali**.
- **Extracting key information** from a PDF document (e.g., energy policy, budget, etc.).
- **Providing answers based on the extracted data**.
- **Using conversation memory** to recall previous user queries and responses.

## Features
- **Question Answering (QA)**: Uses BERT for question answering based on context from the policy document.
- **Text Search**: Utilizes **Faiss** for fast retrieval of relevant document sections.
- **Multiple Language Support**: Supports both English and Bengali queries.
- **Embedding Search**: Uses **Sentence Transformers** for creating embeddings of document chunks and querying them using Faiss.

## Requirements

Before running the chatbot, you'll need to install the required dependencies. You can do this by running:


