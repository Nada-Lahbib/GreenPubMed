# GreenPubMed Assistant

M2 Data Engineering Hackathon — Biomedical article processing and summarization system with environmental impact measurement.

## Objective

Build a data + AI pipeline that:

* Loads and cleans PubMed articles
* Stores them using a Bronze/Silver/Gold architecture
* Generates summaries with AI
* Answers questions using RAG (Retrieval-Augmented Generation)
* Measures environmental impact (CO₂, energy)

## Project structure
GreenPubMed_Hackathon/
data/
bronze/   # Raw Data
silver/   # Parquet
gold/     # Chunks, embeddings, abstracts
src/        # Scripts Python
notebooks/  # Notebooks Colab
reports/    # Benchmarks CSV
app/        # Dashboard Streamlit


## Installation
```bash
pip install datasets pandas pyarrow polars codecarbon tiktoken
pip install sentence-transformers faiss-cpu scikit-learn streamlit matplotlib
```

## Utilisation

Open `AI_PubMed.ipynb` in Google Colab and run the cells in order

