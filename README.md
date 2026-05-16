# 📚 Smart Document Analyzer using RAG (Retrieval Augmented Generation)

An AI-powered Smart Document Analyzer built using **Retrieval Augmented Generation (RAG)** that allows users to upload documents and ask questions based on their content. The system retrieves relevant chunks from documents and generates accurate answers using LLMs.

---

## 🚀 Features

- 📄 Upload and process PDF documents
- 🔍 Intelligent document chunking and embedding
- 🧠 Semantic search using vector database (ChromaDB)
- 💬 Ask questions based on uploaded documents
- ⚡ Fast and accurate context-aware responses
- 🔄 Dynamic retrieval using retriever strategies (MMR, Multi-query, etc.)

---

## 🛠️ Tech Stack

- Python 🐍
- LangChain 🧠
- ChromaDB 📦
- MistralAI / LLM API 🤖
- PyPDF / document loaders 📄

---

## 📂 Project Structure
Smart-Document-Analyzer-RAG
│

├── main.py

├── create_database.py

├── requirements.txt

├── .gitignore

│

├── document loaders/

│ ├── pdf.py

│ ├── page.py

│ └── test.py

│

├── retrievers/

│ ├── mmr.py

│ ├── multiquery.py

│ └── arxiv.py

│

├── vector store/

│ └── DB.py

│

└── data (PDFs)


---

## ⚙️ How it Works

1. Load PDF documents
2. Split documents into chunks
3. Convert chunks into embeddings
4. Store embeddings in ChromaDB
5. User asks a question
6. Retrieve relevant chunks using similarity search
7. LLM generates final answer using retrieved context

---

## 🧪 Installation & Setup

```bash
# Clone repository
git clone https://github.com/your-username/Smart-Document-Analyzer-RAG.git

# Navigate to folder
cd Smart-Document-Analyzer-RAG

# Create virtual environment
python -m venv .venv
.venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
