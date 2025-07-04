# 🦙 FastAPI + Ollama Prompt Generation API

This project provides a simple RESTful API using **FastAPI** and **Ollama** to generate responses based on a user's prompt using a language model (e.g., LLaMA 3.2).  
It also includes **API key verification** and a basic **credit tracking system**.

---

## 🚀 Features

- ✅ REST API endpoint to generate text completions.
- 🔐 API Key authentication via `x-api-key` header.
- 💳 Simple credit-limiting system per API key.
- 🤖 Uses [Ollama](https://ollama.com) to access a language model.

---

## 📦 Requirements

- Python 3.8+
- FastAPI
- Ollama
- requests
- python-dotenv

Install requirements with:

```bash
pip install -r requirements.txt


