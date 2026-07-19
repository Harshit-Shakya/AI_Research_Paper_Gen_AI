# 📚 AI Research Paper Intelligence System

## 🔎 About the Project

**AI Research Paper Intelligence System** is an intelligent research assistance platform designed to simplify the process of discovering, retrieving, understanding, and comparing machine learning research papers.

The system allows users to search through a large collection of research papers using natural language queries. Rather than depending only on traditional keyword-based matching, it uses **Sentence Transformer embeddings** and **FAISS** to perform semantic similarity search and identify papers that are contextually relevant to the user's query.

After retrieving relevant papers, the system uses **Large Language Models (LLMs)** through **LangChain** to summarize content, extract useful information, compare multiple papers, and assist users in understanding research literature more efficiently.

---

## 🌟 Key Capabilities

🔍 **Semantic Paper Search** — Finds research papers based on contextual similarity rather than exact keyword matches.

📄 **Automated Summarization** — Generates concise AI-based summaries of retrieved research papers.

🤖 **LLM Research Assistant** — Uses a Large Language Model to assist with research-related queries and analysis.

📚 **Efficient Vector Retrieval** — Uses FAISS for fast similarity search across stored paper embeddings.

🧠 **Semantic Embeddings** — Generates vector representations using Sentence Transformers.

🏷 **Keyword Identification** — Extracts important keywords and topics from research content.

⚖ **Paper Comparison** — Helps compare multiple relevant research papers.

💬 **Natural Language Interaction** — Allows users to search using simple natural language queries.

🔧 **LangChain Integration** — Connects different AI tools and components through a LangChain-based pipeline.

---

## 🧰 Technologies Used

| Component               | Technology                  |
| ----------------------- | --------------------------- |
| Programming Language    | Python                      |
| Research Dataset        | ML-ArXiv Papers Dataset     |
| Embedding Model         | all-MiniLM-L6-v2            |
| Vector Store            | FAISS                       |
| AI Framework            | LangChain                   |
| Large Language Model    | Groq (Llama 3.1 8B Instant) |
| NLP Library             | Sentence Transformers       |
| Keyword Extraction      | KeyBERT                     |
| Development Environment | Jupyter Notebook            |

---

## 🗂 Repository Layout

```text
AI-Research-Paper-Intelligence-System/
│
├── Coding_Blocks_Research_Paper_Intelligence_System.ipynb
├── paper_faiss.index
├── README.md
└── requirements.txt
```

---

## 🔄 How the System Works

The complete processing pipeline follows these steps:

1. The **ML-ArXiv research paper dataset** is loaded into the system.
2. Research paper **titles and abstracts** are cleaned and preprocessed.
3. **Sentence Transformers** are used to convert the textual data into embeddings.
4. The generated embeddings are stored inside a **FAISS vector index**.
5. The user provides a research topic or query in natural language.
6. The query is converted into an embedding and matched against the FAISS index.
7. The most semantically relevant research papers are retrieved.
8. An **LLM** generates summaries of the selected papers.
9. Important keywords are extracted from the research content.
10. Multiple papers can be compared, and the final results are presented to the user.

---

## 🏗 System Architecture

```text
                 ┌───────────────┐
                 │  User Query   │
                 └───────┬───────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Sentence Transformer │
              └──────────┬───────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Query Embedding │
                └────────┬────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ FAISS Search     │
                │ Index            │
                └────────┬─────────┘
                         │
                         ▼
             ┌─────────────────────────┐
             │ Most Relevant Research  │
             │ Papers                  │
             └───────────┬─────────────┘
                         │
                         ▼
               ┌────────────────────┐
               │ LangChain Pipeline │
               └─────────┬──────────┘
                         │
             ┌───────────┼───────────┐
             │           │           │
             ▼           ▼           ▼
       Summarization   Keywords   Comparison
             │           │           │
             └───────────┼───────────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ AI Response   │
                 └───────────────┘
```

---

## ⚙️ Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Research-Paper-Intelligence-System.git
cd AI-Research-Paper-Intelligence-System
```

### 2. Install Required Packages

Install all project dependencies using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Step 1: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 2: Execute the Notebook

Open the project notebook and run all cells in the correct sequence.

### Step 3: Provide a Research Query

For example:

```text
Deep Learning for Medical Image Reconstruction
```

Based on the query, the system will:

* Find semantically similar research papers
* Generate AI-based summaries
* Identify important keywords
* Compare related research papers

---

## 💡 Sample Research Queries

You can test the system with topics such as:

* Transformer Models for NLP
* Deep Learning for Medical Imaging
* Reinforcement Learning
* Explainable AI
* Computer Vision
* Federated Learning
* Graph Neural Networks
* AI in Healthcare

---

## 🚀 Planned Enhancements

Possible future extensions of the project include:

* Building a Streamlit-based web application
* Adding research paper PDF upload functionality
* Generating research reports in PDF and DOCX formats
* Automatically generating citations
* Developing a multi-agent research workflow
* Creating an interactive analytics dashboard
* Enabling conversations with uploaded research papers
* Implementing RAG-based question answering

---

## 🎓 Skills and Learning Outcomes

Through this project, practical understanding and implementation experience are demonstrated in the following areas:

* Natural Language Processing (NLP)
* Semantic Search
* Vector Databases
* Sentence Embeddings
* Large Language Models (LLMs)
* LangChain
* AI Agents
* Retrieval-Augmented Generation (RAG)
* Information Retrieval

---

## 📜 License

This project has been created for **educational and research purposes**.

---

## 👨‍💻 Author

**Harshit Shakya**


