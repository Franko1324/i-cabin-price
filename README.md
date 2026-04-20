# Smart Cabin Price Predictor

Building AI course project

## Summary

This project uses AI to predict cabin prices from features such as size, sauna size, distance to water, number of bathrooms, and distance to neighbors. It is meant to help estimate a fair cabin price quickly and simply.

## Background

Cabin prices can vary a lot depending on many different features. This makes buying and selling difficult, especially for people who do not have much experience with real estate.

The problem is common because people often:
* do not know the fair value of a cabin
* rely on guessing instead of data
* compare cabins that are not really similar

My motivation is that AI can make price estimation easier, faster, and more objective.

## How is it used?

A user enters the main cabin features into the system, such as:
* size in square meters
* sauna size
* distance to water
* number of bathrooms
* distance to neighbors

The AI model then predicts the cabin price.

The tool could be used by:
* buyers
* sellers
* real estate agents

## Data sources and AI methods

The project would use data such as:
* historical cabin sales data
* cabin feature data from real estate listings
* public housing datasets if available

Possible AI methods:
* linear regression
* k-nearest neighbors
* neural networks

Example:

```python
price = model.predict(features)
