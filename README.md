# Introduction
This project contains all the codes and dataset used in the paper **'Does Configuration Encoding Matter in Learning Software Performance? An Empirical Study on Encoding Schemes'**. Specifically, the documents include:

- Encoding.py: the main program used for loading the dataset, learning the machine learning models, testing the models and saving the results.

 - MTL_sparse_model.py
 - mlp_sparse_model.py
 - mlp_plain_model.py
We take these codes from 'https://github.com/DeepPerf/DeepPerf', 
which is a state-of-the-art deep learning model for performance prediction.
We use their model as the neural network model in our paper.

 - Data.zip
, which contains the datasets for the five systems used in this paper.
The data are from 'https://github.com/anonymous12138/multiobj' and 'https://github.com/FlashRepo/Flash-MultiConfig',
which are the repositories of two excellent studies in the domain of performance modeling.
The details of the datasets are given in our paper.


 - Results.zip
, which contains the RMSE and training time recorded by 'Encoding.py'. 
Each txt file 

