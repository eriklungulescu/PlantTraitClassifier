# PlantTraitClassifier

Initial Setup:
1. Make the directories `feature_data` and `submission`
2. Download and unzip the `cs-480-2024-spring.zip`.

To run this project:

1. Then run `feature_extraction.ipynb`, this will extract the Train and Test image features.
2. Then run `xgboost.ipynb`. You may comment out the Optuna hyperparameter optimization section, there is already a hardcoded "good" parameter choice.