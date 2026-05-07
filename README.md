````markdown
#Healthcare Knowledge Base RAG Chatbot

An AI-powered Retrieval-Augmented Generation (RAG) chatbot built in Jupyter Notebook using LangChain, Google Gemini API, ChromaDB, and Gradio.

The project answers healthcare-related queries using semantic search over hospital review datasets instead of relying only on LLM memory.

---

# Features

- Retrieval-Augmented Generation (RAG) pipeline
- Semantic document retrieval using embeddings
- Google Gemini LLM integration
- ChromaDB vector database support
- Context-aware response generation
- Gradio-based chatbot interface
- Prompt engineering for hallucination reduction
- Modular LangChain workflow implementation

---

# Tech Stack

## Languages
- Python

## Libraries & Frameworks
- LangChain
- Gradio
- Pandas

## AI / NLP
- Google Gemini API
- Gemini Embeddings
- Retrieval-Augmented Generation (RAG)
- Semantic Search

## Database
- ChromaDB

---

# Project Workflow

```text
Hospital Reviews CSV
        ↓
Document Processing
        ↓
Embedding Generation
        ↓
ChromaDB Vector Storage
        ↓
User Query
        ↓
Semantic Similarity Search
        ↓
Relevant Context Retrieval
        ↓
Gemini LLM Response Generation
        ↓
Final Context-Aware Response
````

---

# How It Works

1. Hospital review data is loaded from CSV datasets.
2. Reviews are converted into vector embeddings using Gemini embedding models.
3. Embeddings are stored in ChromaDB for semantic retrieval.
4. User queries are converted into embeddings.
5. Relevant documents are retrieved using similarity search.
6. Retrieved context is passed into the Gemini model.
7. The chatbot generates grounded responses using retrieved knowledge.

---

# Running the Notebook

## Clone Repository

```bash
git clone https://github.com/your-username/healthcare-rag-chatbot.git
cd healthcare-rag-chatbot
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Required Libraries

```bash
pip install langchain
pip install langchain-google-genai
pip install chromadb
pip install pandas
pip install gradio
```

---

# Environment Variable

Create a `.env` file or directly configure your API key inside the notebook:

```python
GOOGLE_API_KEY="your_api_key_here"
```

---

# Launch Notebook

```bash
jupyter notebook
```

Open:

```text
18_Chat_with_Your_Knowledge_Base_Building_a_Powerful_RAG_Chatbot.ipynb
```

Run all cells sequentially.

---

# Example Queries

* “Which hospitals have positive patient feedback?”
* “What are common complaints in reviews?”
* “Which hospitals are recommended most frequently?”
* “Summarize reviews related to emergency care.”

---

# Repository Structure

```text
├── 18_Chat_with_Your_Knowledge_Base_Building_a_Powerful_RAG_Chatbot.ipynb
├── reviews.csv
├── Outputs/
├── README.md
└── requirements.txt
```

---

# Key Concepts Used

* Retrieval-Augmented Generation (RAG)
* Vector Embeddings
* Semantic Search
* Prompt Engineering
* Context Injection
* Vector Databases
* LLM Orchestration

---

# Future Improvements

* PDF document ingestion
* Multi-file knowledge base support
* Persistent chat memory
* FastAPI backend deployment
* Cloud deployment on Azure/AWS
* Streaming responses

---

# Resume Highlights

* Built a healthcare-focused RAG chatbot using LangChain and Gemini API
* Implemented semantic retrieval using ChromaDB vector database
* Developed modular AI pipelines for contextual response generation
* Integrated Gradio UI for interactive chatbot interaction

---

# Author

Harshit Rana
