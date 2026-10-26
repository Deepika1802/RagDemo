# Space Exploration RAG Project

## About
This project uses Retrieval-Augmented Generation (RAG) to answer questions using information from a PDF document.

## Technologies Used
- Python
- PyPDF
- Sentence Transformers
- FAISS
- Groq API

## How It Works
1. Read text from a PDF.
2. Split the text into chunks.
3. Convert chunks into embeddings.
4. Store embeddings in a FAISS vector index.
5. Retrieve relevant chunks based on the user's question.
6. Generate an answer using a language model through Groq.

## Installation
Install the required libraries:

```bash
python -m pip install -r requirements.txt
```

Create a `.env` file locally and add your Groq API key:

```text
GROQ_API_KEY=your_actual_api_key
```

## Dataset
The project uses `dummyData.pdf` as its knowledge base.
