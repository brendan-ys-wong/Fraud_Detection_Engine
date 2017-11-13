# Summary
Created a fraud detection engine for an e-commerce company that hosted events on it's platform that was able to detect instances of fraud in cross-validated data at a 92% recall, 97% accuracy, and 86% F1 score.


# Methodology

EDA: Analyzed over 50 features to build feature matrix of most correlated data features with instances of fraud, and cleaned data set to deal with missing and null values and to deal with categorical and non-numerical feature categories.

Model: Analyzed logistic regression, gaussian naive bayes, and weighted average guess as our baseline models which were sounded beat by our production gradient boosted classifier model.

# Results
Our model was able to detect instances of fraud in cross-validated data set at a 92% recall, 97% accuracy, and 86% F1 score. This was compared to our best performing baseline model, logistic regression which had a 62% recall, 96% accuracy, and 71% F1 score.
