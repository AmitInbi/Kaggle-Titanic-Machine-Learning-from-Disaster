This project was done as part of the Kaggle - "Titanic - Machine Learning from Disaster" Competition (https://www.kaggle.com/competitions/titanic/).

This is a basic ML project implementing Linear Regression and Random Forest algorithms using sklearn library with python.
Total scores:
* Linear Regression - 
	* Test set score: 82.94 / 100.
	* Validation set score: 0.77 / 1.
* Random Forest:
	* Test set score: 91.58 / 100.
	* Validation set score: 0.71 / 1.

# Pre-processing:
preprocessing in this project includes: 
- Droping irrelevant columns.
- Extracting title values from names column and splitting titles to dummy binary coulmns.
- Checking correlation between each column and "Survived" label coulmn, and dropping irrelevant coulmns.
- filling missing 'Age' values based on the passangers sex & ticket class.

# Models:
In this project i've ran both LogisticRegression from the sklearn.linear_model library and RandomForest from the sklearn.ensemble.