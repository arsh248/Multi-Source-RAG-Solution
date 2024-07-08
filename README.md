# Multi Source RAG Solution

## Overview

Welcome to the LangChain project repository! This project showcases the integration of various tools and APIs from the LangChain framework for advanced natural language processing tasks. It focuses on retrieval-augmented generation (RAG), document querying, and content retrieval using multiple data sources.

## Features

- **Wikipedia Query Tool**: Utilizes LangChain's Wikipedia API wrapper to fetch information from Wikipedia.
- **Document Retrieval**: Loads documents from a specified web source and sets up FAISS for efficient document retrieval.
- **Arxiv Query Tool**: Queries Arxiv for academic papers using LangChain's Arxiv API wrapper.
- **OpenAI Integration**: Integrates with OpenAI's GPT-3.5-turbo model for advanced text generation and query responses.
- **Agent Execution**: Demonstrates how to create and execute agents that leverage the integrated tools for various NLP tasks.

## Setup

### Prerequisites

- Python 3.x
- `pip` package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/arsh248/Multi-Source-RAG-Solution
   cd Multi-Source-RAG-Solution

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Set up environment variables:
    Create a .env file in the root directory with your OpenAI API key:

   ```bash
   OPENAI_API_KEY=<your_openai_api_key>


