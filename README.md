# Face_Emotion_Classification

The goal of this project is to develop a deep learning model that can accurately classify facial expressions 
into one of seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. 
We will use convolutional neural networks (CNNs) to train our model, as they have been shown to be effective 
in image classification tasks. Our approach involves designing and training a CNN model from scratch on the FER-2013 dataset.

The FER-2013 dataset consists of 48x48 pixel grayscale images of faces that have been automatically registered to be centred and occupy a similar amount of space in each image.
The dataset contains 24,400 images, with 22,968 examples in the training set and 1,432 examples in the public test set. the dataset is available on https://www.kaggle.com/datasets/msambare/fer2013, i have uploaded some sample dataset.

Here through Implementation of two models we observe that a model with lower complexity and two fully connected layers, rather than one 
can lead to a better generalised model design, with very less overfitting. The emotion classification from face can be used classify
movies into genres from trailers, we can also use it to aggression or angry reactions on CCTV to respond quickly,etc.

# Instruction to run
Download the dataset from the above source and set the path of training data set to train_dir and testing data to test_dir in cell 2. 

# Examples from dataset
![PrivateTest_1623042](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/b3f15d3a-27e5-45d9-be53-537fb323d9e4)
class=angry
![PrivateTest_3929526](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/b356f8d2-f544-4860-8bb0-5baf53efdb15)
class=disgust
![PrivateTest_134207](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/a4891f9f-c0ca-4364-a5c1-fb37eb9a2d5d)
class=fear
![PrivateTest_1140198](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/53b790a7-2fc1-4456-96ca-7adb9b97a987)
class=happy
![PrivateTest_1129340](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/174978a0-6381-4171-8910-1addc151bca2)
class=neutral
![PrivateTest_552501](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/f7b15ab7-7adf-4cce-b027-a35fbb81a886)
class=sad
![PrivateTest_914251](https://github.com/Ross0121/Face_Emotion_Classification/assets/74859623/d337530e-5b42-4c9b-9868-9b9320cb9f47)
class=surprise

