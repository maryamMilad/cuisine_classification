# Restaurant Cuisine Classification Project

## Overview
This project uses machine learning to classify restaurant cuisines based on various features like average cost, price range, aggregate rating, and votes. The model is built using a Random Forest classifier to predict multiple cuisine types for each restaurant (multi-label classification).

## Dataset
The dataset contains restaurant information including:
- Average Cost for two
- Price range
- Aggregate rating
- Votes
- Cuisines (comma-separated list)

## Features
- Data preprocessing handles missing values
- One-hot encoding for cuisine types
- Combined numerical and categorical features
- Multi-label classification approach

## Model
- Random Forest Classifier
- Test size: 20% of data
- Random state: 42 for reproducibility

## Results
The model provides:
- Overall accuracy score
- Detailed classification report with precision, recall, and f1-score for each cuisine type

## Requirements
- Python 3.x
- pandas
- scikit-learn

## Usage
1. Clone the repository
2. Install required packages: `pip install pandas scikit-learn`
3. Run the Jupyter notebook or Python script

## Future Improvements
- Feature engineering for better performance
- Try different classification algorithms
- Hyperparameter tuning for the Random Forest model
- Implement a more sophisticated multi-label classification approach
