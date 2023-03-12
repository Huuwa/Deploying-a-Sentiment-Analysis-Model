# SageMaker Deployment Project
The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural
network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment
Analysis using XGBoost, should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md)
in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

## Project Overview
In this project, I used PyTorch and SageMaker to construct a complete project from end to end. The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to my deployed model which will predict the sentiment of the entered review.

![positive-review](https://user-images.githubusercontent.com/89380757/143674448-ec216992-e64c-45cb-baa4-9872eb96da1e.jpeg)
-----------------------------------------------------------------------------------------------------------------------------------------
![negative-review](https://user-images.githubusercontent.com/89380757/143674450-dda7aef5-3b81-4c2b-88f6-7e7c916d69c4.jpeg)
-----------------------------------------------------------------------------------------------------------------------------------------
![negative-review](https://raw.githubusercontent.com/Abheeshth/Deploying-a-Sentiment-Analysis-Model/491475546d103f55a0843fcd66131d2e047ffb4c/Web%20App%20Diagram.svg)

## Project Information

### Contents

- General Outline
- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 7: Use the model for testing
- Step 6 (again): Deploy the model for the web app
- Step 7 (again): Use the model for the web app

### Libraries

- Amazon SageMaker
- PyTorch
