# 🤖 Interactive PDF Chat System Using Localized LLMs

A privacy-first, locally-run application that lets users upload PDF documents and chat with them in natural language. Built using **Streamlit**, **LangChain**, and **Ollama’s DeepSeek model**, this tool processes PDFs, embeds document chunks, and generates answers using a local LLM—all without internet or API calls.

---

## 🔍 Project Description

**Interactive PDF Chat System Using Localized LLMs** is a private, locally-run app that lets you upload PDFs and ask questions in natural language. Powered by Streamlit, LangChain, and Ollama’s DeepSeek model, it delivers fast, accurate answers without needing the internet or APIs.

---

## 🚀 Features

- 🧠 Uses **DeepSeek-R1** (via Ollama) for local LLM-based reasoning  
- 📄 Upload and chat with any PDF document  
- 🔍 Embedding & semantic search using local vector database  
- 🖤 Dark-mode friendly chat UI via Streamlit  
- 🔐 100% offline – no cloud, no keys, full data privacy  

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/interactive-pdf-chat.git
cd interactive-pdf-chat
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Install Ollama and Pull the Model
Download Ollama from [https://ollama.com](https://ollama.com) and run:
```bash
ollama run deepseek-r1:1.5b
```

### 4. Launch the App
```bash
streamlit run app.py
```

---

## 📦 Requirements

- Python 3.9+
- [Ollama](https://ollama.com)
- Streamlit
- LangChain
- LangChain Community
- LangChain Ollama
- PDFPlumber

```bash
pip install -r requirements.txt
```

---

## 📁 Project Structure

```
interactive-pdf-chat/
├── app.py                      # Main Streamlit app
├── requirements.txt           # Python dependencies
├── document_store/
│   └── pdfs/                  # Uploaded PDFs stored here
├── assets/                    # (Optional) for UI assets
├── .gitignore
└── README.md
```

---

## ✨ Usage

1. Upload a PDF document from your local system.  
2. Once processed, enter a question in the chat input.  
3. The app will analyze the document and generate a concise response based on its content.

---

## 🔐 Local Privacy Advantage

Unlike traditional AI chat tools, **this app runs 100% locally**. No data leaves your system, making it ideal for confidential documents, research papers, internal reports, and more.

---

## 🧠 Powered By

- [LangChain](https://github.com/langchain-ai/langchain)  
- [Ollama](https://ollama.com/)  
- [DeepSeek Model](https://www.deepseek.com/)  
- [PDFPlumber](https://github.com/jsvine/pdfplumber)  

---

## 📄 License

This project is licensed under the MIT License.

---

## 💡 Future Improvements

- Multi-PDF indexing  
- Session memory for continuous chat context  
- Option to choose different LLMs (e.g., Mistral, LLaMA, Gemma)

---

## 🙌 Contribute

PRs and issues are welcome! If you'd like to contribute or suggest improvements, feel free to open a pull request.
