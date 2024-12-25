# PneumoniaDetection
Pneumonia Detection Using Chest X-Ray Images
This repository uses Support Vector Machines (SVM) and Histogram of Oriented Gradients (HOG) features to detect pneumonia from chest X-ray images. Key features include:

Preprocessing: Resizes and converts images to grayscale.
Feature Extraction: Uses HOG for efficient representation.
Model Training: Fine-tunes SVM with grid search for optimal performance.
Evaluation: Provides accuracy, confusion matrix, and classification reports.
Visualization: Displays test predictions with actual labels.
Model Saving: Exports the trained model using joblib.
Achieved 86% accuracy on test data. Requires Python 3.x, NumPy, Scikit-learn, and other libraries. Place your dataset in the specified format and run the script to train and test the model.
