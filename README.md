⸻

Breast Cancer Tumor Classifier

This program uses real medical data to predict whether a breast tumor is cancerous (malignant) or non-cancerous (benign) using a machine learning model called a Decision Tree.

⸻

Overview

This program:

	•	Loads a dataset containing measurements of breast tumors
	•	Trains a machine learning model to recognize patterns in the data
	•	Tests the model on new, unseen data
	•	Evaluates the model’s performance using:
	•	Accuracy score
	•	Confusion matrix (which shows where the model was right or wrong)
	•	Feature importance (which measurements influenced decisions the most)
	•	Visualizes the decision-making process with a chart of the decision tree

⸻

Dataset Information

The dataset is sourced from the UCI Machine Learning Repository. It includes:

	•	569 instances (tumor samples)
	•	30 numeric features such as radius, texture, area, and smoothness
	•	A diagnosis label:
	•	M = Malignant (cancerous)
	•	B = Benign (non-cancerous)

The program converts these labels into binary values:

	•	Malignant = 1
	•	Benign = 0

⸻

What the Model Predicts

The model uses the 30 features to predict whether a tumor is:

	•	Malignant (1) – Cancerous
	•	Benign (0) – Non-cancerous

⸻

Interpreting the Results

The output includes a confusion matrix that explains how many predictions were correct and how many were wrong. 

For example this is what a output may look like:

	Tumors that were ACTUALLY benign (non-cancerous):
	   71 were correctly predicted as benign
	   1 was wrongly predicted as malignant

	Tumors that were ACTUALLY malignant (cancerous):
	   2 were wrongly predicted as benign
	   40 were correctly predicted as malignant
   
⸻

Visual Output

You will see three main visualizations:

	1.	Decision Tree Chart – Shows the model’s logic in making predictions
	2.	Feature Importance Bar Graph – Highlights the most influential measurements
	3.	Confusion Matrix Heatmap – Displays prediction results in a color-coded table

 ⸻
 
