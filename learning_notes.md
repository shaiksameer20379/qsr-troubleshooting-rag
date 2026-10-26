# Learning Notes

## Day 1 — Project Foundation

### What I am building
A QSR Troubleshooting Assistant that uses AI to retrieve
relevant troubleshooting documentation and similar
resolved cases.

### Concepts introduced
- RAG (Retrieval-Augmented Generation)
- Embeddings
- Semantic search
- Vector databases
- Qdrant

### Initial architecture
User query → Embedding → Qdrant retrieval
→ Evidence-based response

### Key understanding
Qdrant retrieves relevant information, while the
application uses that evidence to produce a response.

### Next step
Set up the local Python project environment.
