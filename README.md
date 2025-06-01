# Federal Registry RAG Agent

A User-Facing Chat-Style RAG Agent with daily-updating data pipeline from Federal Registry API.

## Features

- Daily data updates from Federal Registry API
- MySQL database with full-text search
- Local Ollama LLM (llama3.2) 
- Conversational chat 
- Context-aware responses

## Installation

1. **Prerequisites**:
   - Python 3.9+
   - MySQL Server
   - Ollama installed with llama3.2 model

2. **Setup**:
   ```bash
   git clone https://github.com/jaikumar2406/Federal-Registry-RAG-Agent.git
   cd federal-registry-rag-agent
   pip install -r requirements.txt
