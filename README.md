# 🤖 ChatPDF AI (RAG-based PDF Chatbot)

A ChatGPT-like AI application that allows users to upload PDFs and ask questions using **Retrieval-Augmented Generation (RAG)**.

Built using **LangChain, OpenAI, FAISS, and Streamlit**.

---

## 🚀 Features

- 📄 Upload any PDF
- 💬 Ask questions in natural language
- 🧠 Context-aware answers using RAG
- 📚 Source-based responses (with page reference)
- 🔁 Conversation memory (chat history)
- 🎨 Clean ChatGPT-like UI using Streamlit

---

## 🧠 How It Works

1. PDF is loaded and split into smaller chunks  
2. Text is converted into embeddings  
3. Stored in a FAISS vector database  
4. User query → relevant chunks retrieved  
5. LLM generates answer using retrieved context  

👉 This approach is called **RAG (Retrieval-Augmented Generation)**

---

## ⚙️ Tech Stack

- Python  
- LangChain  
- OpenAI  
- FAISS  
- Streamlit  
- Python-dotenv  

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/chatpdf-rag-langchain.git
cd chatpdf-rag-langchain

2. Install dependencies
pip install langchain==0.2.14 langchain-community==0.2.12 langchain-core==0.2.36 langchain-openai==0.1.22 langchain-text-splitters==0.2.2 langsmith==0.1.147 faiss-cpu python-dotenv pypdf streamlit
🔐 Setup Environment Variables

Create a .env file in the root directory:

OPENAI_API_KEY=your_api_key_here
▶️ Run the Application
streamlit run app.py
<img width="1891" height="811" alt="image" src="https://github.com/user-attachments/assets/057ddf35-85bc-46ac-8332-b9120e48994e" />


Add your screenshots or demo video here

📌 Use Cases

Resume analysis

Research paper Q&A

Documentation assistant

Internal knowledge chatbot
