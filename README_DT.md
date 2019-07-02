# Decision Trees in Trading

In this course, you have learned how to code the Classification model, Regression model, Parallel Ensemble model and Sequential Ensemble model in Python. You have also learned to code Cross-validation technique and Hyper-parameter tuning in Python. All these codes are provided in this downloadables folder.

## This readme file has the following sections:
1. Prerequisites
2. Installing packages
3. Running the code
4. Folder structure
5. Authors

## Prerequisites:
Before running these notebooks, you need to setup a Python environment on your local machine. If already present, make sure the Python version is 3.6.8. To change the Python version, open the Anaconda prompt and type the following command: 

	conda install python=3.6.8

## Installing packages:
We have used the following Python libraries in the course. Kindly ensure you have these libraries installed with the same versions as mentioned below. To install the same version on your local system, type these commands on the IPython notebook.

	!pip install numpy==1.16.4
	!pip install pandas==0.23.4
	!pip install matplotlib==2.2.3
	!pip install scikit-learn==0.21.2
	!pip install talib==0.4.17 
	!pip install tabulate==0.8.2
	!pip install graphviz==0.10.1
  
## Running the code:
Once you have your system in place, you can run the notebooks using Jupyter interface. This is installed along with Anaconda.

## Folder structure:
This folder contains 6 subfolders divided based on the sections of the course. Each subfolder contains the IPython notebooks and the data required to run them in that particular section.

	1. Classification model:
		a. Classification Tree Model.ipynb
		b. Class Weights in Decision Trees.ipynb
		c. ACC.csv

	2. Regression Trees:
		a. Regression Tree.ipynb
		b. AAPL.csv

	3. Parallel Ensemble Methods:
		a. Bagging.ipynb
		b. Random subspace.ipynb
		c. Random forest.ipynb

	4. Sequential Ensemble Methods:
		a. AdaBoosting.ipynb
		b. Gradient Boosting.ipynb

	5. Cross Validation and Hyperparameter Tuning:
		a. Cross Validation.ipynb
		b. Hyperparameter Tuning.ipynb
		c. AAPL.csv 
		
	6. Challenges in Execution:
		a. Execution Model-DT.ipynb
		b. BAC.csv
		c. model_save.pkl
		d. example_deploy_model.py
		
	7. example_deploy_model.py:
		The code to deploy the model on Interactive Broker's TWS using IBridgepy. 
		Need to place this file within the Strategies folder of the IBridgepy Installation folder. 
		Place the pickle generated from trained model in IBridgepy Installation folder along with RUN_ME.py file. 			Update the bar frequency to every minute by using repBarFreq = 60 in the RUN_ME.py file. 

## Author:
Quantra by QuantInsti
