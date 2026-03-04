# 🎬 Movie Rating Prediction Using Machine Learning

## 📌 Project Overview
This project builds a machine learning model to predict movie ratings based on features such as genre, year, duration, and number of votes. The goal is to analyze historical movie data and estimate ratings using regression techniques.

---

## 📊 Dataset
The dataset contains information about Indian movies, including:
- Genre
- Year of release
- Duration
- Votes
- Rating (Target variable)

---

## 🛠 Data Preprocessing
The following preprocessing steps were performed:
- Removed rows with missing rating values
- Cleaned and converted "Votes" column to numeric
- Cleaned and converted "Duration" column to numeric
- Converted "Year" to numeric format
- Applied One-Hot Encoding to categorical features (Genre)

---

## 🤖 Machine Learning Model
- Algorithm Used: Random Forest Regressor
- Train-Test Split: 80% Training, 20% Testing
- Evaluation Metrics:
  - R² Score
  - Mean Squared Error (MSE)

---

## 📈 Results
The model achieved:
- R² Score: ~0.19 (initial model)
- MSE: ~1.49

The relatively low R² score indicates that movie ratings are influenced by many subjective and unstructured factors such as story quality, direction, and audience perception, which are not fully captured in structured dataset features.

---

## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## 📌 Conclusion
This project demonstrates the complete machine learning pipeline including data cleaning, preprocessing, feature engineering, model training, and evaluation. The model can be further improved by incorporating additional features such as actor popularity, director success rate, or sentiment analysis from reviews.

---

## 👤 Author
Rmy4143
