Comment Toxicity Detector using TensorFlow and Keras
This Jupyter Notebook project_5_comment toxicity detector.ipynb focuses on building a comment toxicity detection model using TensorFlow and Keras. The code demonstrates the process of training and utilizing a toxicity detection model for comments.

Overview
Data Loading and Preparation: Utilizes a dataset (train.csv) containing comments for toxicity detection.

Text Preprocessing: Uses TensorFlow's TextVectorization to convert words into integers, preparing the text data for model training.

Model Building:

Uses a pre-trained model (toxicity_detector.h5) loaded with Keras to showcase prediction.
Contains commented-out code for a sequential model architecture using an Embedding layer, Bidirectional LSTM, and dense layers for feature extraction.
Model Evaluation:

Includes code snippets for predicting toxicity levels for a sample comment.
Also, there are sections (commented out) demonstrating the use of metrics like Precision, Recall, and Categorical Accuracy for model evaluation on a test dataset.
Instructions
Data: Ensure the availability of the train.csv file or replace it with your dataset.
Pre-Trained Model: The code references a pre-trained model file toxicity_detector.h5.
Execution: Sections are commented out to avoid running the code entirely. Uncomment and execute specific sections as needed.
Requirements
TensorFlow
Pandas
Matplotlib
Scikit-learn
How to Use
Open the Jupyter Notebook using Colaboratory or Jupyter Notebook environment.
Make sure to have the required libraries installed.
Load the necessary dataset and model files.
Uncomment and execute sections of code as per requirements for data loading, model building, or evaluation.
