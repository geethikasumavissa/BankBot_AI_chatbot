# 🏦 BankBot AI

An AI-powered Banking Chatbot built using Streamlit and Ollama.  
This chatbot assists users with banking-related queries, provides quick responses using a knowledge base, and generates intelligent replies using a local LLM.

---

## 🚀 Features

- User Authentication (Login / Signup)
- Multiple Chat Conversations
- Pin, Rename, Delete Chats
- Quick Access Buttons (Balance, Loans, Support)
- Dashboard with Financial Analytics
- Predefined Responses using JSON Knowledge Base
- AI-generated Responses using Ollama (Phi3)
- Restriction to Banking-related Queries Only

---

## 🛠️ Tech Stack

- Frontend & Backend: Streamlit
- AI Model: Ollama (Phi3)
- ML Support: Scikit-learn (TF-IDF, Cosine Similarity)
- Data Storage: JSON (users & knowledge base)
- Visualization: Matplotlib, Pandas

---

## 📂 Project Structure

BankBot-AI/
│── bankbot_app.py
│── bank_library.json
│── users.json
│── requirements.txt
│── README.md

---

## ⚙️ Installation

1. Clone Repository
git clone https://github.com/your-username/bankbot-ai.git
cd bankbot-ai

2. Install Dependencies
pip install -r requirements.txt

---

## 🤖 Setup Ollama

Download and install Ollama from:
https://ollama.com

Then run:
ollama pull phi3
ollama run phi3

---

## ▶️ Run Application

streamlit run bankbot_app.py

---

## 📊 Dashboard Features

- Account Balance Overview
- Loan Summary
- Credit Score Display
- Balance Growth Chart
- Expense Distribution Pie Chart

---

## 🔒 Banking Query Restriction

The chatbot only responds to banking-related queries such as:
- Loans
- Accounts
- Transactions
- Cards
- EMI, Interest

Non-banking queries are blocked.

---

## 📚 Knowledge Base

The chatbot works in 2 steps:
1. Checks predefined responses from JSON
2. If not found → generates AI response using Ollama

---

## ⚠️ Notes

- Ensure Ollama is running before starting the app
- Do not upload sensitive data (passwords, API keys) to GitHub
- users.json is for local storage only (not secure for production)

---

## 🔮 Future Enhancements

- Database integration (MySQL / Firebase)
- Secure authentication (JWT / OAuth)
- Cloud deployment (Streamlit Cloud / AWS)
- Multi-language support
- Voice-based chatbot

---

## 👩‍💻 Author

Developed as part of an AI Chatbot project.

---

## 📜 License

This project is for educational purposes.
