Built a retrieval-augmented question-answering pipeline that loads the university handbook PDF, splits text into overlapping chunks, generates embeddings, and stores them in a Chroma vector database.
Retrieved the five most similar chunks for a question and passed the retrieved context to a local Llama 3 model via Ollama; the prompt instructs the model to answer from context and admit when it does not know.
Python, LangChain, ChromaDB, Ollama (Llama 3), nomic-embed-text, PyMuPDF, Streamlit
