## Related Project

After pre-training and post-training an LLM, one common way to adapt it to domain-specific knowledge is through **Retrieval-Augmented Generation (RAG)**. Instead of relying solely on the model's internal parameters, RAG retrieves relevant information from external knowledge sources at inference time, enabling more accurate, up-to-date, and grounded responses without retraining the model.

This repository demonstrates how to build a production-ready RAG pipeline for Bengali, including document ingestion, embedding generation, vector database indexing, semantic retrieval, and LLM-based answer generation.

👉 **[Bengali RAG QA Bot](https://github.com/LimonHalder/bengali-rag-qa-bot)** — A complete Bengali Retrieval-Augmented Generation (RAG) system built with LangChain, ChromaDB, and Google Gemini for knowledge-grounded question answering.
