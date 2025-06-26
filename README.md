<div align="center">
  <h1>🚀 AIQueryNet</h1>
  <p><i>Empowering Natural Language to SQL with Voice Support and RAG-Powered Precision</i></p>

  <img src="https://img.shields.io/badge/Built%20With-Python-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-Next.js-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-FastAPI-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vector%20Database-Pinecone-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Speech%20Recognition-Whisper-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Sentiment%20Analysis-NLP-purple?style=for-the-badge" />
</div>

---

## 🧰 Built With

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/Pinecone-4EA94B?style=for-the-badge&logo=pinecone" />
  <img src="https://img.shields.io/badge/Whisper-02042B?style=for-the-badge&logo=openai" />
  <img src="https://img.shields.io/badge/NLP-Sentiment%20Analysis-blueviolet?style=for-the-badge" />
</div>

---

## 📚 Table of Contents

- [🔍 Overview](#overview)
- [✨ Core Features](#core-features)
- [🚀 Getting Started](#getting-started)
- [🧱 Prerequisites](#prerequisites)
- [🔧 Installation](#installation)
- [🧪 Testing](#testing)
- [📈 Usage](#usage)
- [🙌 Contribution](#contribution)
- [📬 Contact](#contact)

---

## 🔍 Overview

**AIQueryNet** is an innovative open-source system designed to transform natural language queries, including voice inputs, into precise SQL queries using Retrieval-Augmented Generation (RAG). Leveraging Whisper for speech recognition, sentiment analysis for intent understanding, and Pinecone vector embeddings for semantic search, AIQueryNet delivers accurate and context-aware database interactions.

This project consists of two main repositories:
- [AIQueryNet Backend](https://github.com/mrshivamshaw/aiquerynet-backend)
- [AIQueryNet Frontend](https://github.com/mrshivamshaw/aiquerynet)

---

## ✨ Core Features

- 🗣️ **Voice Support with Whisper**  
  Convert spoken queries into text using OpenAI's Whisper model for seamless voice-to-SQL interactions.

- 🔐 **Sentiment Analysis for Intent Detection**  
  NLP-powered sentiment analysis enhances query understanding by capturing user intent.

- ⚙️ **Pinecone Vector Embeddings**  
  Boosts query relevance with semantic search and intent-aware vector retrieval for precise schema mapping.

- 💻 **Natural Language to SQL**  
  Transforms natural language inputs into accurate SQL queries, simplifying database interactions.

- ⚒️ **Scalable RAG Architecture**  
  Combines retrieval and generation for context-aware, efficient query processing.

---

## 🚀 Getting Started

Get AIQueryNet up and running in minutes by cloning the repositories and setting up the backend and frontend.

### 🧱 Prerequisites

Ensure the following are installed:
- Python (>=3.8)
- Node.js
- NPM
- Pinecone account and API key
- OpenAI API key (for Whisper and embeddings)

---

## 🔧 Installation

### Backend Setup
# Clone the backend repository
git clone https://github.com/mrshivamshaw/aiquerynet-backend.git
cd aiquerynet-backend

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
export PINECONE_API_KEY='your-pinecone-api-key'
export OPENAI_API_KEY='your-openai-api-key'

# Run the backend
fastapi run app.py
