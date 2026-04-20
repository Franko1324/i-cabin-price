# Smart Cabin Price Predictor

Final project for the Building AI course

## Summary

An AI system that predicts cabin prices based on features like size, location, and amenities. It helps users estimate fair prices quickly using machine learning models trained on data. Building AI course project

## Background

Buying or selling cabins can be difficult because prices depend on many factors. People often:
* overpay or underprice properties
* do not understand what affects the price
* rely on guesswork instead of data

This problem is very common in real estate markets. My motivation is to make pricing easier and more accurate using AI.

## How is it used?

Users enter cabin features such as:
* size (m²)
* distance to water
* number of bathrooms
* distance to neighbors

The system then predicts the price.

Users:
* buyers → to avoid overpaying
* sellers → to set realistic prices
* agents → as a support tool

## Data sources and AI methods

Data sources:
* historical cabin price data
* real estate datasets

AI methods:
* linear regression
* neural networks
* k-nearest neighbors

Example:

price = model.predict(features)


## Challenges

This project does not solve everything:
* predictions depend on data quality
* unusual cabins may be predicted incorrectly
* market prices change over time

Ethical considerations:
* bias in data
* fairness of predictions

## What next?

Future improvements:
* better datasets
* web or mobile app
* image recognition of cabins
* real-time market data

## Acknowledgments

* Inspired by real estate pricing problems
* Based on knowledge from the Elements of AI course
* Uses concepts from NumPy and scikit-learn
