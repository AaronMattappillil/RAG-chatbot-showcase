# RAG Chatbot using n8n, Pinecone and Google Gemini

## Overview

This project demonstrates the design and implementation of Retrieval-Augmented Generation (RAG) chatbots using n8n workflow automation, Pinecone Vector Database, and Google Gemini Embeddings.

The system enables users to query domain-specific knowledge bases while ensuring responses are grounded in retrieved documents.

## Features

* Retrieval-Augmented Generation (RAG)
* n8n workflow orchestration
* Pinecone vector database integration
* Google Gemini embeddings
* Semantic document retrieval
* Custom system prompts
* Knowledge base ingestion pipeline
* Context-aware conversational responses

## System Architecture
```text
User Query
↓
n8n AI Agent
↓
Pinecone Vector Store
↓
Semantic Retrieval
↓
Google Gemini
↓
Response Generation
```
## Technology Stack

* n8n
* Pinecone
* Google Gemini
* Vector Search
* RAG Architecture
* Google Drive Integration

## Projects Included

### IPSR Course Assistant

A chatbot that answers questions about IPSR training programs using a vectorized course knowledge base.

### Union Budget Assistant

A chatbot that answers questions regarding Union Budget documents using retrieval-augmented generation.

## Knowledge Base Pipeline
```text
Google Drive
↓
Document Ingestion
↓
Recursive Text Splitting
↓
Google Gemini Embeddings
↓
Pinecone Indexing
↓
Semantic Retrieval
```
## Screenshots

See: docs/screenshots/

## Documentation

* Architecture diagrams
* Workflow screenshots
* Knowledge base indexing examples
* Prompt engineering examples

## Future Improvements

* Hybrid Search
* Metadata Filtering
* Multi-document Retrieval
* Reranking Models
* User Authentication
* Production Deployment
