**Access Dataset here: https://www.kaggle.com/datasets/naveenk903/movies-fight-detection-dataset**

# Fight-or-No-fight-classification

This project focuses on detecting fight scenes in movies using computer vision and machine learning techniques. The main objective is to classify video clips as either "fights" or "noFights" by extracting features from the frames and training a classifier.

# Table of Contents
* Installation
* Dataset
* Feature Extraction
* Clustering
* Classification
* Evaluation
* Results

# Dataset
The dataset used in this project is downloaded from Kaggle. It contains video clips labeled as either "fights" or "noFights".

**To download the dataset:**

Copy code

!kaggle datasets download -d naveenk903/movies-fight-detection-dataset

!unzip -q movies-fight-detection-dataset.zip

# Feature Extraction
We use the SIFT (Scale-Invariant Feature Transform) algorithm to extract features from the frames of the videos.

# Clustering
We use KMeans clustering to create a codebook of visual words from the SIFT features.

# Classification
An SVM (Support Vector Machine) classifier is trained using the histograms of codewords as input features.

# Evaluation
The classifier is evaluated on the test set, and performance metrics are calculated.

# Results
**Accuracy:** The overall accuracy of the model in classifying fight and noFight scenes.

**Precision:** The precision of the fight scene detection.

**Recall:** The recall of the fight scene detection.

**F1 Score:** The F1 score of the fight scene detection.

# Usage
Download and unzip the dataset.
Move the dataset to the desired folder.
Extract features from the videos.
Cluster the features using KMeans.
Train the SVM classifier.
Evaluate the classifier using the test set.
