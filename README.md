# Challenge-13
Venture Funding w/ Deep Learning

## Overview
Premise of this activity is to use available data (applicants_data.csv) from 'Resource' folder in package to create neural network model to predict which whether or not applicants that are funded by the firm will be successful or not. Focus is to develop and implement a binary classifier neural network model to assess the data given.

## Technologies Used
The libraries and dependencies used in this program are listed in the first cell of the program which are: pandas, pathlib, tensorflow, tensorflow.keras.layers, tensorflow.keras.models, sklearn.model_selection, and sklearn.preprocessing. 

## Program Layout
This program is divided into the following parts:

**Part 1** - Prepare Data for use on neural network model:
            In this section, data is imported into a dataframe which will be optimized by eliminating unneccessary data columns. Also implemented StandardScaler()
            to prep data for neural network model. Data is separated into categorical variables and then encoder is applied to data. DataFrame using encoded data is 
            concatenated with original numerical data to create a new 'encoded' dataframe. 
            
**Part 2** - Compile and evaluate 
            Preprocessed data is compiled and implemented into a structured binary neural network using Sequential() function and neural layers are set up. Data is then 
            applied for 50 epochs. Accuracy and summary data is shown as well as a HD5F file is created and saved into 'Resources' folder.

**Part 3** - Optimizing neural network
            Similar to process in part 2, data is again compiled and implemented into neural network using Sequential() function. There are two alternative models
            created (nn.A1: 3 hidden layers implemented; nn.A2: only one hidden layer implemented with 100 epochs), the purpose of this section is to optimize the 
            neural model with the goal of increasing accuracy.



## Author
Juan Bohorquez