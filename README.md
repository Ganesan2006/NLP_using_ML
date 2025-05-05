# 🛒 NLP Product Identifier

This project is an NLP-based machine learning pipeline to identify or classify product categories from textual product descriptions.

## 📌 Features

- Text preprocessing (stemming, vectorization)
- TF-IDF vectorization of product descriptions
- Random Forest classifier for predicting product categories
- Accuracy evaluation on test data

## 🧠 Technologies Used

- Python
- scikit-learn
- pandas
- NLTK

## 🗂️ Dataset

The model is trained on a dataset named `train_40k.csv`, which includes product descriptions and their corresponding category labels.

| Column      | Description                        |
|-------------|------------------------------------|
| Text        | Product description (input text)   |
| Category    | Product category (target variable) |

> Note: Make sure the CSV file is placed in the same directory as the notebook.

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn nltk
