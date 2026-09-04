<div align="center">

# Abdulraheem Bawazir

### Artificial Intelligence Engineer

**RAG · LLM Applications · Machine Learning · NLP · Deep Learning**

Building intelligent systems that move beyond demos into structured, tested, and deployable AI applications.

📍 Abu Dhabi, United Arab Emirates

<br>

<a href="https://www.linkedin.com/in/abdulrheembawazir">
  <img src="https://img.shields.io/badge/LinkedIn-Abdulraheem_Bawazir-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:abdulrheembawazir9@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</div>

---

## About Me

I am an **Artificial Intelligence Engineering graduate** focused on building practical AI systems around **Large Language Models, Retrieval-Augmented Generation, Machine Learning, Natural Language Processing, and intelligent applications**.

My work ranges from designing complete **RAG pipelines and local LLM systems** to building **conversational AI applications, deep learning models, and data-driven backend systems**.

I am particularly interested in the engineering behind reliable AI: retrieval quality, grounding, evaluation, APIs, model integration, testing, containerization, and production-oriented system design.

* 🎓 B.Sc. in **Artificial Intelligence Engineering**
* 💼 AI Intern at **Abu Dhabi Islamic Bank (ADIB)**
* 🧠 Building with **RAG, LLMs, NLP, Machine Learning, and Deep Learning**
* ⚙️ Interested in turning AI prototypes into **reliable end-to-end systems**
* 📍 Based in **Abu Dhabi, UAE**

---

# Featured AI Engineering Project

## 🧠 NexusRAG

### Production-Style Local-First Retrieval-Augmented Generation System

> A complete private-document RAG system built to expose and implement the major components of modern retrieval-augmented generation rather than hiding them behind a high-level framework.

