# Medical Diagnosis Assistant — RAG Capstone 

A Retrieval-Augmented Generation system that combines patient medical histories and a
curated medical knowledge base to suggest possible diagnoses, using LangChain, FAISS,
sentence-transformers (embeddings), and OpenAI GPT-4o (generation).

## Folder contents

```
medical-rag-assistant-203791/
├── Medical_Diagnosis_Assistant_RAG.ipynb   # main capstone notebook
├── data/
│   ├── healthcare_patients.csv
│   └── healthcare_encounters.csv
├── requirements.txt
├── .env.example                                     # add your OpenAI key here
└── README.md
```

---

## Setup instructions

### 1. Create a Python virtual environment

**Windows (PowerShell):**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 2. Install dependencies
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 3. Add your OpenAI API key
Rename the `.env.example` file to `.env` and replace the placeholder:
```
OPENAI_API_KEY=sk-your-actual-key-here
```

### 4. Open and run the notebook
Open `Medical_Diagnosis_Assistant_RAG.ipynb` and then run all cells top to bottom

