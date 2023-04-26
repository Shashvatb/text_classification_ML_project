# text_classification_ML_project
## Introduction
This repository exists as a submission of a pretask for project with ML group for SS2023 <br />
For easy visualization, the html file can be viewed instead of the ipynb
## Steps
* Data cleaning - the data is cleaned by applying some basic methods like removing unknown tokens, numeric and alphanumeric tokens and other stop words
* Data splitting - the data is split into train, validation and test data in the split 60-20-20%
* Model Definition - The pytorch model is defined with a very basic architecture as the accuracy is not being tested here
* Vectorizer - A count vectorizer with vocab size of 1000 is defined and the data is converted to vectors
* Training setup - The model, loss function, optimizer and a few basic hyperparameters are setup
* Dataset and dataloader - Pytorch Dataset and Dataloader classes are used to get the data in a format which is easily usable by the pytorch model
* Training - The model is trained and the loses are stored for further purposes
* Saving - The model is saved for future reference
* Visualization - The training losses are visualized (Again, the accuracy is not of consern here)
* Validation - The model is run on validation data and hyperparameters can be tuned on it (here, no hyperparameters were trained)
* Testing - Final testing on the tuned model takes place here

## Submission details
Submitted by: Shashvat Bharti (423146) <br />
Submittion date: 26.04.2023

