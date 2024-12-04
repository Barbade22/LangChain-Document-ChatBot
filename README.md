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
## Usage
Add your Hugging Face API key to a .env file:
```bash
HUGGINGFACE_API_KEY=<your-api-key>
```
Run the notebook to explore the RAG workflow.

## Dependencies
The notebook requires the following libraries:

Hugging Face Transformers
Panel for GUI components
Python-dotenv for managing environment variables
Install all dependencies using pip:
```bash
pip install -r requirements.txt
```
## Acknowledgments
This project utilizes the open-source Hugging Face models and Panel for interactive GUI development. Special thanks to the Hugging Face community for their robust tools and support.


