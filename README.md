 Extractive Question Answering and Re-ranking System

 Overview

This project implements an NLP pipeline for:

- Extractive Question Answering (QA)
- Passage Retrieval
- Re-ranking of retrieved passages
- Evaluation using Exact Match (EM) and F1 Score

The system retrieves relevant contexts for a user query, re-ranks the candidate passages, and extracts the most accurate answer using transformer-based models.



 Features

- Extractive QA using Transformer models
- Passage retrieval and ranking
- Re-ranking mechanism for improving answer relevance
- Evaluation metrics:
  - Exact Match (EM)
  - F1 Score
- Dataset preprocessing and tokenization
- Hugging Face Transformers integration


 Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- PyTorch
- NumPy
- Pandas
- Scikit-learn



 Dataset

This project uses the SQuAD v1.1 dataset.

Files used:
- `train-v1.1.json`
- `dev-v1.1.json`



Project Structure

```text
Modern-Information-Retrieval/
│
├── notebooks/
│   └── squad_qa.ipynb
│
├── data/
│   ├── train-v1.1.json
│   └── dev-v1.1.json
│
├── README.md
├── requirements.txt
└── results/
