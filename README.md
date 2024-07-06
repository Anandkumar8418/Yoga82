# Hierarchical Yoga Pose Detection
<br>
Our aim is to build a Machine Learning model which can detect the pose of a person doing Yoga.We are using Yoga82 Dataset [Link to Dataset](https://sites.google.com/view/yoga-82/home) to train and test our model.
<br>
We did the following things in the project: 
<br>
• Utilized the Yoga-82 Dataset with 28.4K yoga pose images, classifying them into hierarchical classes of 6, 20, and 82.
<br>
• Explored MediaPipe Library to detect Joints and engineered some features like Angles and Centorids of points in the body.
<br>
• Implemented Pandas and Numpy to convert all extracted features from mediapipe into dataset stored as CSV.
<br>
• Implemented a neural network with TensorFlow, achieving 96.38% accuracy using 6 ReLU, 1 Sigmoid, and 4 Dropout layers.
<br>
• Trained and compared classifiers such as Support Vector Machine, Decision Trees, Random Forest, Naive Bayes, K-Nearest Neighbors, Gradient Boost, and Ada Boost to determine the best accuracy.
<br>
• Applied GridSearch using GridSearchCV for hyperparameter tuning of each model for the best accuracy over all parameters.