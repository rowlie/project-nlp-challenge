# NLP Challenge

Classifies news articles as fake or real using machine learning (Random Forest & Naive Bayes) on a labeled dataset of ~40,000 examples. All workflow steps, from preprocessing with NLTK, TF-IDF feature engineering, training, evaluation, and output submission, are demonstrated in a single Jupyter notebook.

## Quick Start

1. Clone/download this repo and place `data.csv` and `validation_data.csv` in the folder.
2. Open `roland-NLP-Challenge.ipynb` in Jupyter.
3. Run cells sequentially:
    - Install/import: pandas, numpy, scikit-learn, nltk, matplotlib, seaborn
    - Load and clean data (`title` and `text`)
    - Apply TF-IDF vectorization
    - Train Random Forest and Naive Bayes classifiers
    - Evaluate with accuracy and F1 metrics
    - Save predictions to `validation_predictions.csv`

## Results

- Random Forest: ~92% accuracy
- Naive Bayes: ~94% accuracy

## Requirements

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, nltk, matplotlib, seaborn

