# Recommender Systems Challenge 2023

[![Open](https://img.shields.io/badge/Open-Kaggle-blue.svg)](https://www.kaggle.com/competitions/recommender-system-2023-challenge-polimi)

This repository contains the code for the _Recommender Systems_ challenge (_Politecnico di Milano_, 2023-2024), made on [Kaggle](https://www.kaggle.com/competitions/recommender-system-2023-challenge-polimi).

The application domain is book recommendation, and the goal of the competition is to discover which items a user will interact with.<br>
The datasets contains interactions of users with books: if the user attributed to the book a rating of at least 4, the interaction is present in the dataset with value 1. 

## Recommender

The final recommender used in the challenge is an hybrid of:
- **SLIM Elastic Net**
- **RP3beta**

obtained merging the two similarity matrices using a weighted sum.

All the models have been trained using both _Kaggle_ and _Colab_ notebooks.

## Evaluation

The evaluation metric used for the competition is _MAP@10_.
- Public leaderboard score: 0.14042 (18<sup>th</sup> / 63)
- Private leaderboard score: 0.13984 (20<sup>th</sup> / 63)

## Credits

The code in this repository was built upon the code from the [course repository](https://github.com/MaurizioFD/RecSys_Course_AT_PoliMi), which provides the implementation of recommenders and utility code.

## Team

[Simone Scevaroli](https://github.com/simonescevaroli) & [Elisa Composta](https://github.com/elisacomposta)
