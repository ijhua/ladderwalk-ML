# Machine Learning Project

This repo was created for a final project of BIOF 509. The goal of the project was to train supervised learning algorithms to predict horizontal ladder walk scores from tracking data from DeepLabCut. 

## Use

### Package Requirements

Make sure that Python 3 is installed. 

- pandas
- numpy
- glob
- os
- datetime
- sklearn
- dateutil
- joblib

## Required data
The code in this project assumes that the videos have already been processed and analyzed by DeepLabCut to track 16 features on the rat as well as all the rungs on the horizontal ladder. The dataset will remain private for the time being. 

## Running the Supervised Learning OOP Notebook

The main Jupyter Notebook is the Supervised Learning OOP.ipynb. It contains all the code needed to train support vector machines and random forests and to predict scores from the DeepLabCut output files. 

See notes and comments in the notebook for class and function-specific information. 