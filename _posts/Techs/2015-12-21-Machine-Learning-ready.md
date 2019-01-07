---
layout: post
title:  "Machine Learning ready"
date:   2019-01-05
desc: "A Brief guide to show how to install Anaconda by Shashwat Hiregoudar"
keywords: "anaconda,python,python3,pydev,Machine Learning,Opencv,OpenCV"
categories: [Tech]
tags: [DeepLearning,Python,Machine Learning,Opencv]
icon-family: fa
icon: icon-python
author: "Shashwat Hiregoudar"
---
Welcome to the world of machine learning and computer vision

The basic programming language for basic machine learning is python so first let us install it
# Anaconda

## What it is
It is a custom python interpreter.

## Is it necessary for me to install??
A default version of python is already pre-installed in mac and linux os.

But its better to use anaconda because it contains all the required files and libraries pre installed

## How to install 
Simple Go to official anaconda website [here](https://www.anaconda.com/download/)
and type this commnad 

```bash Anaconda*.sh```

The install time is approx 5-6 mins (It depends on your processor). While installing it will also ask weather to install visual studio code its better if you install that also.

# Install the libraries

Yea now bwfore we start with installing the libraries it is better to create a virtual environment so that they do not form any problem when you want to use a different versio of the libraries.

THis following step is totally optional

## Create a virtual environment

```conda create -n ml```

By doing so it will create a virual environment

To install libraries in that environment, we need to first go to that environment how to do it?

```source activate ml```(for mac and linux) ```activate ml```(for windows)

## Install the libraries

First we need to download the libraries so make sure a stable internet connection is present.And dont worry about syntax for operating system The following instructions are common to all os

We will install the following libraries one by one
* numpy
* scipy
* pandas
* scikit-learn
* matplotlib
* opencv
* tensorflow
* keras

### Numpy
This library is mostly present before only but still no harm in doing so

```conda install -c conda-forge numpy ```

### Scipy
```conda install -c conda-forge scipy ```
### Pandas
```conda install -c conda-forge pandas```
### Scikit-learn
```conda install -c conda-forge scikit-learn ```
### Matplotlib
```conda install -c conda-forge matplotlib```
### Opencv
```pip install opencv-python```
### Tensorflow
```conda install -c conda-forge tensorflow ```
### Keras
```conda install -c conda-forge keras```

