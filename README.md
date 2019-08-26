# Indian-License-plate-detection
This project was selected out of the five problem statements in round 2 of TCS-HumAIn


The project is developed using TensorFlow to detect an Indian License Plate from a car and to recognize the charactes from the detected plate.

Approach:

1)Detect License Plate using CCA (Connected Component Analysis) 
2)Perform segmentation of characters (applying CCA on the plate) 
3)Train a CNN model using images of characters (numbers and alphabets) 
4)Prediction of characters in License Plate

Run main.py

Tech-stack:

Python 3.7, tensorflow, keras, open-cv

Software packages:

Anaconda 3 (Tool comes with most of the required python packages along with python3 & spyder IDE)
