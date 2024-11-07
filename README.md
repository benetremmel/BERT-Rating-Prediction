# Fine-Tuning BERT for Rating Prediction from Textual Online Reviews

This repository contains the code and resources for my thesis project: **Fine-Tuning BERT for Rating Prediction from Textual Online Reviews**. The project focuses on predicting movie review ratings using natural language processing (NLP) techniques, leveraging BERT-based models.

## Repository Structure

- **`data_preprocessing.ipynb`**
  This notebook handles data preprocessing as well as sentiment analysis using a multilingual BERT model (bert-base-multilingual-uncased-sentiment). 
- **`rating_prediction_modeling.ipynb`**
  This notebook covers the fine-tuning and evaluation of a BERT model for rating prediction, using regression approaches. It includes experiments with multiple BERT variants, such as Small BERT and BERT Base, to assess their
  performance and effectiveness.
  
## Project Overview

### Objective
The goal is to explore how sentiment polarity and review length influence the performance of rating prediction models. The study utilizes transfer learning with BERT to predict ratings on a continuous scale.

### Key Components
1. **Data Preprocessing**  
   - Text cleaning
   - Normalization of Ratings
   - Sentiment polarity analysis.

2. **Modeling**  
   - Fine-tuning BERT for a regression task.
   - Evaluating model performance using MAE.

### Dataset
- **Source**: Rotten Tomatoes movie reviews dataset.
- **Size**: Over 1M reviews, covering 17,000+ unique movies.
- **Features**: Review content, ratings, sentiment polarity, word count, etc.

## Installation

To run the notebooks locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Fine-Tuning-BERT-Rating.git
