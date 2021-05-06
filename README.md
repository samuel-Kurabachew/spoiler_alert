# Spoiler Alert

This repository containes the code and neccessary files used in detecting **Spoiler reviews** and deploying the model for making it accessable via a simple web interface using Amazon Sagemaker. The dataset on which the model was trained on is [IMDb spoiler dataset](https://www.kaggle.com/rmisra/imdb-spoiler-dataset) from Kaggle.

## Content

[Spoiler_Alert.ipynb](https://github.com/samuel-Kurabachew/spoiler_alert/blob/main/Spoiler_Alert.ipynb) Contains information about the various methods, approaches and preprocessing steps used to tackle the problem.

Codes and explanations are also included inside the notebook for the following models:
* **Linear Regression**,
* **Naïve Bayes** and,
* **RNN**

[Spoiler_Alert_Deployment](https://github.com/samuel-Kurabachew/spoiler_alert/blob/main/Spoiler_Alert_Deployment.ipynb) This notebook includes a detailed explanation on how we used a type of Recurrent Neural Network called Long Short-Term Memory (LSTM) to build a simple model. On top of this, we go through steps on how to run and validate each code on Amazon Sagemaker including how to make it available for testing with publicly accessible API and a simple web app which interacts with the deployed endpoint.






