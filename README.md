# Movie Rating Prediction with Python

## Project Overview

This project aims to predict movie ratings using Machine Learning techniques. The model analyzes various movie attributes such as Genre, Director, Actors, Duration, and Votes to estimate the IMDb rating of a movie.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, prediction, and evaluation.

---

## Dataset

The dataset contains information about Indian movies, including:

* Movie Name
* Genre
* Director
* Actor 1
* Actor 2
* Actor 3
* Duration
* Votes
* Rating

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## Machine Learning Model

**Random Forest Regressor**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Project Workflow

### 1. Data Collection

* Load IMDb Movies India dataset.

### 2. Data Preprocessing

* Remove missing values.
* Clean Duration column.
* Clean Votes column.
* Convert Rating into numeric format.

### 3. Feature Selection

Selected features:

* Genre
* Director
* Actor 1
* Actor 2
* Actor 3
* Duration
* Votes

### 4. Feature Engineering

* Handle missing values using SimpleImputer.
* Encode categorical features using One-Hot Encoding.

### 5. Model Training

* Split data into training and testing sets.
* Train Random Forest Regressor.

### 6. Model Evaluation

Evaluate performance using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Results

Model Performance:

* MAE = 0.52
* RMSE = 0.74
* R² Score = 0.81

The model explains approximately 81% of the variation in movie ratings, indicating strong predictive performance.

---

## Project Structure

Movie-Rating-Prediction/

├── IMDb Movies India.csv

├── movie_rating_prediction.ipynb

├── README.md

└── requirements.txt

---

## Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Deployment using Flask or Streamlit
* Deep Learning-based rating prediction

---

## Conclusion

This project successfully predicts movie ratings using machine learning techniques. By leveraging movie metadata such as genre, director, cast, duration, and votes, the model achieves reliable prediction performance and provides valuable insights into factors influencing movie ratings.
