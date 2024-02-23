# Improvements
1. Use SMOTE for imbalanced labels
2. Examine "time" feature
   1. What it means
   2. Data leakage
3. Scale on training set inside cross validation loop, then apply scaling to validation set
   1. This prevents information from the validation set being leeked into the training data
4. 