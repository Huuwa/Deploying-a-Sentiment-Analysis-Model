# SageMaker Deployment Project
The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural
network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment
Analysis using XGBoost, should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md)
in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

## Project Overview
In this project, I used PyTorch and SageMaker to construct a complete project from end to end. The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to my deployed model which will predict the sentiment of the entered review.

![positive-review](https://user-images.githubusercontent.com/89380757/143674448-ec216992-e64c-45cb-baa4-9872eb96da1e.jpeg)
![negative-review](https://user-images.githubusercontent.com/89380757/143674450-dda7aef5-3b81-4c2b-88f6-7e7c916d69c4.jpeg)
