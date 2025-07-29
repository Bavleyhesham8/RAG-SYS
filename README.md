#  Retrieval-Augmented Generation (RAG) Based QA System (Arabic & English)

This is a graduation project demonstrating a **RAG-based Question Answering system** capable of handling both **Arabic and English** queries. It uses deep learning models to combine semantic search and natural language generation for accurate, context-aware responses.

---

##  Project Overview

Traditional QA systems often struggle with domain adaptation or multilingual input. Our system enhances performance by combining:

✅ **Semantic Retriever** — Locates relevant documents or context using sentence embeddings  
✅ **Generative Language Model** — Produces natural language answers using pre-trained transformers  
✅ **Multilingual Support** — Handles both **Arabic and English** questions and generates fluent responses

---

##  Key Features

- Supports **Arabic & English** text input and response generation  
- Uses **RAG architecture** for long-context and knowledge-grounded answering  
- Semantic indexing with **FAISS**  
- Context encoding via **Sentence-BERT**  
- Answer generation using **T5** and **BART** models from Hugging Face  
- Clear and modular Jupyter Notebook implementation  

---

##  Model Pipeline

1. **Text Preprocessing**
2. **Embedding with SentenceTransformers**
3. **Vector Indexing using FAISS**
4. **Context Retrieval (Top-k matching)**
5. **Answer Generation via Transformers (e.g. `t5-base`)**
6. **Arabic and English language handling** based on user input

---

## Evaluation & Visualization

The notebook includes:
- Answer comparisons in Arabic and English
- Examples of context retrieval
- Model output samples and interpretation

---

## Requirements

Main libraries:
- `transformers`
- `sentence-transformers`
- `faiss-cpu`
- `torch`
- `pandas`
- `numpy`


---

##  Use Case

This system can be applied to:

- 🎓 Educational question-answering systems  
- 🤖 AI-powered multilingual chatbots  
- 🧠 Knowledge assistants in Arabic-speaking environments  
- 📄 Domain-specific document Q&A (e.g., legal, healthcare)  

---

## Team Members

**Undergraduate students from the**  
**Faculty of Computers and Artificial Intelligence – Benha University**  
**Department**: Artificial Intelligence  

- 🧑‍💻 Ahmed Salem  
- 🧑‍💻 Mohamed Ramadan  
- 🧑‍💻 Bavley Hesham  

---

##  License

This project is intended for **academic and educational purposes only**.

---
