Retail Profit Prediction Using Machine Learning
Project Overview
This project explores the application of machine learning to predict retail transaction-level profit using the Sample Superstore dataset.
The objective is to understand how factors such as sales, discounts, product categories, quantities, and shipping characteristics relate to profitability.
A Random Forest Regressor is trained on historical retail transaction data to estimate profit and identify important predictive features.
Dataset
Dataset: Sample Superstore
The dataset contains 9,994 records and 21 original columns, including sales, profit, discounts, quantity, product categories, customer segments, and shipping information.
Target Variable: Profit
Technologies Used
	•	Python
	•	pandas and NumPy
	•	scikit-learn
	•	Matplotlib
	•	Jupyter Notebook
Methodology
	1	Loaded and explored the Sample Superstore dataset.
	2	Converted date columns and engineered additional features, including order-related date attributes and shipping duration.
	3	Removed identifier columns and encoded categorical variables.
	4	Split the dataset into training (80%) and testing (20%) sets.
	5	Trained a Random Forest Regressor using 200 estimators and a maximum depth of 10.
	6	Evaluated the model using R², MAE, and RMSE.
	7	Visualized actual versus predicted profits and analyzed feature importance.
Model Performance
Evaluation Metric
Result
R² Score
0.8752
Mean Absolute Error (MAE)
$14.23
Root Mean Squared Error (RMSE)
$38.71
The model explained approximately 87.52% of the variation in profit in the reported test evaluation.
Key Findings
	•	Sales and discount were among the most influential features in predicting profit.
	•	Quantity and product sub-category also contributed to predictions.
	•	The analysis highlighted the relationship between discounting and loss-making transactions.
	•	The model demonstrated how historical retail transactions can be used to study profitability patterns.
Limitations and Future Improvements
This project was developed as an academic machine learning exercise.
	•	The model uses actual shipping duration, which may not be available when predicting profit for a newly placed order.
	•	The random train-test split could be improved by considering order-level grouping or chronological validation.
	•	Additional models, such as Linear Regression and Gradient Boosting, could be compared against Random Forest.
	•	Hyperparameter tuning and cross-validation could be explored to evaluate generalization.
Project Files
	•	retail_profit.ipynb — Jupyter Notebook containing the ML implementation and visualizations.
	•	Retail_profit.pdf — Academic project report.
	•	sample_-_superstore.xls — Dataset used for the analysis (subject to redistribution permissions).
Contributors
	•	Rhythem Kalra
	•	Iknoor Kaur
	•	Ridhima Soni
Project Context
Developed as an academic mini-project to apply machine learning techniques to retail profitability analysis.
