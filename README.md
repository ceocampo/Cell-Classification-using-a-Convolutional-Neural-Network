# Cell-Classification-using-a-Convolutional-Neural-Network
A model using a convolutional neural network was created to predict whether or not a cell is infected with malaria. Images of malaria-infected cells and healthy uninfected cells were used to train the model.  

# Project Overview
- The dataset includes images of cells infected with malaria and uninfected healthy cells.
- The goal of this project is to use these images to create a predictive model using a convolutional neural network that can predict whether or not a cell is infected with malaria.
- We begin by sampling some infected and uninfected cells to visually inspect any noticeable differences between the two classes of cells.
- Data augmentation was performed to increase the number of samples we have before feeding them into our model for training.
- The model was then applied to a randomly selected uninfected and infected cell image.

The project is located in the .ipynb notebook file and the library requirements/versions used for this project are located in the requirements.txt file. The model is also attached as Cell_Classification_Model.h5.

This dataset was taken from the NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/
