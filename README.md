# <center> 🌐 🔤 <font color = 'pink'>**Data Science Concept Assistant**</font></center>

Semantic Question Answering system designed to retrieve and generate accurate responses for data science and machine learning concepts using transformer-based embeddings and retrieval pipelines.

---

## 🧠 Problem Description

Understanding technical concepts in data science often requires navigating large volumes of fragmented educational content, documentation, and community-generated explanations.

This project explores a semantic Question Answering (QA) pipeline that combines dense vector embeddings, similarity search, and transformer-based text generation to retrieve contextually relevant information and generate concise educational answers.

The system focuses on semantic retrieval quality and qualitative answer generation for machine learning and data science-related questions.

---

## 📊 Inference & Qualitative Evaluation of Outputs

The evaluation was performed through qualitative human assessment using both in-domain and out-of-domain questions.

The system was tested on:

* Machine learning concepts
* Data science terminology
* Statistical learning questions
* General AI-related prompts

The retrieval pipeline demonstrated stronger performance on in-domain educational queries, while maintaining acceptable semantic relevance on unseen prompts.

---

## ⚙️ Requirements & Installation

```bash
pip install torch transformers sentence-transformers langchain faiss-cpu gradio datasets accelerate
```

> Requires Python 3.10+

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/your-repo.git

cd your-repo

jupyter notebook
```

Open the notebook and run all cells sequentially.

---

## 📁 Project Structure

```bash
├── notebook.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🧪 Models Used

### Embedding Model

* sentence-transformers/all-MiniLM-L6-v2

### Generative QA Model

* google/flan-t5-large

---

## 📚 Datasets

* `mjphayes/machine_learning_questions`
* `team-bay/data-science-qa`
* `databricks/databricks-dolly-15k`

---

## 🛠️ Technologies Used

* FAISS
* LangChain
* Hugging Face Transformers
* Sentence Transformers
* Gradio

---

## 🎯 Objective

The goal of this project is to investigate how semantic retrieval pipelines and transformer-based language models can improve educational Question Answering systems for data science and machine learning concepts.
