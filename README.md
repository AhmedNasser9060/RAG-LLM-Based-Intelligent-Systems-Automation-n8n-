# RAG & LLM-Based Intelligent System

This project demonstrates a **Retrieval-Augmented Generation (RAG)** system for building knowledge-grounded AI applications.  
It integrates **large language models (LLMs)** with **semantic search** over structured and unstructured data using **Supabase** as the vector database and **n8n** for workflow automation.

---

## Features

- **Document Ingestion:** Process PDFs, web pages, and text data into manageable chunks.  
- **Embeddings Generation:** Transform text chunks into vector embeddings using OpenAI or Gemini.  
- **Semantic Search:** Store embeddings in **Supabase** and retrieve relevant chunks based on similarity search.  
- **Grounded LLM Responses:** Feed retrieved context to LLMs for accurate and hallucination-reduced answers.  
- **Workflow Automation:** Integrate the RAG pipeline into automated workflows using **n8n**, enabling AI-driven tasks and processes.  

---

## Tech Stack

- **LLMs:** OpenAI, Gemini  
- **Vector Database:** Supabase (pgvector)  
- **Automation:** n8n  
- **Data Processing:** Python, Pandas, NumPy  
- **Text Processing:** Hugging Face Transformers, NLTK, SpaCy  

---

## How It Works

1. **Ingest Data:** Import documents and web content.  
2. **Chunk & Embed:** Split text into chunks and generate embeddings.  
3. **Store in Supabase:** Save embeddings for efficient retrieval.  
4. **Retrieve Context:** Perform semantic search to get relevant chunks.  
5. **Generate Answer:** Pass retrieved chunks to an LLM to produce grounded responses.  
6. **Automate Workflow:** Trigger actions or queries in **n8n** based on AI outputs.

---

## Use Cases

- AI-powered Q&A over internal documents  
- Knowledge assistant for company data  
- Automated chatbot workflows for customer support or operations  

---

## Getting Started

1. Set up a **Supabase account** and create a project with **pgvector** enabled.  
2. Prepare your documents and text data for ingestion.  
3. Configure your **OpenAI / Gemini API keys**.  
4. Integrate the pipeline into **n8n workflows** to automate AI tasks.  

---

## Contribution

Feel free to contribute by adding more LLMs, new data connectors, or improving automation workflows.  

---

## License

MIT License
