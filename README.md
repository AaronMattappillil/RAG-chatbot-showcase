# RAG Chatbot using n8n, Pinecone and Google Gemini

## Overview

This project demonstrates the design and implementation of Retrieval-Augmented Generation (RAG) chatbots using n8n workflow automation, Pinecone Vector Database, and Google Gemini Embeddings.

This repository documents two domain-specific Retrieval-Augmented Generation (RAG) chatbots. While both systems share the same architecture, they operate on different knowledge bases:

- IPSR Course Assistant
- Union Budget Assistant

The project demonstrates how a single RAG pipeline can be adapted to multiple domains by changing the underlying document corpus and retrieval context.
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

## Technology Stack

* n8n
* Pinecone
* Google Gemini
* Vector Search
* RAG Architecture
* Google Drive Integration

## Chatbot Implementations

This repository contains documentation for two Retrieval-Augmented Generation (RAG) chatbot implementations built on the same underlying architecture.

### IPSR Course Assistant
- Domain: Educational and training programs
- Knowledge Source: IPSR course information and training details
- Purpose: Answer user queries regarding courses, certifications, fees, schedules, and training programs.

### Union Budget Assistant
- Domain: Government financial documents
- Knowledge Source: Union Budget reports and related documents
- Purpose: Provide context-aware answers and insights from budget documents through semantic retrieval.

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

See: docs/

## Documentation

* System Overview
* Workflows
* Screenshots
* System Prompts

## Future Improvements

* Hybrid Search
* Metadata Filtering
* Multi-document Retrieval
* Reranking Models
* User Authentication
* Production Deployment
