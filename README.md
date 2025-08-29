# [Hate Speech Detection - RNN]

## Overview
The goal of this project is to train an RNN model to identify social media posts with hate speech. I focused on learning how to use NLKT and how to choose and optimize my deep neural network for social media training.

## Data
- Kaggle dataset: collection of text segments classified as hateful or non-hateful
- https://data.mendeley.com/datasets/9sxpkmm8xn/1
- Preprocessing steps: Used NLTK to tokenize the data and tried out different levels of text processing (minimal vs aggressive processing)

## Methods
- Compared LSTM model, CNN_LSTM model, and GRU model. Used confusion matrix and train_test validation plots for optimization
- Libraries: tensorflow, sklearn, NLTK, wordcloud, plotly

## Results
- CNN_LSTM was my chosen model after comparisons
- Achieved 87.5% accuracy in identifying hateful posts. Needs improvement
- Visualizations (embed plots) Figure out how to add my accuracy plots and others.
  

## Key Learnings
- The biggest takeaway from this project was that time constraints and hardware constraints are much more important than I realized. I had to adjust my optimization techniques based on how long it took to train and test my models. My ultimate choice of RNN was based primarily on the benefit of being much faster to train than the others, while retaining high accuracy.
