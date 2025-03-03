# fake-account-detection-on-instagram-using-ANN 

Description

This project implements an Artificial Neural Network (ANN) to detect fake social media accounts on Instagram. Using user features and engagement metrics, the model predicts whether an account is genuine or fake.

Role of ANN in Fake Account Detection on Instagram
Artificial Neural Networks (ANNs) are deep learning models inspired by the way the human brain processes information. In the context of fake social media account detection, ANN plays a crucial role by learning complex patterns in account behavior and distinguishing between fake and real accounts.

 How ANN Works in Fake Account Detection
Feature Extraction:

Instagram account features like:
Number of followers
Number of following
Post count
Engagement rate (likes/comments per post)
Account age
Data Preprocessing:

Normalize the data to ensure features have a similar scale.
Split into training and testing sets.
Building the ANN Model:

Input Layer: Takes in account features.
Hidden Layers: Learn patterns between real and fake accounts.
Output Layer: Predicts whether an account is fake or real (Binary Classification: 0 = Real, 1 = Fake).
Training the Model:

Use labeled data (real and fake accounts) to adjust weights.
Optimize using backpropagation and gradient descent.
Prediction & Evaluation:

The trained model predicts new account statuses.
Evaluated using accuracy, precision, recall, and F1-score.

Installation

Prerequisites

Python 3.x

Jupyter Notebook

TensorFlow / Keras for ANN implementation

Setup

Clone this repository:

git clone https://github.com/yourusername/fake-account-detection-ann.git
cd fake-account-detection-ann

Install dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook

Run ANN.ipynb to train and test the model.

Usage

Open ANN.ipynb in Jupyter Notebook.

Run all cells to load the dataset, train the model, and evaluate performance.

Check accuracy and classification metrics for results.

Dataset

The dataset contains Instagram account features such as:

Number of followers

Number of followings

Post count

Engagement rate

Account age

Source: Custom dataset (or specify if using a public dataset)

Model & Approach

Machine Learning Model: Artificial Neural Network (ANN)

Architecture:

Input Layer: Takes in Instagram account features.

Hidden Layers: Learn complex patterns for classification.

Output Layer: Predicts whether an account is fake or real.

Training: Uses labeled account data to adjust model weights through backpropagation.

Authors & Credits

Developed by [mirsana]

