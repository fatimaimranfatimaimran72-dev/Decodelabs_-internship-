# Decodelabs_-internship-
I have my internship at decodelabs in data science and I collect a dataset of wethers pictures and by using machine learning I make a small prediction application after preprocessing and clean the data 
I have a dataset of different type of weather's in my drive and I make a prediction app...
this code in python language and it execute the application completely 
Overview
This project predicts weather conditions from images using HOG feature extraction and an SVM classifier. Given an input image, it identifies whether the weather is Sunny, Rainy, Cloudy, Foggy, or Snowy.
Dataset
Images are sourced from Google Drive, organized in class folders. They are converted to grayscale, resized to 128×128, and normalized before use.
How It Works
Images are loaded and cleaned, then HOG features are extracted to capture edge and texture patterns. These features are scaled and fed into an SVM with an RBF kernel (C=10) for classification. The model is evaluated using accuracy, F1-score, and 5-fold cross-validation.
Prediction
Python
Tools Used
Python, OpenCV, scikit-learn, scikit-image, NumPy, Matplotlib, and Seaborn.
Author
Fatima Imran
Task 5 — Predictive Model / Insight Project