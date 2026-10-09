# Machine Learning Classifiers

A comparative study of multiple classification algorithms on a chessboard-like dataset, plus an analysis of the curse/blessing of dimensionality.

## Overview
Built as part of Columbia University's Artificial Intelligence course (COMS 4701). Implements, tunes, and compares five classifiers using scikit-learn, with decision boundary visualization and a research analysis of high-dimensional spaces.

## Tech Stack
- **Language:** Python
- **Libraries:** scikit-learn, NumPy, Pandas, Matplotlib

## Classifiers Implemented
1. **k-Nearest Neighbors** — tuned n_neighbors (1-19) and leaf_size (5-30)
2. **Logistic Regression** — tuned C (0.1-100)
3. **Decision Trees** — tuned max_depth (1-50) and min_samples_split (2-10)
4. **Random Forest** — tuned max_depth (1-5) and min_samples_split (2-10)
5. **AdaBoost** — tuned n_estimators (10-70)

## Methodology
- **60/40 train-test split**
- **5-fold cross-validation** for hyperparameter tuning
- **GridSearchCV** for systematic parameter search
- **Decision boundary visualization** for each classifier

## Additional Analysis
- **Curse of dimensionality experiment:** computed DMAX/DMIN ratio as dimensionality increases from 1 to 100
- **Research component:** literature review on whether high dimensionality is a blessing, with citations

## Results
- Recorded training and test accuracy for all classifiers
- Compared decision boundaries visually
- Analyzed which method performs best and why

## What I Learned
- Practical ML workflow with scikit-learn
- Hyperparameter tuning with cross-validation
- Tradeoffs between classifier families
- The curse vs. blessing of dimensionality

## Note
This project was completed for a course. Source code is available upon request due to course policy restrictions. I'm happy to discuss the methodology and results in an interview.
