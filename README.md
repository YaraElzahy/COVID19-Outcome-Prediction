# COVID-19 Outcome Prediction 🦠

COVID-19 Outcome Prediction: Discover if you'll recover or not! Dive into symptom-based insights and compare ML models. Will SVM outshine the rest? 

## What's This Project About?

Ever wondered if someone's chances of recovering from COVID-19 could be predicted? Well, you're in for a treat! We're analyzing data based on predefined symptoms to determine whether a person will recover or not. Using a set of standard symptoms, we've collected data that could hold the key to understanding who recovers (labeled as 0) and who doesn't (labeled as 1). 

## Let's Dive Deeper

- **Data Exploration**: We've got 13 interesting features, including age, gender, and more. Our data has already been cleaned and preprocessed, but there's a twist – it's imbalanced, which makes things all the more challenging.

- **Problem Statement**: We've even identified the crucial features with high correlations – age, visit to Wuhan, origin from Wuhan, and several symptoms. 

## Project Pipeline

We've built a robust pipeline:

1. **Data Preparation**: Loading, splitting, labeling, normalizing - we've got it all covered.
2. **Hyperparameter Tuning**: GridCVSearch helps us find the best parameter values.
3. **Model Building**: We use Decision Trees, K-Nearest Neighbors, Logistic Regression, Naïve Bayes, and Support Vector Machines to make predictions.
4. **Model Evaluation**: We're not stopping at just one model; we're comparing them and using Principal Component Analysis and the Silhouette Coefficient to evaluate their performance.

## Why Grid Search Cross Validation?

Grid Search Cross Validation helps us find the best parameter values, making our models even more accurate. It's like finding the perfect combination to unlock the mystery of recovery prediction!

## The Clash of the Classifiers

We've pitted Decision Trees, K-Nearest Neighbors, Logistic Regression, Naïve Bayes, and Support Vector Machines against each other. Who will emerge as the champion in predicting COVID-19 outcomes?

## Conclusion

SVM stands tall as the victor in this epic battle of classifiers, outperforming all others. 

Are you ready to uncover the secrets hidden in the data? Dive in and explore this fascinating world of COVID-19 outcome prediction! 😷🧪📊

---

*Note: This project was carried out as part of an academic endeavor and should not be considered for real-world medical decision-making.*

[![Yara's GitHub](https://img.shields.io/badge/More%20Projects-Check%20out%20my%20GitHub-blue)](https://github.com/YaraElzahy)

*Distributed under the MIT License.*
