# BME450-EpilepticSeizureRecognition
# Title: 
  "Epileptic Seizure Recognition"
# Team members:
  Sanjana Prashanth (sprasha09) and Arwa Neemuchwala (aneemuch)
# Project Description:
  Dataset: https://www.kaggle.com/datasets/harunshimanto/epileptic-seizure-recognition
  
  This project aims to create a neural network model to detect seizure activity from a restructured EEG dataset obtained from the UCI Machine Learning Repository. The dataset contains recordings from 500 subjects, each spanning 23.6 seconds and sampled into 4097 data points. These were further divided into 23 chunks of 178 data points per second, resulting in 11,500 samples with 178 features each. The dataset is labeled into five classes, with class 1 representing seizure activity and the other classes representing non-seizure states. 
  The proposed methodology involves preprocessing the data through normalization and label encoding, followed by splitting it into training, validation, and test sets. A feedforward neural network will be implemented using frameworks like TensorFlow or PyTorch, incorporating multiple hidden layers with activation functions, dropout, and batch normalization for regularization. Model training will involve monitoring loss and accuracy, optimizing hyperparameters, and applying techniques like early stopping to prevent overfitting. Evaluation metrics such as accuracy, precision, recall, and F1-score will be used to assess model performance. Successful implementation of this system can significantly aid in proper and timely diagnosis and management of epilepsy, providing valuable support for medical professionals and patients.
