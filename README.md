# Introduction
This project contains all the codes and dataset used in the paper ***'Does Configuration Encoding Matter in Learning Software Performance? An Empirical Study on Encoding Schemes'***. Specifically, the documents include:

- **Encoding.py**: the main program used for loading the dataset, learning the machine learning models, testing the models and saving the results.

 - **mlp_sparse_model.py, mlp_plain_model.py, utils**: We take these codes from 'https://github.com/DeepPerf/DeepPerf', which is a state-of-the-art deep learning model for performance prediction. We use their model as the neural network performance prediction model in our paper.

 - **Data.zip**: contains the datasets for the five systems used in this paper.


 - **Results.zip**: contains the RMSE and training time recorded by 'Encoding.py'. 
Each txt file corresponds to a subject system, and contains the RMSE and training times for 50 runs.

<!-- --- -->

# Prerequisites
 - Python 3.6 - 3.7
 - Tensorflow 1.x

<!-- --- -->

# Datasets
Five subject systems and their datasets are applied in this study as given below:
 - MongoDB
 - Lrzip
 - Trimesh
 - ExaStencils
 - x264
 
The datasets are originally from 'https://github.com/anonymous12138/multiobj' and 'https://github.com/FlashRepo/Flash-MultiConfig',
which are the repositories of two excellent studies in the domain of performance modeling.
Details of the datasets are given in our paper.

<!-- --- -->

# Installation
Download all the codes into the same folder.

<!-- --- -->

# Usage

#### To run the default experiments:
 - Command line: 

 Move to the folder with the codes, and run 
```
python Encoding.py
```

 - Python IDE (e.g., Pycharm): 

Open the Encoding.py file on the IDE, and click 'Run'.


#### To change experiment settings:
Change the codes following the comments in Encoding.py.
 
