# Cell-Classification-using-a-Convolutional-Neural-Network
A model using a convolutional neural network was created to predict whether or not a cell is infected with malaria. Images of malaria-infected cells and healthy uninfected cells were used to train the model.  

# Project Overview
- The dataset includes images of cells infected with malaria and uninfected healthy cells.
- The goal of this project is to use these images to create a predictive model using a convolutional neural network that can predict whether or not a cell is infected with malaria.
- We began by sampling some infected and uninfected cells to visually inspect any noticeable differences between the two classes of cells.
- Data augmentation was performed to increase the number of samples we have before feeding them into our model for training.
- The model was then applied to a randomly selected image of an uninfected and infected cell.

The project is located in the .ipynb notebook file and the library requirements/versions used for this project are located in the requirements.txt file. The model is also attached as Cell_Classification_Model.h5.

This dataset was taken from the NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/

<b>Images of malaria-infected cells:</b> 

<img width="800" alt="Iris Versicolor" src="https://www.researchgate.net/profile/Mahdy_Rahman_Chowdhury_Mahdy/publication/334669002/figure/fig2/AS:784395963228161@1564025979768/Samples-drawn-from-NIH-Malaria-dataset-which-are-malaria-infected-parasite-red-blood.jpg">

<b>Images of healthy uninfected cells:</b>

<img width="800" alt="Iris Versicolor" src="https://www.researchgate.net/profile/Mahdy_Rahman_Chowdhury_Mahdy/publication/334669002/figure/fig1/AS:784395963232262@1564025979734/Samples-drawn-from-NIH-Malaria-dataset-which-are-uninfected-red-blood-cells-It-is-seen.jpg">

