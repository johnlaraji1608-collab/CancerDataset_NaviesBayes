# CancerDataset_NaviesBayes
🧬 Cancer Detection using Gaussian Naive Bayes
📌 Overview

This project implements a Gaussian Naive Bayes Classifier to predict whether a tumor is benign or malignant using a cancer dataset.

Gaussian Naive Bayes is a probabilistic machine learning algorithm based on Bayes’ Theorem, and it assumes that features follow a normal (Gaussian) distribution, making it suitable for continuous medical data .

🎯 Objectives
Build a classification model for cancer detection
Apply Gaussian Naive Bayes on medical data
Analyze feature distributions
Visualize model performance
Evaluate prediction accuracy
🧠 Theory

Gaussian Naive Bayes works based on:

Feature independence assumption
Gaussian distribution of features

The likelihood is calculated using:

P(x∣y)=
2πσ
2
	​

1
	​

e
−
2σ
2
(x−μ)
2
	​


Where:

μ → Mean of feature values
σ² → Variance of feature values

The model predicts the class with the highest posterior probability.

📂 Dataset
Dataset Name: Cancer Dataset
Commonly used for:
Tumor classification (Benign / Malignant)
Contains multiple medical features such as:
Radius
Texture
Perimeter
Area
⚙️ Workflow
Import required libraries
Load dataset
Preprocess data (handle missing values, scaling if needed)
Split dataset into training and testing sets
Train the Gaussian Naive Bayes model
Predict test results
Evaluate model performance
Visualize outputs
📊 Visualizations
🔹 1. Gaussian Distribution Plot
Shows bell curves for each class
Helps understand how features differ between benign and malignant cases
🔹 2. Decision Boundary Plot
Displays how the model separates cancer classes
Helps visualize classification regions
🔹 3. Scatter Plot
Shows distribution of data points
Helps identify patterns in the dataset
📈 Results
The model effectively classifies cancer cases
Works well with continuous medical data
Visualization improves understanding of predictions
Provides fast and efficient classification
🚀 How to Run
Open the notebook in Google Colab
Run all cells sequentially
View predictions and visualizations

👉 Colab Link:
https://colab.research.google.com/github/johnlaraji1608-collab/CancerDataset_NaviesBayes/blob/main/CancerDataset_NaviesBayes.ipynb

🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
📚 Applications
Medical diagnosis
Disease prediction
Healthcare analytics
Early cancer detection systems
📌 Conclusion

Gaussian Naive Bayes is a simple yet powerful algorithm for medical classification tasks. Its assumption of normally distributed features makes it highly effective for continuous datasets like cancer diagnosis.
