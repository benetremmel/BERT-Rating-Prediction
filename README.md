# Fine-Tuning BERT for Rating Prediction from Textual Online Reviews

The project focuses on predicting movie review ratings using natural language processing (NLP) techniques, leveraging BERT-based models.

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
   - EDA  
   - Sentiment polarity analysis using **`bert-base-multilingual-uncased-sentiment`**.  

2. **Modeling**  
   - Fine-tuning **Small BERT** and **BERT Base** for a regression task.  
   - Training and evaluation with:  
     - **Single-feature configuration** (reviews only).  
     - **Multi-feature configuration** (reviews + additional features).  
   - Evaluating model performance using **Mean Absolute Error (MAE)**. 

### Dataset
- **Source**: Rotten Tomatoes movie reviews dataset.
- **Size**: Over 1M reviews, covering 17,000+ unique movies.
- **Features**: Review content, ratings, sentiment polarity, word count, etc.

## Installation

To run the notebooks locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Fine-Tuning-BERT-Rating.git

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

3. Ensure the dataset is placed in the data/ directory.

## Usage

- Run `data_preprocessing.ipynb` to clean and preprocess the dataset.
- Run `rating_prediction_modeling.ipynb` to fine-tune the BERT models and evaluate their performance.

## Results

- Achieved a **Mean Absolute Error (MAE)** of 0.45 on the validation set for rating prediction.
- Demonstrated high performance across different feature configurations.

## Technologies Used

- Python
- Hugging Face Transformers
- TensorFlow/Keras
- Pandas, NumPy, Matplotlib

## Future Work

- Incorporating additional NLP techniques to further enhance model accuracy.
- Exploring other pre-trained models like GPT or RoBERTa for rating prediction.

## Contributors

- **Benedikt Tremmel** - Master's student in Business Analytics at Nova SBE.

