# Personality-Prediction
 

<img width="899" alt="Screenshot 2023-08-27 at 9 49 14 PM" src="https://github.com/Naivedya-Rai/Personality-Prediction/assets/122347651/94981c94-0e01-4d54-80ab-b108ff50ec0d">

# Personality Prediction using Machine Learning - MBTI Personality Predictor 

This project aims to predict personality types based on text data using Machine Learning techniques. The dataset used for this project includes text posts along with the corresponding personality type indicators based on the Myers-Briggs Type Indicator (MBTI).

## Table of Contents
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Results](#results)

## Dataset Description

The dataset consists of text posts, each associated with one of the 16 MBTI personality types. The posts are preprocessed, and the text data is used to train machine learning models to predict the four dimensions of MBTI, which include:
- Introversion (I) / Extroversion (E)
- Intuition (N) / Sensing (S)
- Feeling (F) / Thinking (T)
- Judging (J) / Perceiving (P)

## Data Preprocessing

The text data is preprocessed to clean and tokenize the posts. This involves removing stopwords, special characters, and links. Additionally, the MBTI personality type indicators are encoded for model training.

## Feature Engineering

Feature engineering involves transforming text data into numerical form. Text data is represented using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) to create features that can be used for model training.

## Model Training

Multiple machine learning models are trained for each of the four dimensions of MBTI. Models include:
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)

The dataset is split into training and testing sets, and each model is trained individually to predict a specific dimension of the personality type.

## Prediction

After model training, the models are used to predict personality types for new text data. Users can input text, and the models will predict the personality type based on that input.

![image](https://github.com/Naivedya-Rai/Personality-Prediction/assets/122347651/9255965e-2fee-4c30-ae79-7a68dada8f96)


## Results

The accuracy of each model in predicting the different dimensions of MBTI is reported. The results show how well the models perform in classifying personality types based on text data.

Feel free to explore this project and the results in more detail by visiting the provided Jupyter notebooks and scripts.

## Dataset Source
The dataset used in this project can be found on Kaggle

## Questions or Feedback
If you have any questions or feedback, please don't hesitate to reach out by creating an issue or contacting the project contributors.



