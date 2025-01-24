# AI Models Exploration and Preparation

This repository showcases our initial explorations with AI models (RAG, LangChain) and tools as part of our preparation for future projects. This repository contains implementations, experiments, and learnings from trying out various LLMs, RAG , and embedding models.

---

## Repository Overview

This repository includes:

1. **LLM Models Explored**
   - `google/flan-t5-base`
   - `google/gemma-7b`
   - `meta-llama/Llama-2-7b`
   - `Microsoft/Phi-3.5-mini-instruct`
   - `Mistral-7B-Instruct-v0.3`

2. **Embedding Models Explored**
   - `sentence-transformers/all-MiniLM-L6-v2`
   - `BAAI/bge-base-en-v1.5`
   - `sentence-transformers/all-mpnet-base-v2`
   - `OpenAIEmbeddings`

3. **Technologies and Tools**
   - RAG Pipelines (Retrieval-Augmented Generation)
   - LangChain
   - FAISS for Vector Similarity Search
   - Hugging Face Models

---

## Objectives

- **Gain Hands-On Experience**: The goal is to get a foundational understanding of how various tools and models function.
- **Compare Models**: Test performance of different LLMs and embedding models.
- **Prepare for Future Projects**: Build the groundwork for scaling these approaches to complex, real-world tasks.

---

## Structure

- **`/code`**: Contains Python scripts for:
  - Implementing RAG pipelines
  - Embedding generation and storage
  - Querying and generating responses using LLMs
- **`/notebooks`**: Jupyter Notebooks demonstrating step-by-step explorations.
- **`/resources`**: Links to documentation, research papers, and tutorials used during this phase.

---

## Key Learnings

1. **Challenges Faced**:
   - Model size constraints on free-tier GPU environments.
   - Token permission adjustments for API access.
   - Efficiently managing GPU and CPU resources for embeddings and LLMs.

2. **Solutions Implemented**:
   - Using smaller model variants where required.
   - Explicitly setting `device='cpu'` for embeddings when GPU was allocated to the LLM.

3. **Takeaways**:
   - Exposure to tools like LangChain and FAISS.
   - Practical experience in embedding generation and querying pipelines.

---

## Next Steps

- Refine and scale the approaches for real-world use cases.
- Integrate structured databases like MongoDB or PostgreSQL for managing data..
