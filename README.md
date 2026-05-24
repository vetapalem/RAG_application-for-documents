# RAG_application-for-documents
# Complete RAG System with Hugging Face

A production-ready Retrieval-Augmented Generation (RAG) system that answers questions from your documents using free, open-source models from Hugging Face. No API keys required – runs entirely locally.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Code Structure](#code-structure)
- [Components](#components)
- [Configuration](#configuration)
- [Usage Examples](#usage-examples)
- [Performance](#performance)
- [Troubleshooting](#troubleshooting)
- [Customization](#customization)
- [Limitations](#limitations)
- [Roadmap](#roadmap)
- [License](#license)

## Overview

This RAG system enables you to:
- 📄 Load documents (PDF, TXT files)
- ✂️ Split text into semantic chunks
- 🔢 Create embeddings using Sentence Transformers
- 🔍 Search for relevant content using FAISS
- 💬 Generate answers using Hugging Face LLMs
- 📖 Cite sources for transparency

**No cloud dependencies, no API costs, fully private.**

## Features

| Feature | Status | Description |
|---------|--------|-------------|
| PDF Support | ✅ | Extract text from PDF files |
| TXT Support | ✅ | Load plain text files |
| Smart Chunking | ✅ | Overlapping chunks preserve context |
| Embeddings | ✅ | 384-dim vectors with all-MiniLM-L6-v2 |
| Vector Search | ✅ | FAISS similarity search |
| LLM Generation | ✅ | Zephyr-7B (free, local) |
| Source Citation | ✅ | Shows retrieved chunks |
| Interactive Mode | ✅ | Command-line Q&A |
| Batch Processing | ⏳ | Planned |
| Multiple Documents | ⏳ | Planned |
| Word Support | ⏳ | Planned |
| GPU Acceleration | ✅ | Optional CUDA support |

## Architecture
