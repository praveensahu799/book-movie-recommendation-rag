# Book & Movie Recommendation Chatbot

This project explores a book and movie recommendation chatbot using Retrieval-Augmented Generation (RAG). It combines semantic search with a language model to find relevant information and generate responses based on the retrieved context.

## Features

- Semantic search for book and movie information
- Text embeddings using Sentence Transformers
- Similarity search with FAISS
- Context-based response generation using Google's Gemini API
- Notebook-based implementation for experimentation

## Tech Stack

- Python
- Jupyter Notebook
- Sentence Transformers (`all-MiniLM-L6-v2`)
- FAISS
- LangChain
- Google Gemini API

## Project Structure

```text
book-movie-recommendation-rag/
├── Chatbot_LLM_RAG.ipynb
└── README.md
```

## Note

The notebook uses local dataset paths, so these may need to be updated to match your environment. A valid Gemini API key and the required book and movie data files are needed to run the notebook.

## Author

**Praveen Sahu** · [GitHub](https://github.com/praveensahu799)
