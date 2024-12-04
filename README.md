# Hugging Face-based Retrieval Augmented Generation (RAG) Workflow

This repository demonstrates a Retrieval Augmented Generation (RAG) workflow using Hugging Face's transformers and related tools. The notebook explores document loading, splitting, storage, retrieval, and Q&A generation using a `RetrievalQA` chain.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Acknowledgments](#acknowledgments)

## Overview

The workflow includes the following steps:
1. **Document Loading and Splitting**: Load and preprocess documents.
2. **Storage and Retrieval**: Store embeddings for efficient retrieval.
3. **Q&A Generation**: Use a `RetrievalQA` chain for generating answers.

![Workflow Overview](attachment:overview.jpeg)

## Installation

To use this repository, clone it and install the required dependencies:

```bash
git clone https://github.com/yourusername/hugging-face-rag.git
cd hugging-face-rag
pip install -r requirements.txt
```
##Usage

Add your Hugging Face API key to a .env file:
```bash
HUGGINGFACE_API_KEY=<your-api-key>
```
Run the notebook to explore the RAG workflow.
