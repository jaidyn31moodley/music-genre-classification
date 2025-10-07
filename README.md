# Music Genre Classification Using GTZAN Dataset

## Overview:

This project predicts the genre of a song using precomputed audio features from the GTZAN dataset. It applies machine learning techniques to classify songs into genres and visualize their feature clusters.

### Dataset:

features_30_sec: a pre-extracted features file of the GTZAN dataset, which contains 1000 30-second audio clips of songs from the following genres: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock.

#### Features include:

Chroma, RMS, Spectral centroid, Bandwidth, Rolloff, Zero-crossing rate, Tempo, MFCCs (20 coefficients, mean + variance)

#### Label: 

label (genre of the song)

### Project Workflow:

1. Data Preprocessing

- Loaded audio features and genre labels

- Split data into training and test sets

2. Model Training

- Used a Random Forest Classifier (100 estimators)

3. Evaluation

- Accuracy score

- Classification report (precision, recall, F1-score)

- Confusion matrix heatmap

4. Enhancements

- PCA visualization of genre clusters

- Similarity-based song recommendations using cosine similarity

### Results/Findings

- Random Forest achieved high accuracy on test data

- Confusion matrix reveals which genres are most difficult to distinguish

- PCA visualization shows how genres cluster by audio features

### Example Outputs:

- Confusion Matrix Heatmap

- PCA plot of genres

- Most similar songs (recommendation system)

### Future Improvements:

- Experiment with different models (SVM, Gradient Boosting, Neural Nets)

- Extend to deep learning (CNN on raw audio spectrograms)

- Build an interactive recommendation system

### Technologies Used:

- Python (pandas, numpy, scikit-learn, seaborn, matplotlib)

- Jupyter Notebook

### How to Run:

- Clone/download this repo

- Place features_30_sec.csv in the data/ folder

- Open the Jupyter Notebook

- Run all cells to train the model and view results

Author: Jaidyn Moodley



