 A simple RAG (Retrieval-Augmented Generation) pipeline:

It loads a PDF, cleans and chunks the text, then stores embeddings in a FAISS vector index.
It saves/loads the index locally so you can reuse it without re-embedding.
It sets up a Groq-hosted LLM and a retrieval chain so queries are answered using only the retrieved document context.
It includes sample queries, streaming output, and batch Q&A to demonstrate the pipeline.
