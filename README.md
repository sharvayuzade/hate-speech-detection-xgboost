# hate-speech-detection-xgboost
A text-based hate speech classification project using XGBoost, NLP, and sklearn.

# Hate Speech Detection Using XGBoost

This project is part of a Project-Based Learning (PBL) showcase at Symbiosis Institute of Technology, Nagpur. It focuses on detecting hate speech in textual data using machine learning and natural language processing techniques.

## Project Overview

The model classifies text into three categories:
- Hate Speech
- Offensive Language
- Neither

This classification is achieved using TF-IDF vectorization and the XGBoost algorithm. The dataset used includes labeled Twitter data with annotations indicating the type of speech.

## Features

- Preprocessing of raw text data including cleaning and tokenization.
- Feature extraction using TF-IDF.
- Training and evaluation using the XGBoost classifier.
- Performance metrics including accuracy, precision, recall, and F1-score.

## Dataset

- Source: Publicly available hate speech Twitter dataset.
- Format: CSV file with columns such as `tweet`, `class`, and `label`.

## Requirements

- Python 3.8+
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Jupyter Notebook

Install dependencies with:

```bash
pip install -r requirements.txt
