# Rag_Chatbot

🔹 RAG-based Multi-Source Question Answering System

This project is a Retrieval-Augmented Generation (RAG) application built using Flask, FAISS, Sentence Transformers, and Groq LLMs.
It allows users to upload or provide data from multiple sources such as:

📄 PDF files

📝 Word & TXT documents

🌐 Website URLs

🎧 Audio files

▶️ YouTube videos

The system extracts text from these sources, converts it into vector embeddings, and stores them in a FAISS vector database.
When a user asks a question, the most relevant content is retrieved and passed to a Groq-hosted LLM (LLaMA) to generate accurate, context-aware answers.

🔹 Key Features

Multi-format document ingestion (PDF, DOCX, TXT, URL, Audio, YouTube)

Fast semantic search using FAISS

Context-aware responses using RAG

Conversation memory support

Audio & video transcription using Groq Whisper

Profanity filtering and secure file handling

🔹 Tech Stack

Backend: Flask, Python

Vector DB: FAISS

Embeddings: Sentence Transformers

LLM: Groq (LLaMA 3)

Speech-to-Text: Groq Whisper

Frontend: HTML, JS (Flask templates)

2️⃣ Steps to Create a Groq (Grok) API Key 🔑

⚠️ People often say “Grok API”, but the correct platform is Groq Cloud.

✅ Step-by-Step Guide
Step 1: Open Groq Cloud

Go to 👉 https://console.groq.com

Step 2: Sign Up / Login

Sign in using Google / GitHub / Email

Complete account verification

Step 3: Go to API Keys

Click on your profile icon (top right)

Select API Keys

Step 4: Create New API Key

Click “Create API Key”

Give it a name (example: rag-project-key)

Copy the key immediately 🔐
