##PROJECT TITLE : FACIAL EMOTION RECOGNITION ~ REAL TIME

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).
Being able to recognize facial expressions is key to nonverbal communication between humans, and the production, perception, and interpretation of facial expressions have been widely studied.
The ability to recognize facial expressions automatically enables novel applications in human-computer interaction and other areas.
Consequently, there has been active research in this field, with several recent works utilizing Convolutional Neural Networks (CNNs) for feature extraction and inference. 
These works differ significantly in terms of CNN architectures and other factors.
This notebook utilizes a 3 layered CNN architecture where the main aim is to squeeze out maximum accuracy from a simplistic model. 
We have also used methods to reduce overfitting thus increasing the performance of the model on unknown data. 
We have also created visualizations for an intuitive understanding of what actually happens inside each and every CNN layer of our architecture and how each layer learns different aspects of a particular image.
At the end we have made the model live by integrating it with our webcam and detecting facial eemotions in real-time. Now let's dive into a step by step process on how we did it:


##Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1)Python 3 https://www.python.org/downloads/
2)Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy,OpenCV,keras https://www.anaconda.com/download/

##Built With
1) ipython-notebook - Python Text Editor
2) OpenCV - It is used for processing images
3) Keras - Deep Learning Library
4) Sklearn: It is a Machine Learning library but here it is used just to calculate accuracy and confusion matrix.
5) Tensorflow - To build a deep learning model and used for Open CV2



##Source Data
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge



##Real-World Business Objective & Constraints
1)Low-latency is required.
2)Interpretability is important for still images but not in real time. For still images, probability of predicted expressions can be given.
3)Errors are not costly.

##Getting Started
To run the code -
1) Download FER2013 dataset from Kaggle Facial Expression Recognition Challenge and extract in the main folder.
2) Run the Real-Time Facial Emotion Recognition.ipynb file 

##Authors
Sayali Borse
Spurthi Shetty
