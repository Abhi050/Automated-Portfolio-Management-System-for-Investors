# Automated-Portfolio-Management-System-for-Investors

In this project I tried to create a portfolio management system that can predict the risk tolerance of the portfolio of an investor and the I deployed that model using an interactive dashboard created using Dash library in Python.

This project is divided into 2 parts:
1. Modelling
2. Dashboard

In Modeling, I worked on S&P500 data(dataset is included). I performed task like data cleaning, feature selection, etc. Feel free to try your own methods to get better results. This was followed by modelling where I first tried bunc of ML algorithmns like:
1. Linear Regression
2. Parametrize Regression
3. KMeans
4. SVM
5. Adaboost
6. GBoost
7. Random Forest
8. Extra Trees Regressor

Out of all, Random Forest was working best in my case. I tested this using KFold cross validation and later performed hyperparameter tuning using GridSearchCV


In Dashboard part, I created a generic dashboard using dash library. I used the saved model from first part and used it to make real time prediction on the dashboard.



To firt run th the project, one has to follow the following steps:
1. Run the Model.ipynb file
    Follow all the instruction mention in the jupyter file, feel free to experiment with the model selection on your own

2. Save the model.
    At the end of first step, you will have a .sav file. Thats your model with all the parameters and hyperparameters you used during training. Download that file locally.
    
3. Run the Dashboard.ipynb file
    This file contains the code for dashboard creation. Make sure to use .sv file from step 2 here.


This is my first project where I have deployed my model. I am still learning and will try to make this project even better. In case of any queries feel free to contact me:

Linkdin: https://www.linkedin.com/in/abhi050

Github Repo: https://github.com/Abhi050/Automated-Portfolio-Management-System-for-Investors

Email:   abhi.pradhan389@gmail.com
