# 🌿 GreenPubMed Assistant

M2 Data Engineering Hackathon — Biomedical article processing and summarization system with environmental impact measurement.

## 🎯 Objective

Build a data + AI pipeline that:

* Loads and cleans PubMed articles
* Stores them using a Bronze/Silver/Gold architecture
* Generates summaries with AI
* Answers questions using RAG (Retrieval-Augmented Generation)
* Measures environmental impact (CO₂, energy)

## 📁 Project structure
GreenPubMed_Hackathon/
data/
bronze/   # Données brutes
silver/   # Données nettoyées (Parquet)
gold/     # Chunks, embeddings, résumés
src/        # Scripts Python
notebooks/  # Notebooks Colab
reports/    # Benchmarks CSV
app/        # Dashboard Streamlit


## ⚙️ Installation
```bash
pip install datasets pandas pyarrow polars codecarbon tiktoken
pip install sentence-transformers faiss-cpu scikit-learn streamlit matplotlib
```

## 🚀 Utilisation
Ouvrir `AI_PubMed.ipynb` dans Google Colab et exécuter les cellules dans l'ordre.

## 👩‍💻 Auteure
Nada Lahbib ENCIBI — M2 Data Engineering
Celina
Rahma
