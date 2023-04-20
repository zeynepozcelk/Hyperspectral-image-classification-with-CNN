# Hyperspectral-satellite-image-classification-Using-Deep-CNNs
This is a Python project for hyperspectral image classification using machine learning techniques. The project aims to classify hyperspectral images into different land cover classes.

## Requirements
The project requires the following Python packages:
- numpy
- pandas
- scikit-learn
- spectral
You can install them using pip:

    pip install numpy pandas scikit-learn spectral
## Dataset
The Indian Pines dataset is used for this project, which can be downloaded from the following link:

- http://www.ehu.eus/ccwintco/uploads/6/67/Indian_pines_corrected.mat
- http://www.ehu.eus/ccwintco/uploads/c/c4/Indian_pines_gt.mat
The Indian Pines dataset contains a hyperspectral image of size 145 x 145 x 224, representing 224 spectral bands, and a ground truth map of size 145 x 145, representing the land cover classes for each pixel.

## Usage
The project consists of the following files:

- main.py: The main script for running the classification algorithms.
- utils.py: Utility functions for loading and preprocessing the data.
- classifiers.py: Different classification algorithms, including SVM, Random Forest, KNN, and MLP.
- evaluate.py: Functions for evaluating the classification results.
To run the project, execute the main.py script. You can choose the classification algorithm and the parameters to use in the script.

    python main.py --classifier svm --C 1 --kernel rbf --gamma 0.1
    
This will run the SVM algorithm with C=1, RBF kernel, and gamma=0.1. The script will print the classification report and confusion matrix for the results.
## Results
The project achieves an overall accuracy of 85% using SVM with RBF kernel, C=1, and gamma=0.1.

## Credits
This project is created by Zeynep Ozcelik. The Indian Pines dataset is provided by the University of Basque Country. The code is adapted from the "Remote Sensing Image Classification with Python" tutorial by Hamed Habibi on Towards Data Science.
    
  
