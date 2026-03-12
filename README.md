🎵 Spotify Music Recommendation System

📌 Project Overview

The **Spotify Music Recommendation System** is a Machine Learning project that predicts whether a user will like or dislike a song based on various audio features.
The system analyzes song characteristics and builds predictive models to recommend music aligned with user preferences.

This project demonstrates the **complete Machine Learning pipeline**, including data preprocessing, exploratory data analysis, feature scaling, model training, and evaluation.

---

🎯 Objective

The goal of this project is to build a **classification model** that predicts whether a user will like a song based on its attributes.

The system helps simulate how streaming platforms recommend songs by analyzing musical features and learning patterns from user preferences.

---

📂 Dataset

The dataset used in this project contains various Spotify audio features of songs and a label indicating whether the user liked the song.

Dataset Source:
https://www.kaggle.com/datasets/bricevergnou/spotify-recommendation

Dataset Features

Some of the important features include:

* Danceability
* Energy
* Loudness
* Speechiness
* Acousticness
* Instrumentalness
* Liveness
* Valence
* Tempo

Target Variable:

* **liked** → Indicates whether the user likes the song or not.

---
 ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Missingno
  
🔎 Project Workflow
1️⃣ Data Loading

The dataset is loaded using **Pandas** and inspected using:

head()
describe()
info()

2️⃣ Data Cleaning

Data preprocessing includes:

* Checking missing values
* Identifying duplicate records
* Removing unnecessary columns

Visualization of missing values is performed using the **Missingno** library.

---

3️⃣ Exploratory Data Analysis (EDA)

EDA techniques used in the project:

* Feature distribution visualization using histograms
* Correlation analysis using heatmaps
* Statistical analysis of dataset features

These steps help understand relationships between different musical attributes.

---

4️⃣ Feature Scaling

Feature scaling is performed using **StandardScaler** to normalize input features and improve model performance.

---

5️⃣ Machine Learning Models

Three classification algorithms were implemented and compared:

* Random Forest Classifier
* Decision Tree Classifier
* Support Vector Machine (SVM)

These models were trained on the dataset to predict whether a song will be liked.

---
6️⃣ Model Evaluation

The models were evaluated using multiple performance metrics:

* Precision
* Recall
* F1 Score
* Classification Report

These metrics help measure the effectiveness of the recommendation system.

---

📊 Results

The machine learning models were successfully trained and evaluated to determine the best-performing algorithm for predicting song preferences.

Among the tested models, **Random Forest and Support Vector Machine performed better in terms of precision and recall**.

---

📁 Project Structure

Spotify-Music-Recommendation-System
│
├── Spotify music recommendation sys.ipynb
├── data.csv
└── README.md

 🚀 Future Improvements

Possible improvements for this project include:

* Implementing Deep Learning models
* Deploying the recommendation system as a web application
* Integrating Spotify API for real-time recommendations
* Building a collaborative filtering recommendation system

 Author

Billa Shiva

AI / Machine Learning Student interested in building intelligent data-driven systems.

---

⭐ Acknowledgements

Dataset provided by Kaggle.
Libraries from the Python Machine Learning ecosystem were used to build and evaluate the model.
