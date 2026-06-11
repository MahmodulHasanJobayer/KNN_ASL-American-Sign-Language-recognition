# KNN_ASL-American-Sign-Language-recognition
This project estimates alphabet from hand gesture using MediaPipe + KNN algorithm.
- Dataset from [link](https://www.kaggle.com/grassknoted/asl-alphabet) which already converted into landmark.
- Generate Dataset (Generates landmark dataset from images).
- KNN_ASL-American-Sign-Language-recognition (Trains model and recognizes alphabet gestures).

# Requirements
- anaconda
- mediapipe 0.8.1
- opencv 3.4.2 or Later
- scikit-learn 0.23.2 or Later
- matplotlib 3.3.2 or Later

# Training
- After generating landmark dataset from the image dataset:
1. Importing libraries and defining dataset.
2. Creating Train and Test Data.
3. Creating classifier model for our alphabet recognition.
4. Calculate model accuracy.
5. Show graph for adjusting number of n_neighbors.
6. Intialize Mediapipe Hands for alphabet recognition.
