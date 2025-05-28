
# Waste Segregation CNN Project

# Overview
This project uses a Convolutional Neural Network (CNN) to classify waste into seven categories: Cardboard, Food Waste, Glass, Metal, Paper, Plastic, and Other. The goal is to improve recycling by sorting waste accurately. It’s implemented in a Jupyter notebook (CNN_Assg_Waste_Segregation_Starter.ipynb).
Dataset

Source: data.zip with images in seven folders (one per category).
Size: 7,625 images, resized to 128x128 pixels.
Note: Some classes (e.g., Plastic, Paper) have more images than others (e.g., Food Waste), causing imbalance.

# How to Run

Unzip data.zip to ./dataset/data.
Install libraries: numpy, pandas, matplotlib, seaborn, Pillow, tensorflow, scikit-learn (see notebook for versions).
Run CNN_Assg_Waste_Segregation_Starter.ipynb in Jupyter Notebook.
Ensure the dataset path is set to C:/Users/sande/Downloads/dataset/data (or adjust as needed).

# Key Results

Loaded 7,625 images successfully.
Augmented training data to 12,200 images using rotation, flipping, and zooming.
CNN achieved 36.20% validation accuracy and 1.6249 loss after 13 epochs with augmentation.
Class imbalance and limited model complexity likely limited accuracy.

# Requirements

Python 3.12
Jupyter Notebook
Libraries listed in the notebook (section 1).

