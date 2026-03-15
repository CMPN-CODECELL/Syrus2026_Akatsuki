## Team Name
Team Akatsuki

## Problem Statement
PS-03: Autonomous Developer Onboarding Agent

## Hackathon
Syrus 2026 Hackathon


## Project Overview
The Autonomous Developer Onboarding Agent is an AI-powered assistant designed to automate the onboarding process for new developers. The system uses Retrieval-Augmented Generation (RAG) and Agentic AI to guide developers through company documentation, setup processes, and internal workflows.

It personalizes the onboarding journey based on developer role, experience level, and technology stack while tracking progress and automatically notifying HR upon completion.

## Key Features
- AI-powered chat-based onboarding assistant
- Personalized onboarding based on role, experience, and tech stack
- Retrieval-Augmented Generation (RAG) knowledge retrieval
- Vector database for semantic search of documentation
- Automated onboarding checklist tracking
- Automatic HR completion notification

## System Architecture
The system processes company documentation into embeddings, stores them in a vector database, and allows AI agents to retrieve relevant knowledge using RAG. Agentic AI coordinates developer profiling, onboarding planning, and guidance through a FastAPI backend and web interface.

## Tech Stack
- Python
- FastAPI
- LangChain
- Vector Database
- Large Language Models (LLMs)
- Web Interface

## How It Works
1. Collect company documentation and onboarding guides  
2. Process and convert documents into embeddings  
3. Store embeddings in a vector database  
4. AI agents retrieve relevant knowledge using RAG  
5. Developers interact with the onboarding assistant via chat interface  
6. The system tracks onboarding progress and notifies HR upon completion

## Repository
This repository contains the implementation of the Autonomous Developer Onboarding Agent developed for Syrus 2026 Hackathon (PS-03).
