# Intelligent Document Processing using LangChain RAG Pipeline

A sophisticated document retrieval and question-answering system built with LangChain framework that enables intelligent processing of PDF documents using RAG (Retrieval Augmented Generation) architecture.

## Key Features

- Implements an end-to-end RAG pipeline using LangChain and local LLM (Llama3)
- Intelligent router system for document vs web search with multi-stage verification
- Document relevance grading with custom scoring mechanism
- Hallucination detection for high-quality responses
- PDF document processing with chunking and semantic search
- Vector store integration using SKLearn for efficient retrieval
- Local embeddings using Nomic Embed

## Technical Stack

- **Framework**: LangChain
- **Language Model**: Llama3 (local deployment)
- **Vector Store**: SKLearn Vector Store
- **Embeddings**: Nomic Embeddings
- **Document Processing**: PyPDF Loader, Recursive Character Text Splitter
- **Quality Control**: Custom grading system for relevance and hallucination detection

## Architecture

1. **Document Processing**
   - PDF ingestion and chunking
   - Text splitting with overlap for context preservation
   - Vector embeddings generation

2. **Intelligent Routing**
   - Smart routing between document search and web search
   - Multi-stage verification process
   - Custom relevance scoring

3. **Response Generation**
   - Context-aware answer generation
   - Hallucination detection
   - Quality grading system

## Implementation Details

- Custom router instructions for intelligent source selection
- Document grader for relevance assessment
- Hallucination detection for response validation
- Graph-based state management for pipeline control
- Modular design for easy extension and modification

This project demonstrates advanced RAG implementation with focus on response quality and accuracy through multi-stage verification and grading systems.


