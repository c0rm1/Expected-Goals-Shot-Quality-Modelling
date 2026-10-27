# Expected-Goals-Shot-Quality-Modelling
Goal: Predict the probability that an individual shot results in a goal.

Build plan
1. Extract shot events and calculate distance and angle to goal.
2. Train logistic regression as a baseline.
3. Compare decision trees, random forests, SVM, and gradient boosting.
4. Introduce features such as shot type, assist type, body part, and defensive pressure where available.
5. Calibrate predicted probabilities.
6. Build an interactive pitch shot map with xG values.
7. Compare player goals with expected goals across a season.
Suggested stack: Python, scikit-learn, XGBoost, mplsoccer, Streamlit.

Module practice: Classification, regression, gradient descent, ensembles, model evaluation.

Evaluation: Log loss, Brier score, calibration curves, and ROC-AUC.

Extension: Build a post-shot xG model using goalkeeper and shot-placement data, where suitable tracking or shot data is available.

Data: StatsBomb Open Data. Note that advanced contextual features may not exist for every shot.
