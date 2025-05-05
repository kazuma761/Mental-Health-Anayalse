# Mental Health State Detection

This repository contains multiple experiments and research approaches to determine the most effective method for detecting mental states, such as depression, from textual data.

## Repository Structure

- **transcripts.csv**: The original dataset containing raw transcripts.
- **merged_output.csv**: The cleaned and processed dataset generated from `transcripts.csv`.
- **bert.ipynb**: Jupyter notebook using BERT-based models for mental state detection.
- **cnn.ipynb**: Jupyter notebook implementing a Convolutional Neural Network approach.
- **rain-xgboost.ipynb**: Jupyter notebook using XGBoost for classification.
- **f1_score.ipynb**: Notebook for evaluating model performance using the F1 score.
- **positive.txt, negative.txt, depressed.txt**: Word lists used for detecting depression and sentiment from the processed data.
- **Link.txt**: (Purpose unspecified, likely for references or resources.)

## Workflow

1. **Data Cleaning**: Start with `transcripts.csv` and clean the data to produce `merged_output.csv`.
2. **Analysis**: Use the Jupyter notebooks to analyze `merged_output.csv` with different machine learning models.
3. **Word List Detection**: The `.txt` files (positive, negative, depressed) are used within the notebooks to help detect depression and sentiment in the dataset.

## Objective

The goal of this project is to compare various machine learning and word-based approaches to accurately detect mental states from text data.

---
Feel free to contribute or raise issues for further improvements.
