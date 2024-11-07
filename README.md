# Fine-Tuning BERT for Rating Prediction from Textual Online Reviews

This repository contains the code and resources for my thesis project: **Fine-Tuning BERT for Rating Prediction from Textual Online Reviews**. The project focuses on predicting movie review ratings using natural language processing (NLP) techniques, leveraging BERT-based models.

## Repository Structure

- **`preprocessing.ipynb`**  
  This notebook handles data preprocessing tasks such as cleaning, tokenization, and preparing review text for model input.

- **`modeling.ipynb`**  
  This notebook covers the fine-tuning and evaluation of a BERT model for rating prediction, using both regression and classification approaches.

## Project Overview

### Objective
The goal is to explore how sentiment polarity and review length influence the performance of rating prediction models. The study utilizes transfer learning with BERT to predict ratings on a continuous scale.

### Key Components
1. **Data Preprocessing**  
   - Text cleaning and tokenization.
   - Sentiment polarity analysis.
   - Review length bucketing.

2. **Modeling**  
   - Fine-tuning BERT for regression and classification tasks.
   - Evaluating model performance using MAE and accuracy metrics.

### Dataset
- **Source**: Rotten Tomatoes movie reviews dataset.
- **Size**: Over 700,000 reviews, covering 17,000+ unique movies.
- **Features**: Review content, ratings, sentiment polarity, word count, etc.

## Installation

To run the notebooks locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Fine-Tuning-BERT-Rating.git
