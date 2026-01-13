# AI Automation Lab

A local AI workflow environment built with n8n, Ollama, and open-source tools for experimenting with AI automation and orchestration.

## Overview

This project is a personal development workspace for exploring AI workflow automation, local LLM integration, and visual workflow building. It's designed for hands-on learning and experimentation with different AI models and orchestration patterns.

## Features

- Visual workflow builder using n8n editor
- Local LLM integration with Ollama models
- PostgreSQL database with Qdrant vector search
- Docker-based development environment
- Modular workflow components and templates
- Real-time workflow execution and debugging

## Tech Stack

- **n8n**: Node.js workflow automation platform
- **Ollama**: Local LLM integration for private AI processing
- **Qdrant**: Vector database for semantic search
- **PostgreSQL**: Primary data storage
- **Docker Compose**: Containerized development setup
- **LangChain**: Workflow orchestration components

## Local Setup

1. Clone the repository and navigate to the project directory
2. Install dependencies with `npm install`
3. Start PostgreSQL and Qdrant services
4. Launch n8n with `npm run dev`
5. Import the demo workflow from `demo-data/workflows/`
6. Start experimenting with local AI workflows

## Use Cases

### PDF Processing Pipeline
Create automated workflows for:
- Document extraction and summarization
- Multi-step analysis with local LLMs
- Content classification and organization

### Local AI Assistant
Build conversational agents that:
- Process documents using Ollama models
- Maintain conversation context
- Generate responses without external APIs

### Automation Workflows
Design visual workflows for:
- Batch content processing
- Scheduled task execution
- Integration with external tools and APIs

## Notes

This is a personal learning project for exploring AI automation concepts. The workflows and components are experimental and intended for local development and education purposes. The environment supports rapid prototyping and testing of AI-powered automation patterns.

## Limitations

- Designed for local development and experimentation
- Workflows may require manual configuration for specific use cases
- Performance depends on local hardware capabilities
- Not intended for production deployment without modification
