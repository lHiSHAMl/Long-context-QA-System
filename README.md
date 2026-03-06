# Long Context Question Answering System
A simple Retrieval-Augmented Generation (RAG) style Question Answering system built using Sentence Transformers, Cosine Similarity, and HuggingFace Transformers.
The system accepts a long document, splits it into chunks, retrieves the most relevant chunks using semantic similarity, and generates an answer using a language model.
# Features
Accepts long text documents
Splits text into chunks (~30 words)
Generates embeddings using Sentence Transformers
Uses Cosine Similarity to retrieve relevant chunks
Retrieves the Top 2 most relevant chunks
Generates answers using a HuggingFace language model
Simple and easy-to-understand implementation
