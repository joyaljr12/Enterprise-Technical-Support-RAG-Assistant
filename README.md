# Enterprise-Technical-Support-RAG-Assistant
Enterprise Technical Support RAG Assistant using Python, FastAPI, PostgreSQL, pgvector, local LLMs, Docker and AWS.


## Problem

IT support teams and developers often need to search through large collections of technical documentation to find information related to specific issues. Manually locating and reading relevant documents can be time-consuming, especially when information is distributed across multiple pages.

## Project Goal

The goal of this project is to develop a Retrieval-Augmented Generation (RAG) assistant that helps users find relevant technical information more efficiently.

The system will retrieve relevant passages from technical documentation based on a user's question and use a Large Language Model (LLM) to generate a grounded answer with citations to the original sources.

## Data source

This project will initially use publicly available official Docker documentation.

Docker documentation provides realistic technical information about containers, images, networking, storage and troubleshooting. It allows us to develop and evaluate the RAG system without using confidential enterprise data.