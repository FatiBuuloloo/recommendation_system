# Smart_Car_Recommender_SBERT
## 📌 Overview
This project implements a Hybrid Search Pipeline that combines:
1. Rule-Based Entity Extraction: Leverages Regex and Context-Window Parsing to identify specific constraints for **Year**, **Price**, and **Engine Size**.
2. Semantic Re-ranking: Utilizes the **all-mpnet-base-v2** model to rank results based on user preferences.
## 🚀 Key Features
- Smart Intent Parsing: Capable of distinguishing "below", "above", and "around" logic from unstructured free-text input.
- Semantic Awareness: Understands automotive synonyms and specialized contexts using advanced Transformer models.
- Two-Stage Retrieval: Using pre-filtering the dataset before performing Cosine Similarity calculations.
## 🛠️ Tech Stack
Language: Python
Data Manipulation: Pandas, NumPy
Machine Learning: PyTorch, Sentence-Transformers (SBERT)
NLP Techniques: Regular Expressions (Regex), Entity Extraction, Vector Embeddings
