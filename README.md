# BITS_ML_Assignment
## Business Statement: 
Bubba Gump Shrimp Company starts selling Abalone Salads and Fried Abalone. They place daily orders to our Seafood Supply Co. for fresh Abalone. 
I want to sort and verify our Abalone harvest using ML algorithms. 

## Abalone Harvest Standard:
1. Harvest all male Abalone once the ring-size is more than 10
2. Infant and Female Abalone are not harvested usually(we keep them safe for the future of our business).
3. Only Female Abalone which are very big(ring-size>14) becomes so costly and profitable, we started selling those.

## Data Source:
https://archive.ics.uci.edu/ml/datasets/Abalone

## Problem:
Classify Abalone into 2 categories: Harvestabel(for sale) and non-harvestabel.

## Algorithms used:
1. Logistic Regression: Please check the file `logistic_regression.ipynb`. 
   Accuracy: 0.76
   
2. Decision Tree: Please check the file `dt.ipynb`.
   Accuracy: 0.91

## Verdict: 
As the supplier has to maintain very high standard of the product, we are going with Decision Tree(high accuracy of 0.91)
