## Contents
- `house_price_model.ipynb`: full walkthrough of our final model with commentary (start here)
- `train.csv`, `test.csv`: competition data

## Approach
- Predicted the log of sale price and removed two extreme outliers
- Encoded ordinal and categorical features and added engineered features (total square footage, age, bathrooms, etc.)
- Compared Ridge, Lasso and Gradient Boosting with 5-fold cross-validation
- Final model: an average (blend) of the three, which had the lowest CV RMSE (about $19.7K)
- Clipped test features and predictions to the training range, which fixed a large error on our first Kaggle submission

Only scikit-learn estimators are used.

## Results
Kaggle public leaderboard RMSE: [add final score] (rank [N] of 28)

## How to run
Install numpy, pandas and scikit-learn, open `house_price_model.ipynb`, and run all cells. It writes `preds.csv`.

## Contributions
- Akhil: [what you did]
- Veer: [what Veer did]
- Julie: [what Julie did]