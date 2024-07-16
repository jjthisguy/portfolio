# Netflix Data Science Project

## Overview
This project aims to analyze the Netflix dataset to explore various machine learning questions, including predicting IMDb scores, classifying age certifications, and evaluating differences in IMDb scores between movies and TV shows.

## Objectives
- Identify factors influencing IMDb scores
- Classify age certification based on runtime, release year, genre, etc.
- Test the difference in mean IMDb scores between movies and TV shows using permutation tests

## Data
The dataset is located in the `data` folder and includes features such as runtime, release year, genres, IMDb scores, and age certification.

## Methodology
1. **Data Preparation and Cleaning**:
   - Handled missing values and performed data preprocessing (scripts/data_preprocessing.py).
2. **Exploratory Data Analysis (EDA)**:
   - Visualized and summarized key data insights (notebooks/analysis_notebook.ipynb).
3. **Model Selection and Training**:
   - Implemented and tuned Random Forest and Decision Tree models (scripts/model_training.py).
4. **Evaluation**:
   - Evaluated model performance using accuracy metrics and addressed overfitting.
5. **Hypothesis Testing**:
   - Conducted permutation tests to compare IMDb scores between movies and TV shows.

## Results
- The Random Forest model showed overfitting, while the Decision Tree model provided better generalization.
- The permutation test indicated a significant difference in IMDb scores between movies and TV shows.

## Conclusion
The project highlighted the importance of feature selection and model tuning in predictive analytics. Future work could involve exploring deep learning models and incorporating additional features.

## Future Work
- Explore advanced models such as neural networks.
- Incorporate additional features like viewer ratings and social media sentiment.
- Compare results with datasets from other streaming platforms.
