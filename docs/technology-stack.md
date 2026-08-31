# Technology Stack

## 1. Programming Language

Python

Python is used for the backend and AI processing because of its strong ecosystem for AI and machine learning.

## 2. LLM Framework

LangChain

LangChain will be used to orchestrate LLM workflows, prompts, retrieval, and RAG components.

## 3. LLM Provider

OpenAI API

The OpenAI API will initially be used as the LLM provider.

The architecture will keep the LLM layer modular so that another provider can be integrated later.

## 4. Embeddings

OpenAI Embeddings

Embeddings will convert transcript chunks and user questions into numerical vector representations.

## 5. Vector Database

ChromaDB

ChromaDB will be used for storing embeddings and performing similarity search during the RAG stage.

## 6. Backend

FastAPI

FastAPI will expose REST API endpoints for the frontend and connect the frontend with the AI processing pipeline.

## 7. Frontend

React

React will provide the user interface for entering YouTube URLs, viewing summaries, and asking questions.

## 8. Testing

Pytest

Pytest will be used for backend and AI pipeline testing.

## 9. Version Control

Git and GitHub

Git and GitHub will be used for source control, documentation, and project history.

## 10. Containerization

Docker

Docker will be introduced after the application is functional to provide a reproducible runtime environment.
