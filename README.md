# Stock-based Recommendation System

In this project, we created an end-to-end solution for 

First, I built a clothing image classification model using a ResNet-based model. The feature layer of this model can .... Then, using such features, the model can recommend similar stock index to the input stock using nearest neighbor search and also predict its price in short-term.

## Dataset
[DeepFashion](https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs) is a large-scale clothes database that is quite popular in the research community. It contains over 800,000 diverse fashion images ranging from well-posed shop images to unconstrained consumer photos. It is annotated with rich information of clothing items. It also contains over 300,000 cross-pose/cross-domain image pairs.

[Ticker Symbol](https://www.nasdaq.com/market-activity/stocks) is 
More specifically, I trained the stock price prediction in the [DeepFashion Attribute Prediction](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion/AttributePrediction.html) subset. It contains 289,222 number of clothes images, 50 number of clothing categories, and 1,000 number of clothing attributes. Each image is annotated by bounding box and clothing type.

![AttributePrediction](deep-fashion-attribute-prediction.jpg)

## Code
1. [preprocessing.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/preprocessing.py): This code is used to pre-process the dataset.
2. [hyper_parameters.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/hyper_parameters.py): This code is used to define all hyper-parameters regarding training.
3. [fashion_input.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/fashion_input.py): This code is used to pre-process the image further during training.

## Sample Results

1 - Romper Category

![Romper](Results/Romper-Examples.png)

2 - Jacket Category


