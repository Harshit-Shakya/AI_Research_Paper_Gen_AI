# 📚 AI Research Paper Intelligence System

An AI-powered research assistant that helps users discover, retrieve, summarize, compare, and analyze machine learning research papers using semantic search, large language models (LLMs), and vector databases.

## 🚀 Overview

The AI Research Paper Intelligence System enables users to search a large collection of machine learning research papers using natural language queries. Instead of relying on keyword matching, the system performs semantic similarity search using Sentence Transformers and FAISS to retrieve the most relevant papers.

The retrieved papers can then be summarized, compared, and analyzed using Large Language Models (LLMs) integrated through LangChain.

---

## ✨ Features

- 🔍 Semantic search over research papers
- 📄 AI-generated paper summaries
- 🤖 LLM-powered research assistant
- 📚 FAISS vector database for fast retrieval
- 🧠 Sentence Transformer embeddings
- 🏷 Keyword extraction
- ⚖ Research paper comparison
- 💬 Natural language querying
- 🔧 LangChain tool integration

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Dataset | ML-ArXiv Papers Dataset |
| Embedding Model | all-MiniLM-L6-v2 |
| Vector Database | FAISS |
| Framework | LangChain |
| LLM | Groq (Llama 3.1 8B Instant) |
| NLP | Sentence Transformers |
| Keyword Extraction | KeyBERT |
| Notebook | Jupyter Notebook |

---

## 📂 Project Structure

```
AI-Research-Paper-Intelligence-System/

│── Coding_Blocks_Research_Paper_Intelligence_System.ipynb
│── paper_faiss.index
│── README.md
│── requirements.txt
```

---

## ⚙️ Workflow

1. Load the ML-ArXiv research paper dataset.
2. Preprocess titles and abstracts.
3. Generate embeddings using Sentence Transformers.
4. Store embeddings in a FAISS vector index.
5. Accept a user's research query.
6. Retrieve the most relevant papers using semantic similarity.
7. Summarize the retrieved papers using an LLM.
8. Extract important keywords.
9. Compare multiple research papers.
10. Present the results to the user.

---

## 📊 Architecture

```
                User Query
                     │
                     ▼
          Sentence Transformer
                     │
                     ▼
             Query Embedding
                     │
                     ▼
             FAISS Search Index
                     │
                     ▼
      Top Relevant Research Papers
                     │
                     ▼
         LangChain Tool Pipeline
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼
 Summarization   Keywords     Comparison
      │              │              │
      └──────────────┼──────────────┘
                     ▼
              Final AI Response
```

---

## 📦 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/AI-Research-Paper-Intelligence-System.git
cd AI-Research-Paper-Intelligence-System
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open the Jupyter Notebook.

```bash
jupyter notebook
```

2. Run all notebook cells in sequence.

3. Enter your research query.

Example:

```
Deep Learning for Medical Image Reconstruction
```

The system will:

- Retrieve similar research papers
- Generate summaries
- Extract important keywords
- Compare related papers

---

## 📖 Example Queries

- Transformer models for NLP
- Deep Learning for Medical Imaging
- Reinforcement Learning
- Explainable AI
- Computer Vision
- Federated Learning
- Graph Neural Networks
- AI in Healthcare

---

## 🎯 Future Improvements

- Streamlit web application
- PDF upload support
- Research report generation (PDF/DOCX)
- Citation generation
- Multi-agent research workflow
- Interactive dashboard
- Chat with uploaded research papers
- RAG-based question answering

---

## 📈 Learning Outcomes

This project demonstrates practical knowledge of:

- Natural Language Processing (NLP)
- Semantic Search
- Vector Databases
- Sentence Embeddings
- Large Language Models (LLMs)
- LangChain
- AI Agents
- Retrieval-Augmented Generation (RAG)
- Information Retrieval

---

## 📜 License

This project is developed for educational and research purposes.

---

## 👨‍💻 Author

**Rituraj**

B.Tech Computer Science Engineering  
Delhi Technical Campus (GGSIPU)

GitHub: https://github.com/rituraj-cell

LinkedIn: https://www.linkedin.com/in/rituraj-raj-761ab7380
