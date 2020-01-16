# Admission-Predictor-with-Linear-Regression

### This Project has been sucessfully deployed in Heroku Cloud Platform:

Check here: https://demo-app-saurabh4.herokuapp.com

## Problem Statement

We need to predict the chances of admission of a candidate based on GRE Score (out of 340), TOEFL Score (out of 120), rating of the University (out of 5), Strength of the SOP (out of 5), strength of the Letter Of Recommendation (out of 5), CGPA (out of 10) and the research experience (0 or 1). 

## Model Selection

After performing Exploratory Data analysis, it was idenfied that Linear Regression model will be more suitable in this case

## Content of this Repository

1. statis/css >> Styling for the webpage
1. templates >> Basic HTML pages (landing page, results page)
1. Admission_Prediction.csv >> Dataset
1. Linear_Regression.ipynb >> Exploratory Data Analysis and Model creation
1. Procfile >> Needed for Cloud deployment
1. app.py >> Actual Flask app
1. finalized_model.pickle >> File where the model is stored
1. requirements.txt >> contains all the necessary libraries (Needed for cloud deployment)

## Deployment Procedure (on Heroku Cloud Platform)
1. Download all the files from this repository and save it in a folder
1. Go to https://www.heroku.com and Sign up/Login
1. On the Heroku homepage, click on New button >> create app
1. Open Git Bash
1. cd "/Path of the project folder where all the files are stored locally"
1. git init
1. git add .
1. git commit -m "your comments"
1. git remote add origin https://git.heroku.com/demo.git (note: this url is available under settings tab of the heroku app)
1. git push origin master

#### ------------------------------------------------------THANK YOU---------------------------------------------------------
