# Advanced Question Answering System

## Project Overview

This project involves the development of an advanced Question Answering (QA) system utilizing state-of-the-art Natural Language Processing (NLP) technologies. The system is designed to provide accurate and relevant answers to user queries by leveraging a Transformer-based Large Language Model (LLM) and a Retrieval-Augmented Generation (RAG) pipeline.

## Key Features

- **Transformer-based LLM (BERT)**: The core of the QA system is built around BERT (Bidirectional Encoder Representations from Transformers), which enables the model to understand and generate contextually relevant answers.
- **Web Scraped News Articles**: The QA system is trained on a large dataset of 37,000 news articles, ensuring a diverse and comprehensive knowledge base.
- **Data Cleaning with spaCy**: The raw text data from the news articles is pre-processed and cleaned using spaCy, an advanced NLP library, to enhance the quality and reliability of the information.
- **RAG Pipeline**: The integration of a Retrieval-Augmented Generation pipeline using Langchain improves information retrieval and answer generation, ensuring detailed and accurate responses to user queries.

## Technical Stack

- **Large Language Model**: BERT
- **Data Pre-processing**: spaCy
- **Information Retrieval and Answer Generation**: RAG pipeline with Langchain

## Functionality

1. **Automated Question Answering**: Users can input queries, and the system will provide precise answers based on the processed dataset.
2. **Enhanced Information Retrieval**: The RAG pipeline allows the system to retrieve relevant information efficiently from the extensive dataset of news articles.
3. **Comprehensive Responses**: By combining retrieval and generation techniques, the system ensures that the answers are not only relevant but also comprehensive and contextually appropriate.

## Usage

To use the QA system, simply input your query, and the system will process the input, retrieve the most relevant information from the dataset, and generate an accurate response. This makes it an invaluable tool for anyone seeking quick and reliable answers from a vast pool of news articles.