[![Repository](https://img.shields.io/badge/View_Repository-NexusRAG-181717?style=for-the-badge\&logo=github)](https://github.com/Abdulraheem-Bawazir/NexusRAG)

### Architecture

```text
PDF / DOCX / TXT
        │
        ▼
Document Ingestion
        │
        ▼
     Chunking
        │
        ├───────────────┐
        ▼               ▼
 MiniLM Embeddings     BM25
        │               │
        ▼               │
    ChromaDB            │
        │               │
        └───────┬───────┘
                ▼
      Reciprocal Rank Fusion
                │
                ▼
         Retrieved Evidence
                │
                ▼
          Grounded Prompt
                │
                ▼
         Qwen3 via Ollama
                │
                ▼
     Answer + Validated Citations
                │
        ┌───────┼────────┐
        ▼       ▼        ▼
     FastAPI    MCP     Web UI
                │
                ▼
        Docker / CI / Testing
```

### Engineering Highlights

* 📄 PDF, DOCX, and TXT document ingestion
* ✂️ Deterministic document chunking with metadata preservation
* 🧠 Local `all-MiniLM-L6-v2` embeddings
* 🗃️ Persistent ChromaDB vector storage
* 🔎 Semantic retrieval
* 🔤 BM25 lexical retrieval
* 🔀 Hybrid search using Reciprocal Rank Fusion
* 🤖 Local Qwen3 generation through Ollama
* 📚 Grounded answers with source and page citations
* 🛡️ Insufficient-evidence handling
* 📊 Retrieval and citation evaluation
* ⚡ FastAPI REST API
* 🔌 Model Context Protocol integration
* 🐳 Docker and Docker Compose deployment
* 🔄 GitHub Actions CI
* 🔍 Request IDs and observability
* ✅ **179 automated tests passing**

**Core Technologies**

`Python` · `RAG` · `LLMs` · `NLP` · `FastAPI` · `ChromaDB` · `BM25` · `Ollama` · `Qwen3` · `MCP` · `Docker` · `GitHub Actions`

---

# Selected Projects

<table>
<tr>
<td width="50%" valign="top">

## 🤖 SophiAI

**AI-Powered Smart Personal Assistant**

Cross-platform conversational AI application that transforms natural-language voice commands into structured schedules, reminders, and productivity actions.

### Highlights

* Voice-based interaction
* Speech transcription
* Natural-language intent extraction
* Intelligent scheduling
* Conflict detection
* Alternative-time suggestions
* Recurring tasks
* Real-time Firebase synchronization
* AI productivity features

**Stack**

`React Native` `Expo` `OpenAI` `Firebase` `JavaScript`

<br>

[![View Project](https://img.shields.io/badge/View_Project-SophiAI-181717?style=flat-square\&logo=github)](https://github.com/Abdulraheem-Bawazir/SophiAI-Showcase)

</td>

<td width="50%" valign="top">

## 🏭 Predictive Maintenance

**Hybrid CNN–LSTM Machine Failure Classification**

Deep-learning project exploring machine-failure prediction from industrial sensor data using the AI4I 2020 Predictive Maintenance dataset.

### Highlights

* Industrial sensor preprocessing
* Hybrid 1D CNN–LSTM architecture
* Classification pipeline
* Model training and validation
* Precision / Recall / F1 evaluation
* Imbalanced-data analysis

**Stack**

`Python` `TensorFlow` `Keras` `scikit-learn` `Pandas` `NumPy`

<br>

[![View Project](https://img.shields.io/badge/View_Project-Predictive_Maintenance-181717?style=flat-square\&logo=github)](https://github.com/Abdulraheem-Bawazir/Predictive-Maintenance-CNN-LSTM)

</td>
</tr>

<tr>
<td width="50%" valign="top">

## ✈️ Flight DBMS

**Flight Management Database System**

Relational database system supporting airline operations including flights, schedules, bookings, tickets, payments, aircraft, airports, users, and roles.

### Highlights

* Relational database architecture
* 10 core database tables
* PostgreSQL constraints and indexes
* PL/pgSQL procedures and functions
* Database triggers
* SQL analytics
* Flask web application
* Authentication and CRUD workflows

**Stack**

`PostgreSQL` `SQL` `PL/pgSQL` `Python` `Flask` `Supabase`

<br>

[![View Project](https://img.shields.io/badge/View_Project-Flight_DBMS-181717?style=flat-square\&logo=github)](https://github.com/Abdulraheem-Bawazir/CMPE-344-Project-FlightDBMS)

</td>

<td width="50%" valign="top">

## 🔬 What I'm Building Toward

My portfolio is increasingly focused on the engineering required to build dependable AI applications:

* Retrieval-Augmented Generation
* LLM application architecture
* AI agents and tool integration
* Semantic search
* Vector databases
* Model Context Protocol
* AI evaluation
* Local AI infrastructure
* Containerized AI services
* Production-oriented APIs

I am especially interested in systems where **AI, backend engineering, data, and deployment meet**.

</td>
</tr>
</table>

---

# AI & Machine Learning Stack

### Artificial Intelligence

![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented_Generation-8A2BE2?style=flat-square)
![LLMs](https://img.shields.io/badge/LLMs-Large_Language_Models-412991?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-Natural_Language_Processing-00897B?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-ML-FF6F00?style=flat-square)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-Neural_Networks-CC0000?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=flat-square\&logo=openai\&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLMs-000000?style=flat-square)

### RAG & AI Infrastructure

![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_Database-F4B400?style=flat-square)
![BM25](https://img.shields.io/badge/BM25-Lexical_Retrieval-005571?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-5A29E4?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-API-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square\&logo=docker\&logoColor=white)

### Machine Learning & Data

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square\&logo=tensorflow\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square)

### Backend, Database & Cloud

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square\&logo=firebase\&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square\&logo=supabase\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square\&logo=flask\&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square\&logo=microsoftazure\&logoColor=white)

### Application Development

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square\&logo=react\&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square\&logo=expo\&logoColor=white)

### Engineering Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square\&logo=visualstudiocode\&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square\&logo=androidstudio\&logoColor=white)

---

# Engineering Mindset

I like understanding what happens **inside the system**, not only connecting APIs together.

For AI projects, that means thinking about:

```text
Data
  ↓
Preprocessing
  ↓
Representation / Embeddings
  ↓
Retrieval or Model Inference
  ↓
Evaluation
  ↓
API / Application Integration
  ↓
Testing
  ↓
Deployment
  ↓
Monitoring & Improvement
```

My goal is to build AI systems that are not only intelligent, but also **measurable, testable, maintainable, and useful**.

---

# Certifications

* 🎓 Microsoft Azure AI Fundamentals
* ☁️ Microsoft Azure Machine Learning & MLOps
* 🧠 Deep Learning & Neural Networks
* 💬 Natural Language Processing
* 🤖 Microsoft Copilot Studio

---

# Current Focus

```python
abdulraheem = {
    "role": "Artificial Intelligence Engineer",
    "location": "Abu Dhabi, UAE",
    "building": [
        "Retrieval-Augmented Generation Systems",
        "LLM Applications",
        "AI Agents",
        "Machine Learning Systems",
        "NLP Applications",
    ],
    "learning": [
        "Advanced RAG",
        "AI Evaluation",
        "Agentic AI",
        "Local LLM Infrastructure",
        "Production AI Engineering",
    ],
}
```

---

<div align="center">

## Let's Connect

I'm interested in opportunities where I can contribute to **AI engineering, machine learning, NLP, LLM applications, and intelligent systems** while continuing to grow as an engineer.

<br>

<a href="https://www.linkedin.com/in/abdulrheembawazir">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:abdulrheembawazir9@gmail.com">
  <img src="https://img.shields.io/badge/Email-Get_In_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

<br><br>

**Abdulraheem Bawazir**
Artificial Intelligence Engineer · Abu Dhabi, UAE

</div>
