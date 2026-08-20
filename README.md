# RAG App

A simple RAG (Retrieval-Augmented Generation) chatbot that answers questions about a PDF document using Google Gemini.

## Setup

1. Install dependencies:
```bash
uv sync
```

2. Get your Google API key from [Google AI Studio](https://aistudio.google.com/app/apikey) and add it to `.env`:
```
GOOGLE_API_KEY=your_api_key_here
```

## Run

```bash
uv run rag_app.py
```

The chatbot will load the employee handbook PDF and create a vector database. Then ask questions in the terminal.
