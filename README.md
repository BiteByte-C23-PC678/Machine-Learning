# Bitebyte - Machine-Learning
This repository contains a recommender system using a regression model with 6 labels implemented using feedforward neural network architecture.

## Table of Contents
* [Introduction](#Introduction)
* [Datasets](#Datasets)
* [Model Architecture](#ModelArchitecture "Goto Model Architecture")
* [Training](#Training)
* [Evaluation](#Evaluation)

## Introduction
This repository contains a recommender system using a regression model with 6 labels implemented using feedforward neural network architecture.

Team Member : 
* M037DKY3884– Deo Ulina Nopiska Marbun
* M166DSX1489 – Faturrahman Alharitszoe
* M340DKY3933 – Khusna Hanifah

## Datasets
* [Food.com Recipes and Interactions](#https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions?select=RAW_recipes.csv)

We have 5 classes in total:
1. calories
2. protein
3. fat
4. carbohydrates
5. vegetarian

We splitted the dataset into:
* Train (800 Recipes)
* Validation (200 Recipes)
* Test (200 Recipes)

## Model Architecture
A feedforward neural network architecture, also known as a multilayer perceptron (MLP), is a type of artificial neural network where information flows in a forward direction, from the input layer through one or more hidden layers to the output layer. It is called "feedforward" because the information moves through the network without cycles or loops.

## Training 
The code trains a feedforward neural network model using TensorFlow and Keras to make recipe recommendations based on user input. It preprocesses and scales the input data, splits it into training and test sets, builds the model architecture with multiple dense layers, and compiles it with an optimizer and loss function. The model is trained using the training data, with the validation data used to monitor performance. The code also evaluates the model, calculates additional metrics, generates recipe recommendations, and saves the trained model.
![image](https://github.com/BiteByte-C23-PC678/Machine-Learning/assets/72615238/b6ea0d52-f98b-4f7b-91a6-ba20857f7265)

## Evaluation 
The evaluation part of the code occurs after training the model. It starts by using the evaluate method of the trained model to compute the test loss, which represents how well the model performs on unseen data. This test loss value is then printed. Additionally, the code uses the trained model to predict the recipe features for the test data (X_test) and calculates the mean absolute error (MAE) and root mean squared error (RMSE) between the predicted features (y_pred) and the true features (y_test). These metrics provide a quantitative measure of the model's accuracy and performance. The MAE and RMSE values are printed to assess how well the model is predicting the recipe features.
![image](https://github.com/BiteByte-C23-PC678/Machine-Learning/assets/72615238/9f95ab53-754a-46de-987f-b443e2320cd8)


