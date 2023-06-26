# Face_Emotion_Classification

The goal of this project is to develop a deep learning model that can accurately classify facial expressions 
into one of seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. 
We will use convolutional neural networks (CNNs) to train our model, as they have been shown to be effective 
in image classification tasks. Our approach involves designing and training a CNN model from scratch on the FER-2013 dataset.

The FER-2013 dataset consists of 48x48 pixel grayscale images of faces that have been automatically registered to be centred and occupy a similar amount of space in each image.
The dataset contains 24,400 images, with 22,968 examples in the training set and 1,432 examples in the public test set. the dataset is available on https://www.kaggle.com/datasets/msambare/fer2013

Here through Implementation of two models we observe that a model with lower complexity and two fully connected layers, rather than one 
can lead to a better generalised model design, with very less overfitting. The emotion classification from face can be used classify
movies into genres from trailers, we can also use it to aggression or angry reactions on CCTV to respond quickly,etc.

# Instruction to run
Download the dataset from the above source and set the path of training data set to train_dir and testing data to test_dir in cell 2. 
