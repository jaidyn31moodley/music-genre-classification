🎶 Music Genre Classification (GTZAN Dataset)
📌 Overview

This project predicts the genre of a song using precomputed audio features from the GTZAN dataset
.
It applies machine learning techniques to classify songs into genres and visualize their feature clusters.

📂 Dataset

File used: features_30_sec.csv

Features include:

Chroma, RMS, Spectral centroid, Bandwidth, Rolloff

Zero-crossing rate, Tempo

MFCCs (20 coefficients, mean + variance)

Label: label (genre of the song)

⚙️ Project Workflow

Data Preprocessing

Loaded audio features and genre labels

Split data into training and test sets

Model Training

Used a Random Forest Classifier (100 estimators)

Evaluation

Accuracy score

Classification report (precision, recall, F1-score)

Confusion matrix heatmap

Enhancements

PCA visualization of genre clusters

Similarity-based song recommendations using cosine similarity

📊 Results

Random Forest achieved high accuracy on test data

Confusion matrix reveals which genres are hardest to distinguish

PCA visualization shows how genres cluster by audio features

🔍 Example Outputs

Confusion Matrix Heatmap

PCA plot of genres

Most similar songs (recommendation system)

🚀 Future Improvements

Experiment with different models (SVM, Gradient Boosting, Neural Nets)

Extend to deep learning (CNN on raw audio spectrograms)

Build an interactive recommendation system

💻 Technologies Used

Python (pandas, numpy, scikit-learn, seaborn, matplotlib)

Jupyter Notebook

📁 How to Run

Clone/download this repo

Place features_30_sec.csv in the data/ folder

Open the Jupyter Notebook

Run all cells to train the model and see results

✨ Author: Jaidyn Moodley
