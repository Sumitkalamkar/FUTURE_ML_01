# 🎵 Spotify Song Classification by Mood

This project was developed as part of an internship task at **Future Interns**. It focuses on classifying songs based on their **mood** using audio features extracted with `librosa`, followed by training a machine learning model for classification.

## 📁 Dataset

The dataset used is `song_data.csv`, which contains preprocessed Spotify audio features along with mood labels for each song.

## 🎯 Objective

To build a machine learning model that predicts the mood of a Spotify song using its audio features.

## 📊 Features Used

- Extracted audio features such as:
  - Tempo
  - Energy
  - Loudness
  - Danceability
  - and more...

## 🧠 Model Overview

- **Algorithm**: Random Forest Classifier
- **Preprocessing**:
  - Label Encoding for categorical features
  - Standard Scaling for numerical features
- **Evaluation Metrics**:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## 🛠️ Installation

Install all necessary libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn librosa

🚀 How to Run the Project
Place song_data.csv in the same directory as the notebook.

Open task 1 (1).ipynb in Jupyter Notebook.

Run all cells sequentially to train and evaluate the model.

📈 Output Includes
Accuracy of the classifier

Confusion Matrix visualization

Detailed classification metrics

👨‍💻 Author
Sumit — developed as an internship project for Future Interns
