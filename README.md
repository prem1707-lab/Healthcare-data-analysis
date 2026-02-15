# Healthcare-data-analysis
it consists of sample projects about data analytics and data science 
🏥 Healthcare Disease Prediction using Machine Learning
📌 Project Overview

This project applies machine learning techniques to predict affected diseases using structured healthcare data. The dataset includes patient demographics, consulting doctor details, and time-based features, allowing the model to learn disease patterns from historical records. A classification model was trained to identify relationships between patient attributes and diagnosed conditions. Proper preprocessing and categorical encoding were applied to ensure compatibility with ML algorithms. The system also demonstrates future predictions and visualizations to analyze predicted disease trends.

📊 Dataset Description

The dataset contains healthcare visit records with features such as:

Age – Patient age

Gender – Patient gender

Consulting Doctor – Doctor handling the case

Year / Month / DayOfWeek – Temporal visit data

Affected_Disease – Target variable (prediction label)

🎯 Objective

✔ Predict affected diseases using patient and visit attributes
✔ Apply classification algorithms for healthcare analytics
✔ Demonstrate end-to-end ML workflow
✔ Visualize prediction patterns

🧠 Machine Learning Approach

The project follows a standard ML pipeline:

Data cleaning & missing value handling

Feature selection

Categorical variable encoding

Train-test split

Model training using Random Forest Classifier

Performance evaluation

🤖 Model Used

Random Forest Classifier

Reasons for selection:

✔ Handles non-linear patterns
✔ Robust to noise
✔ Works well with mixed feature types
✔ Suitable for multi-class classification

📈 Evaluation Metrics

Model performance was evaluated using:

Accuracy Score

Precision / Recall / F1-score

Classification Report

Confusion Matrix

🔮 Future Predictions

The system supports predictions for new patient records and visualizes:

✔ Most predicted diseases
✔ Prediction distribution
✔ Probability rankings

📊 Visualizations

Examples of analysis included:

Disease prediction frequency

Most predicted diseases bar plots

Performance comparison visuals

🛠️ Tech Stack

Python

Pandas – Data handling

Scikit-learn – Machine learning

Matplotlib – Visualization

NumPy – Numerical operations





🔥 Key Learning Outcomes

✔ Handling structured healthcare datasets
✔ Avoiding data leakage
✔ Categorical encoding techniques
✔ Classification modeling
✔ Model evaluation & visualization
