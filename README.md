# Deep-Learning
This repository consists of 3 independent Deep Learning projects using Tensorflow2.0 and Keras.

**1.) One Shot Learning with minimal training data**

•	Implemented a compact Siamese Network for building a speaker verification system to confirm whether the speech signal is from the authorized speaker. Hence, translated a multi-class classification problem into a binary classification problem.

•	The model was trained on GCP VM instance with approx. 3K signal pairs for 50 distinct speakers.

**Project USP:** Problem statement was to classify the speeches to its corresponding user. The data consisted of 50 users with 500 speech signals for each speaker. I felt that it is a small training data given the number of classes. Also, if a new user comes in the entire data set has to be retrained (assuming the new speaker gets his own set of speech signals).
This problem can be overcome by following the one shot learning paradigm. Hence instaead of multiclass classification I altered the use case to binary classification. The system takes input as 2 utterences and decides whether its from the same speaker or not!

The data has not been uploaded because of confidentiality reasons (I don't own the right to upload the data-set).

**2.) Cifar10 image recogonition and classification with data augmentation using CNN**

**3.) Signal denoising (Source Seperation)**

•	Prototyped a novel speech denoising system using LSTM and dense networks formulated as a regression problem.

•	Developed metrics and visualizations for different models (1-D & 2-D CNNs) before finalizing the LSTM model.

•	The original network was compressed by 95% by killing redundant weights using SVD. SNR=23dB

The code for this project is the POC of actual one. Again, the data-set has not been uploaded for the same reasons.
