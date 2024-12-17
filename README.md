 Medicine Recommendation System Using Machine Learning

A content-based medicine recommendation system using NLP and cosine similarity.

## Features
- Recommends similar medicines based on descriptions and usage reasons.
- Flask-based web application for user interaction.
- Text preprocessing with tokenization, stemming, and stop-word removal.

## Requirements
- Python (>=3.7), Flask, pandas, scikit-learn, nltk, numpy

## Usage
1. Enter a medicine name in the input field.
2. Get a list of 5 similar medicines.
   
## How It Works
- **Dataset**: `medicine.csv` contains medicine names, descriptions, and reasons.
- **Preprocessing**: Text is cleaned, tokenized, and combined into tags.
- **Similarity**: Cosine similarity is used to recommend medicines.
- 
## File Structure
```
├── app.py                 # Flask application
├── medicine.csv           # Dataset
├── similarity.pkl         # Similarity matrix
├── medicine_dict.pkl      # Pickled medicine data
├── templates/index.html   # HTML UI
└── requirements.txt       # Dependencies
