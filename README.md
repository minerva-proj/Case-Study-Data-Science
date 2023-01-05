# Overview of the Coursework

The aim of this project is to compare the performance of different supervised machine learning algorithms for detecting fake notes. This repository contains a Jupyter notebook with code to compare the performance of various supervised machine learning models on a given dataset.

***

# Requirements
* Python3
* Jupyter Notebook (can be installed using pip install jupyter)
* Any necessary Python libraries specified in the notebook

# Dataset

The dataset used in this project is the "Fake Note Detection" dataset from the UCI Machine Learning Repository. It contains 1372 instances and 5 attributes. The attributes are:

* Variance of Wavelet Transformed image (continuous)
* Skewness of Wavelet Transformed image (continuous)
* Kurtosis of Wavelet Transformed image (continuous)
* Entropy of image (continuous)
* Class (binary, 1 for fake and 0 for genuine)

# Preprocessing
Before the data is used to train the machine learning models, it must be preprocessed. This includes splitting the data into training, validation and test sets, and performing feature scaling.

# Machine Learning Models
The following supervised machine learning algorithms will be compared in this project:

* K-Nearest Neighbors (KNN)
* Logistic Regression (LR)
* Random Forest (RF)
* Support Vector Machine (SVM)
* Naive Bayes (NB)

# Evaluation
The performance of each machine learning model will be evaluated using a variety of metrics, including accuracy, precision, recall, and f1-score. The model with the highest average performance across all metrics will be considered the best model for fake note detection.

# Usage
To use the code, follow these steps:

1. Place the code in the same directory as the dataset file.
2. Clone this repository to your local machine.
3. Open a terminal in the repository directory.
4. Run the command jupyter notebook. This will launch the Jupyter Notebook server and open the notebook in your web browser.
5. Specify the name of the dataset file and the path to it in the 'data' variable.
6. Follow the instructions in the notebook to run the code.

# Additional Information
The notebook includes explanations and comments for each block of code, as well as markdown cells with additional information. Be sure to read these for a better understanding of what the code is doing.


# Output
The code will output the evaluation scores for each model, as well as a summary of the results.

# Troubleshooting
If you encounter any issues running the notebook, make sure you have all the necessary libraries installed and that you are using the correct version of Python. If the issue persists, please create an issue in this repository with a detailed description of the problem and any error messages you are receiving.
