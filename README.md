# 🫀 Health Insurance Premium Prediction — Summary

This project uses Machine Learning to predict health insurance charges/premiums based on factors such as:

Age
Gender
BMI
Number of children
Smoking status
Region

🔄 Project Process
Dataset → Data Cleaning → EDA → Encoding → Train/Test Split → Model Training → Evaluation → Prediction

🤖 Models Used

Three Linear Regression models are compared:

Model 1: Age only
Model 2: Age + BMI
Model 3: All available features

The models are evaluated using:

MSE (Mean Squared Error) — lower is better
R² Score — higher is better
🏆 Final Model

Model 3, which uses all available features, is selected as the final model because it provides better predictive performance and generalization compared with the simpler models.

🛠️ Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab / Jupyter Notebook

🔮 Final Output

The trained model can take information about a new individual and predict their expected health insurance charge.
