# AI vs Real Image Detection

Presented by: Neural Ninjas (SaaS)
- Chinmay Singh
- Jaipaul Chinthakuntla
- Mahananda Nyamagouda
- Nakul Kadam
- Sarat Goli

# Introduction
With the rise of AI image generation tools like Midjourney and DALL·E, it’s becoming increasingly difficult to distinguish real from fake. This project aims to tackle that.

# Context & Problem Statement
The line between synthetic and authentic images is blurring, creating challenges in:
- misinformation detection
- digital identity verification, 
- legal evidence authentication, 
- and artistic originality.
Real-world incidents: Deepfakes in scams, fake news, and AI-generated identities.
A simple scroll through social media can show you AI-generated people who don't exist. That’s why automated detection matters.

# Solution Overview
Data Collection: We collected multiple different data sets from Kaggle. There are total 9067 images that we combined from multiple data
These data sets were preprocessed and transformed into required format. 
Since we are categorizing the image as either AI or Real, this is a classification problem. 
As a team we worked on different datasets, different models with different combination of hyperparameters to evaluate the accuracy of the model. 

# Dataset
- https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images/code
- https://www.kaggle.com/datasets/cashbowman/ai-generated-images-vs-real-images/data

# Results
We explored various models with different datasets and parameters & evaluated the accuracy of those models. 
One thing to highlight is that with the smaller number of images in the training data set, the accuracy of those models was somewhere around 60% - 70%.
Also, when we tried a dataset with limited number of categories, the accuracy was much better.

In this project we are working with ResNet50 model as we got better results with this model. Since this is a pre-trained model, it also helps to reduce the training time and improve accuracy. 
ResNet50 is trained on 1.28 million images, with 50 layers & 1000 categories.

