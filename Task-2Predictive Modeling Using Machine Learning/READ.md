# Task 2: Predictive Modeling Using Machine Learning

## Project Title
Fake News Detection Using Machine Learning

## Project Overview

This project aims to classify news articles as Fake News or Real News using Machine Learning techniques and Natural Language Processing (NLP). The model analyzes textual information and predicts the authenticity of news articles.

## Dataset Description

The dataset contains the following attributes:

- id : Unique identifier for each news article
- title : Headline of the news article
- author : Author of the article
- text : Content of the news article
- label :
  - 0 = Real News
  - 1 = Fake News

## Data Preprocessing

The following preprocessing steps were performed:

- Handled missing values
- Combined author and title columns
- Removed special characters
- Converted text to lowercase
- Removed English stopwords
- Applied stemming using Porter Stemmer

## Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) Vectorization was used to convert text data into numerical features suitable for machine learning algorithms.

## Machine Learning Models Used

### Logistic Regression
Used as the primary classification model.

### Naive Bayes
Implemented for performance comparison.

### Decision Tree
Implemented to compare classification accuracy with other models.

## Model Training

The dataset was divided into:

- Training Data: 80%
- Testing Data: 20%

The models were trained using the training dataset and evaluated using the testing dataset.

## Performance Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- ROC Curve
- AUC Score

## Results

| Algorithm | Accuracy |
|------------|------------|
| Logistic Regression | 0.9790865384615385|
| Naive Bayes | 0.9550480769230769 |
| Decision Tree | 0.9932692307692308 |


## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib

## Key Learning Outcomes

- Text preprocessing using NLP
- Feature extraction using TF-IDF
- Machine Learning model training
- Performance evaluation using Accuracy, Confusion Matrix, and ROC Curve
- Comparison of multiple classification algorithms

## Conclusion

The Fake News Detection model successfully classified news articles as fake or real using machine learning techniques. Logistic Regression provided strong predictive performance and demonstrated the effectiveness of NLP-based text classification.
