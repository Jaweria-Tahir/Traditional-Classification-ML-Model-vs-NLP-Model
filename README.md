# Halal vs Haram ML vs LSTM

Traditional machine learning and NLP LSTM model for classifying food products as **Halal or Haram** based on their ingredient lists.

## Objective

This project compares two approaches:

* **Traditional ML:** Ingredient lists converted into multi-hot encoded features and used with a classification model.
* **NLP + LSTM:** Ingredient text converted into token sequences and processed using an Embedding layer and LSTM.

Both approaches are trained and evaluated on the same dataset to provide a fair comparison.

## Dataset

**Dataset:** Food ingredients dataset with halal label
**Source:** Kaggle
**Link:** https://www.kaggle.com/datasets/irfanakbarihabibi/food-ingredients-dataset-with-halal-label

The dataset contains food ingredient lists with **Halal/Haram labels**. It is used for both the Traditional ML and NLP (LSTM) approaches to ensure a fair comparison.

### Data Preparation

The dataset was cleaned and prepared for binary classification:

* Removed/handled missing values
* Removed ambiguous samples where applicable
* Kept only **Halal** and **Haram** classes
* Applied the same train/validation/test split to both models


## Evaluation

The models will be compared using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Error Analysis
