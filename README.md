# Choosing cyclists for my fantasy team

Using machine learning to predict the top performers at the Tour de France.

## Table of Contents
* [Introduction](#Introduction)
* [Technologies](#Technologies)
* [Data](#Data)

## Introduction

Every year, I compete in a cycling fantasy league for the legendary Tour de France. Last year, I have learned Machine Learning and I think the best learning experience comes from making a project. Therefore, I embarked on this fun project to test what I have learned and to develop me further. 

Steps taken in this project:
* Web scraping to acquire the data
* Filling missing data with image classification using a ResNet artificial neural network
* Engineering features
* Training and using a machine learning model

## Technologies

* [BeautifulSoup](https://pypi.org/project/beautifulsoup4/), which is used for acquiring data via web-scraping (version 4.7.1).
* [Pytorch](https://pytorch.org/), which is used for image classification with a ResNet artificual neural network (version 1.6.0+cu101).
* [Numpy](https://numpy.org/), which is used for its arrays (version 1.18.5).
* [Pandas](https://pandas.pydata.org/), which is used to load the data and adjust the data (versions: Google Colab --> 1.0.5, My Linux System --> 0.24.2).
* [PILLOW](https://pillow.readthedocs.io/en/stable/), which is used to work with and alter images. (version 7.0.0).
* [Matplotlib](https://matplotlib.org/), which is used to visualize and analyse the data. (version 3.2.2)

## Data
The images with the accompanied information can be found on Kaggle via [this link](www.kaggle.com/dataset/a72a6c40e1c0949a248414af11a01214258d8e6229362ca1710be9b87df2c17c).

The created features for each year of results are found in the features folder.
