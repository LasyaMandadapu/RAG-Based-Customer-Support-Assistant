# RAG-Based-Customer-Support-Assistant

## Overview
This project implements a Retrieval-Augmented Generation (RAG) system using LangGraph and ChromaDB to provide intelligent customer support.

## Features
- PDF Knowledge Base Processing
- Semantic Search with Embeddings
- Context-Aware Answer Generation
- Graph-Based Workflow (LangGraph)
- Conditional Routing
- Human-in-the-Loop Escalation

## Tech Stack
- Python
- LangChain
- LangGraph
- ChromaDB
- OpenAI / LLM

## Workflow
1. Load PDF
2. Chunk & Embed
3. Store in Vector DB
4. Retrieve relevant context
5. Generate response
6. Route based on confidence
7. Escalate if needed

## Project Structure
--> main.py
--> requirements.txt
--> sample.pdf
--> Technical-docx
--> HLD and LLD detailed Docx

## How to Run
```bash
pip install -r requirements.txt
python main.py

##Future Improvements
Multi-document support
Chat memory
Deployment
