# future-hdb-resale-price

Future HDB Resale Prices Predictive Model Based on Historical Values

dataset - https://www.kaggle.com/datasets/teyang/singapore-hdb-flat-resale-prices-19902020

## Information Extraction

This Notebook at ./information_extraction.ipynb extracts information from the dataset by answering the following questions:
Questions:

1. What is the location, room type of the top 5 town of resale flats transaction?
   **Answer** : Sengkang, Jurong West, Woodlands, Tampines, Yishun
2. for resale flat with story range of 10-20 with number fo room >= 3, what is the location of the most affordable resale
3. What is the highest and lowest resale price in each town with number of room ranges between 10 and 15
4. what is the highest and lowest resale of every sales
5. what is the median resale price for story range of 3-4

## Predictive Model

Objective: Create a predictive model of the resale price so that property agents are able to estimate the price range.

Inputs - the different features
Output - a hdb resale price (continuous number)
Model - Regression
Loss function - BCE

### Preprocessing

1. find correlation between features
2. ensure balanced dataset

TODO

1. change everything to numerical
2. try one model ML
3. see how to preprocess more
4. try NN
