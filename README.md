# -Test-Suite-Generation-in-Malicious-File-Detection-Across-Multiple-File-Types-Using-Machine-Learning
 This is the code for the implementation of a test suite framework for malicious file detection using ML models and entropy features (Shannon and Rényi). Includes preprocessing, stratified 5-fold validation, confusion matrix, and passing rate analysis. This version is specific to document-based files.

#This repository contains the implementation of a test suite generation framework for detecting malicious files using machine learning models. The approach leverages Shannon entropy (F1) and Rényi entropy (F2, α=2) as core features for training Naïve Bayes, Random Forest, and Decision Tree classifiers. The framework includes  extracting entropy features,  data preprocessing  stratified 5-fold cross-validation, confusion matrix generation, and passing rate calculation to assess detection performance.

Experiments were conducted across four categories of files: document-based, image-based, compressed, and miscellaneous. This code specifically handles document-based files, with identical experiments conducted for the other types.


