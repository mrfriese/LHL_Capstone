# LHL_Capstone

# Project introduction

Leukemic cell identification (specifically Acute Lymphocytic Leukemia) project by image.

## workflow

Import appropriate picture data, and perform some EDA. Data is limited to pictures, so there is not really anything to do as far as 
data cleaning.
Transform images for processing - reduce image size and change color scheme for ease computation cost.
Create the first CNN model with pytorch and run through some small portion of data to evaluate if the model is working.
Train data and evaluate testing of dataset.
Investigate the progress of the model via graphs and metrics like accuracy.
Create MVP and presentation.
Clean code, create py files for storage and push project to github.


## Process notes

Initial model took some time to create. Pytorch was used for the project, and I had to become familiar with it
before I could begin. .bnp files were computationally expensive to process, and inital models contained errors
that significantly slowed down the process - even working with google colab.
Edit increased training speed around 30x faster.