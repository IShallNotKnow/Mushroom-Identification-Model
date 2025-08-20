## Overview
This project applies machine learning to the UCI Agaricus–Lepiota Mushroom Dataset to predict whether a mushroom is poisonous or edible based on its physical characteristics. It demonstrates:
 - Feature engineering (target encoding, interaction features)
 - Modeling with Decision Trees and Random Forests
 - Hyperparameter tuning using Grid Search
 - Evaluation with accuracy scores and feature importances
 - The goal is to provide a clear, reproducible workflow for handling categorical datasets in classification problems.

This project uses the UCI Mushroom Dataset to predict whether a mushroom is poisonous or edible based on its physical characteristics. It demonstrates how to apply feature engineering techniques like target encoding and interaction features, and how to train and evaluate a Decision Tree & Random Forest classifier for categorical data. The goal is to provide a clear, reproducible example of how to preprocess categorical datasets, apply supervised machine learning, and interpret model results through feature importance analysis.

## Usage

Requirements

 - Python 3.8+
 - Core packages: pandas, numpy, scikit-learn, matplotlib, seaborn

## Installation

```powershell
pip install pandas numpy scikit-learn matplotlib seaborn
```

Results

Feature importance plot (Random Forest):

![Feature Importances](https://github.com/IShallNotKnow/Mushroom-Identification-Model/blob/main/feature_importances.png)

 - Random Forest achieved 100% accuracy on the test set.
 - Feature importance analysis showed odor was among the top predictors.
 - Target encoding and interaction features improved model stability compared to raw categorical encodings.

## Notes and next steps

 - Test models with missing values included to evaluate robustness.
 - Try additional encoding methods (e.g., cross-validated target encoding).
 - Explore model interpretability with SHAP or LIME.

## Contact

- Dataset source: UCI Machine Learning Repository — Agaricus/Lepiota (Mushroom)

## License

- This codebase is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license
