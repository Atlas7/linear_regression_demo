# linear_regression_demo
This is the code for "How to Make a Prediction - Intro to Deep Learning #1' by Siraj Raval on YouTube

## Overview
This is the code for [this](https://youtu.be/vOppzHpvTiQ) video by Siraj Raval on Youtube. This is the 1st episode in my 'Intro to Deep Learning' series. The goal is to predict an animal's body weight given it's brain weight. The model we'll be using is called [Linear Regression](http://www.statisticssolutions.com/what-is-linear-regression/). The dataset we're using to train our model is a list of brain weight and body weight measurements from a bunch of animals. We'll fit our line to the data using the scikit learn machine learning library, then plot our graph using matplotlib.

## Dependencies

- python = 2.7
- matplotlib = 1.5.1
- numpy = 1.11.0
- pandas = 0.18.0
- scikit-learn = 0.17.1

## Installation and usage

### Install with Conda

Assuming you have Anaconda already installed on your machine. If not, download and install from the [Continuum Analytics website](https://www.continuum.io/downloads).

Issue these commands to create a new Conda environment and run the Python code from there.

```
conda create
source activate linear-regression-demo
python demo.py
```

A chart will pop up in the end.

### Install with PIP

This is the original PIP install method (assuming you have Python 2.7 pre-installed on your machine):

In terminal to install the necessary dependencies. Here is a link to [pip](https://pip.pypa.io/en/stable/installing/) if you don't already have it.

```
pip install -r requirements.txt
python demo.py
```

A chart will pop up in the end.

##Challenge

The challenge for this video is to use scikit-learn to create a line of best fit for the included 'challenge_dataset'. Then, make a prediction for an existing data point and see how close it matches up to the actual value. Print out the error you get. You can use scikit-learn's [documentation](http://scikit-learn.org/stable/documentation.html) for more help. These weekly challenges are not related to the Udacity nanodegree projects, those are additional.

*Bonus points if you perform linear regression on a dataset with 3 different variables*

##Credits

The credits for the original code go to [gcrowder](https://github.com/gcrowder). I've merely created a wrapper to get people started.

# Notes

If you'd like to run this in other Python version (2.x / 3.x), simply amend the followings in the `environment.yml` (conda method) or `requirements.txt` (direct pip method):
- replace python version with the one you like
- remove all the version numbers in the other modules (e.g. matplotlib, numpy, pandas, scikit-learn)
