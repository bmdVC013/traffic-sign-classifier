# Build a Traffic Sign Classifier
## Overview
*In this project, I used Python and TensorFlow to classify traffic signs.*

**Pipeline architecture:**
+ Load The Data
+ Dataset Summary & Exploration
+ Data Preprocessing
  + Shuffling
  + Grayscaling
  + Local Histogram Equalization
+ Normalization
+ Design a Model Architecture
  + LeNet-5
  + AlexNet
+ Model Training and Evaluation
+ Testing the Model Using the Test Set
+ Testing the Model on New Images

## Dependencies
This project requires Python 3.5 and the following Python libraries installed:
+ Jupyter
+ Numpy
+ Matplotlib
+ OpenCV
+ Scikit-learn, Scikit-image
+ Pandas
+ Tensorflow

## Dataset
Dataset used: [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). This dataset has more than 50,000 images of 43 classes.
You can download the dataset from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip).
We already have three .p files of 32x32 resized images:
+ `train.p`: The training set.
+ `test.p`: The testing set.
+ `valid.p`: The validation set.

## Preferences
[CarND-Traffic Sign Classifier Project](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project) - Udacity
