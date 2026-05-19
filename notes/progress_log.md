# Progress Log

## Day 1 — Basic RAG pipeline

Implemented:
- Word-based chunking with overlap
- SentenceTransformer embeddings
- In-memory vector DB
- Top-k retrieval using cosine similarity
- OpenAI response generation using retrieved context

Key lesson:
- Retrieval quality controls answer quality. Increasing k from 2 to 4 allowed the model to retrieve the chunk containing the final weighted mean estimator.
- Normalizing vectors before calculating the cosine similarity reduces the computation down to only the dot product.

