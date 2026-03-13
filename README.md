# 🧠 NeuralSearch-Engine

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![AI](https://img.shields.io/badge/AI-NLP-green.svg)](https://github.com/TanNgo1/NeuralSearch-Engine)

A high-performance semantic search engine that understands the context of your queries. Built with **Sentence-Transformers** for embeddings and **FAISS** for lightning-fast similarity search.

## ✨ Features
- **Semantic Understanding:** Goes beyond keyword matching.
- **High Performance:** Optimized for million-scale datasets.
- **Modular Design:** Easily plug in any HuggingFace model.

## 🛠️ Tech Stack
- **Models:** `all-MiniLM-L6-v2` (via Sentence-Transformers)
- **Vector DB:** Meta's FAISS
- **Backend:** Python

## 🚀 Quick Start
```bash
pip install -r requirements.txt
python engine.py
```
