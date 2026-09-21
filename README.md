# Technical Documentation Assistant using RAG

An AI-powered technical documentation assistant built using Retrieval-Augmented Generation (RAG).

The system will allow users to ask questions about technical documentation and receive grounded answers based on the provided documents, along with relevant source citations.

## Project Status

🚧 Under Development

## Planned Features

- Technical document ingestion
- Document parsing and text extraction
- Text cleaning and chunking
- Embedding generation
- Vector database
- Semantic search
- Retrieval-Augmented Generation
- Source citations
- FastAPI backend
- Streamlit interface
- RAG evaluation
- Logging and error handling
- Automated tests
- Docker support

## Architecture

```text
Technical Documents
        ↓
Document Ingestion
        ↓
Text Cleaning
        ↓
Chunking
        ↓
Embeddings
        ↓
Vector Database
        ↓
Retriever
        ↓
Relevant Context
        ↓
LLM
        ↓
Grounded Answer
        ↓
Source Citations