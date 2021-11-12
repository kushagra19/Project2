<h1 align="center">
<span style = "color: #FFC300">
Project2
</span>
</h1>
***
## Introduction
 This repository consists of solutions to project2 and data files used for the same.
***
## Installation
For installing the repository use the command below in your terminal.<br>
<code>
<blink>
    git clone https://github.com/kushagra19/Project2     
</blink>
</code>
***
## Description
In this problem we were given data of automobile dataset stored as data_set.data in the repository.We had to train two models using L1 regularization in one of them and compare both by choosing a loss funciton of our choice. <br />
***
## Steps to run the code:
The repository consists of following files:
* Project2.ipynb
* data_set.data
* clean_data.csv

Each file has its own role
### data_set.data
  It consists of data that will be used to train and test model.
### Project2.ipynb
  * Libraries required to run the code include Tensorflow,numpy,scikit,keras and matplotlib which are thoroughly used all over the code.
  * This is the main code of the project and it performs cleaning,pre-processing and designing of both models in one go.
  * The only care need to be taken is to updata path variable for data_set.data depending on your PC.
  * This code when run will also generate a clean_data.csv file which stores cleaned and pre-processed data in the same directory where the code will be kept just for reference.
  * At last this code also predicts a data point given to us during submission to test our model's prediction capabilities. 

**NOTE:Change path variable according to your files in order for the code to work properly.**
