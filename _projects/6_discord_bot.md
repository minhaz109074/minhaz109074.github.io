---
layout: page
title: AI Search & QA Discord Bot
description: Discord bot for image similarity search, text summarization, and question answering powered by Ollama and pgvector.
# img: assets/img/11.jpg
importance: 6
category: Research & ML
---

**Technologies:** Python, Ollama, pgvector, PostgreSQL, Discord API

[GitHub](https://github.com/minhaz109074/discord-bot-for-similarity-search){: .btn .btn-sm .btn--primary target="_blank"}

---

### Overview

Built a feature-rich Discord bot that integrates **local LLMs via Ollama** and **vector-based semantic search via pgvector** to enable intelligent search, summarization, and question answering directly inside a Discord server.

### Key Features

- **Image Similarity Search:** Users can upload an image and retrieve visually similar images from a stored database using semantic vector embeddings.

- **Text Summarization:** Automatically summarizes long documents or messages using locally running LLMs (via Ollama), keeping all data private.

- **Question Answering (RAG):** Implements a Retrieval-Augmented Generation (RAG) pipeline — converts user queries to embeddings, retrieves relevant chunks from `pgvector`, and generates grounded answers using the LLM.

### Architecture

The bot connects the Discord API → Python backend → Ollama (local LLM inference) → PostgreSQL with pgvector (semantic storage and retrieval), enabling a fully private, self-hosted AI assistant experience.
