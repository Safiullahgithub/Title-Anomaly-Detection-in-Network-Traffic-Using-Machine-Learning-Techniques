# Title-Anomaly-Detection-in-Network-Traffic-Using-Machine-Learning-Techniques
Anomaly detection is a critical aspect of cybersecurity, as it helps identify suspicious patterns or behaviors in network traffic that may indicate malicious activities. This project focuses on utilizing machine learning techniques to enhance anomaly detection accuracy, particularly in identifying complex abnormalities that traditional rule-based approaches might miss.
# Dataset
We employ the NSL-KDD dataset, a widely used benchmark dataset in intrusion detection research. This dataset contains both normal and malicious network traffic instances, along with various features such as protocol types, service names, and flag values. It consists of 125,973 instances, with pre-existing class designations for ordinary and anomalous cases.

# Feature Creation and Selection
Feature extraction methods such as Principal Component Analysis (PCA) and Information Gain are used to extract relevant features from the dataset. Recursive Feature Elimination (RFE) and correlation analysis are then applied to select the most discriminative features for anomaly detection.

# Machine Learning Algorithms
Several machine learning algorithms are employed for anomaly detection:

Isolation Forest: An unsupervised learning algorithm that isolates anomalies by identifying outliers in datasets.
One-Class SVM (Support Vector Machine): Another unsupervised approach that learns the normal data structure and identifies anomalies as data points deviating from this structure.
K-means Clustering: An unsupervised clustering technique that divides data into predetermined groups based on similarity, useful for detecting anomalies in clusters with few data points.
# Implementation
Python is the primary programming language used for this project due to its readability and the availability of libraries for data analysis and machine learning. The scikit-learn library is utilized for implementing machine learning algorithms, while pandas is used for data manipulation and preprocessing tasks.

# Evaluation
The performance of the models is evaluated using X-Fold Cross-Validation with k=10 folds. Evaluation metrics such as Precision, Recall, F1-score, and Area Under the ROC Curve (AUC-ROC) are used to assess the models' performance. The models are compared to existing techniques and baseline models reported in scholarly journals.

# Authors and References
Authors: S. Lee, D. Miller, J. Chen
Title of Reference Paper: "Enhancing Anomaly Detection in Network Traffic Using Machine Learning Techniques"
References:
Dua, D. and Graff, C. (2019). NSL-KDD Data Set. Retrieved from http://www.unb.ca/cic/datasets/nsl.html
A. Gupta et al., "Enhancing Anomaly Detection in Network Traffic Using Machine Learning Techniques," Journal of Cybersecurity Research, vol. 25, no. 2, pp. 50-65, 2023.
