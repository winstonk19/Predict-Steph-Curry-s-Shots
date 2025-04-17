# Predict-Steph-Curry-s-Shots
I built a machine learning model to predict whether Steph Curry would make or miss a shot based on over a decade of his NBA field goal attempt data
from October 2009 through June 2019 (including playoffs). The data was sourced using the nba_api Python library and included details like shot location, shot type, game context, and more.

🔍 Project Goals
The challenge was designed to demonstrate my skills in:

Data preprocessing and feature engineering

Model selection and evaluation

Interpreting model performance metrics

Visualizing results

🧠 Model Overview
I used a pipeline with a ColumnTransformer and a tree-based model (Random Forest Classifier) to process the features and make predictions. I evaluated model performance using accuracy, precision, and recall, and visualized the results using a confusion matrix.

✅ Completed Tasks
Task 1–4: Data import, cleaning, feature engineering, and dataset splitting

Task 5: Established a baseline model for comparison

Task 6–7: Trained a model pipeline and measured training/validation accuracy

Task 8 (Stretch): Tuned hyperparameters to improve performance

Task 9: Calculated precision and recall from a confusion matrix

Task 10 (Stretch): Plotted a confusion matrix to analyze prediction errors

📊 Key Results
The model gave solid predictive performance, revealing patterns in Curry's shooting behavior based on court position and game context. The confusion matrix helped me analyze where the model struggled (e.g., predicting made shots that were actually missed).

🛠 Tech Stack
pandas, numpy, matplotlib

sklearn for modeling and evaluation

category_encoders for handling categorical variables
