# 📄 Document Question Answering System (RAG)

## 📌 Overview

This project implements a **Retrieval-Augmented Generation (RAG)** system that answers questions based on a custom PDF document. The system retrieves the most relevant information from the document using semantic search and generates accurate answers using Google's Gemini Large Language Model.

For this project, my resume PDF was used as the knowledge source to demonstrate document-based question answering.

---

## 🎯 Objective

To build a simple RAG pipeline that:

- Loads a PDF document
- Splits the document into smaller chunks
- Generates embeddings for each chunk
- Stores embeddings in a FAISS vector database
- Retrieves the most relevant document chunks
- Uses Google Gemini to generate context-aware answers

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- LangChain
- FAISS
- Sentence Transformers
- Google Gemini API
- PyPDF
- Hugging Face

---

## 📂 Project Structure

```
Document_Question_Answering_System_RAG/
│
├── Document_Question_Answering_System_RAG.ipynb
├── Swasti_Jain_PIET23CS162.pdf
├── README.md
└── requirements.txt
```

---

## ⚙️ Workflow

1. Load the PDF document.
2. Extract text using PyPDFLoader.
3. Split the text into smaller chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector database.
6. Accept a user question.
7. Retrieve the most relevant chunks.
8. Send the retrieved context to Google Gemini.
9. Generate and display the final answer.

---

## 🚀 Features

- Document-based Question Answering
- Semantic Search using FAISS
- Context-aware Responses
- Google Gemini Integration
- Easy to use and extend
- Supports any PDF document

---

## 📌 Sample Questions

- What are my technical skills?
- What internships have I completed?
- List my projects.
- What programming languages do I know?
- What is my career objective?
- What achievements are mentioned?

---

## 📷 Example Output

**Question**

```
What are my technical skills?
```

**Answer**

```
Programming Languages:
- Java
- Python
- SQL
- JavaScript

Machine Learning:
- XGBoost
- Scikit-learn
- Model Evaluation
- Feature Engineering

Cloud & DevOps:
- Docker Basics
- AWS Fundamentals
- Azure Fundamentals

Tools:
- Git
- GitHub
- Streamlit
- Hugging Face
```

---

## 📋 Installation

Install the required libraries:

```bash
pip install langchain
pip install langchain-community
pip install langchain-google-genai
pip install langchain-text-splitters
pip install sentence-transformers
pip install faiss-cpu
pip install pypdf
```

---

## ▶️ How to Run

1. Clone or download the project.
2. Install the required libraries.
3. Add your Google Gemini API key.
4. Open the Jupyter Notebook.
5. Run all cells in order.
6. Enter your question.
7. View the generated answer.

---

## 📈 Future Improvements

- Support multiple PDF documents
- Add a Streamlit web interface
- Store vector database locally
- Chat history support
- Hybrid search (Keyword + Semantic Search)

---

## 👩‍💻 Author

**Swasti Jain**

B.Tech Computer Science Engineering

Poornima Institute of Engineering & Technology

Celebal Technologies Internship Assignment

---

## 📄 License

This project is developed for educational and internship purposes.
