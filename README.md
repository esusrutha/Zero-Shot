# Zero-Shot Document Classification using BERT, RoBERTa, and S-BERT

## Overview

This project implements Zero-Shot Document Classification using pretrained transformer models from the Hugging Face ecosystem. The solution was developed and executed in Google Colab and evaluates the performance of BERT, RoBERTa, and Sentence-BERT (S-BERT) on the BBC News dataset.

## Models Used

* BERT (bert-base-uncased)
* RoBERTa (roberta-base)
* Sentence-BERT (all-MiniLM-L6-v2)

## Technologies

* Python
* Google Colab
* Hugging Face Transformers
* Sentence Transformers
* PyTorch
* Scikit-learn
* Pandas
* NumPy

## Dataset

BBC News Dataset

Categories:

* Business
* Entertainment
* Politics
* Sport
* Technology

## Methodology

* Generated document embeddings using pretrained transformer models.
* Created category embeddings by averaging document embeddings.
* Applied cosine similarity for zero-shot document classification.
* Evaluated model performance using Accuracy, Precision, Recall, and F1-Score.

## Research Publication

Published in DAPCOM 2024:

"Zero-Shot Document Classification Using Pretrained Models"

## How to Run

1. Open the notebook in Google Colab.
2. Install required libraries.
3. Upload or mount the BBC News dataset.
4. Execute the notebook cells.
5. View classification results and performance metrics.

## Author

Susrutha Ettimalla
