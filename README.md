# Sentiment Analysis with Yelp Review Dataset

This repository contains **my completed homework** for the *Computational Data Science* course. The goal is to classify Yelp reviews into star ratings (1 to 5) using a series of **NLP** and **deep learning** techniques.  

---

## Overview

1. **Data Loading**  
   - Imported data from the [Yelp Review Full](https://huggingface.co/datasets/Yelp/yelp_review_full) dataset.  
   - Mapped labels (0–4) to star ratings (1–5).

2. **EDA & Preprocessing**  
   - Cleaned and tokenized text (removing URLs, stopwords, punctuation, etc.).  
   - Leveraged TF-IDF and other vectorizers for feature extraction.

3. **Modeling**  
   - Trained multiple **neural network architectures** (including optional Transformer layers).  
   - Tuned hyperparameters (learning rate, dropout, etc.) to improve performance.

4. **Evaluation**  
   - Validated models using accuracy, precision, recall, F1-score, and confusion matrices.  
   - Demonstrated predictions on custom sample sentences.

---

## How to Use

1. **Clone or Download** the repo:  
   ```bash
   git clone https://github.com/YourUsername/YelpNLPHomework.git
   cd YelpNLPHomework
   ```
2. **Install Requirements** (Python 3.7+):
   ```bash
   pip install -r requirements.txt
   ```
3. **Open the Notebook**:
   ```bash
   jupyter notebook yelp_sentiment.ipynb
   ```
4. **Run & Explore** the cells in order, from data loading/EDA to modeling and evaluation.

---

## Notes

- This work is part of the **Computational Data Science** course homework.  

**Thank you!** 

