# deep-learning-pixel-coordinate-prediction
Predicting Pixel Coordinates Using CNN
Problem Statement
Given a 50x50 grayscale image where only one pixel has intensity 255 and all other pixels are 0, predict the (x, y) coordinate of the white pixel using Deep Learning techniques.

This is formulated as a supervised regression problem.

# Pixel Coordinate Prediction Using CNN (Classification Approach)
Objective
Given a 50×50 grayscale image containing a single white pixel, predict the exact pixel location using a Convolutional Neural Network.

Instead of regression, this problem is formulated as a multi-class classification task with 2500 classes.
# conclusion
The problem of predicting the position of a single white pixel in a 50×50 grayscale image was reformulated as a multi-class classification problem with 2500 classes.

A Convolutional Neural Network (CNN) was trained using CrossEntropyLoss to predict the pixel index. The model achieved over 90% training accuracy within 10 epochs and demonstrated highly accurate pixel localization on the test set.

Most prediction errors were limited to adjacent pixels (±1), indicating strong spatial learning. The classification formulation successfully avoided regression collapse and provided stable convergence.

This experiment demonstrates the effectiveness of CNNs in spatial localization tasks and highlights the importance of selecting an appropriate problem formulation.

Final Dependency List (For Report Section)

# Required Dependencies: 

Python 3.8+

CNN

PyTorch

NumPy

Matplotlib

Scikit-learn
