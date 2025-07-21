# LSTM-Based Sentiment Analysis of Drug Reviews

## Project Summary
This initiative leverages Long Short-Term Memory (LSTM) neural networks, a form of recurrent neural network, to analyze the sentiment of drug-related user reviews. The objective is to classify feedback as positive or negative, providing deeper understanding of patients' experiences with various medications.

## Background
The project applies Natural Language Processing (NLP) methods, specifically LSTM models, to interpret sentiment in drug review data—offering actionable insights to enhance both patient support and pharmaceutical evaluation. The sentiment classifier demonstrates an accuracy rate of 86%, establishing a robust tool for discerning patient sentiment in the health domain.

## Technology Stack
- Python programming language
- LSTM neural network architecture
- Pandas for handling and filtering data
- Matplotlib and Seaborn for creating data visualizations
- Scikit-learn for evaluating model performance
- Jupyter Notebook for interactive analysis and reporting

## Data Details

The dataset, sourced from the UCI Machine Learning Repository, consists of patient narratives tied to specific medications, the corresponding illnesses, and satisfaction ratings (on a 10-point scale). Dataset structure:

- **Total records:** 161,297
- **Attributes:** 7 (drugName, condition, review, rating, date, usefulCount)

### Main Features
- **Drug Name:** The name of the prescribed medication.
- **Condition:** The ailment treated by the drug.
- **Review:** Written feedback from patients.
- **Rating:** Patient’s rating on a 10-star scale.
- **Date:** Review submission date.
- **Useful Count:** Number of users who rated the review as helpful.

Because there were no predefined sentiment labels, sentiments were inferred from the numerical ratings, allowing the model to effectively become the basis for analyzing patient satisfaction and feedback in healthcare contexts.

## Performance
The implemented LSTM model reached 86% accuracy in identifying the sentiment of drug reviews, providing practical insights for both healthcare providers and the pharmaceutical industry.

## Acknowledgments
This work draws inspiration from [Purvansh-Jain/DRUG-REVIEW-SENTIMENT-ANALYSIS](https://github.com/Purvansh-Jain/DRUG-REVIEW-SENTIMENT-ANALYSIS) and acknowledges all contributors to the dataset and underlying technologies.
