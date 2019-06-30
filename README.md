# DallasCrimeFlask

Disaster-Response-Pipeline
Project Overview
The purpose of this project is to analyze disaster data set from Figure Eight to build a model for an API that classifies disaster messages. There is an web app included where an emergency worker can input a new message and get classification results in several categories.

Project Components
Distaster Response project contains three parts:

ETL Pipeline - Where is data is explored, wrangled, and cleansed
Machine Learning Pipeline - This is where data is run through machine learning algorithms that predict
Flask App
1. ETL Pipeline
ETL Pipeline Preparation.ipynb jupyter notebook shows the code and development of ETL pipeline. Process_data.py Python script loads the messages & categories datasets, and merges the clean data then store the data into a SQLite database.

2. Machine Line Pipeline
ML Pipeline Preparation.ipynb Jupyther notebook shows the code and develoment of Machine Learning Pipeline. Train_classifier.py script loads the data from a SQLite database. And it uses the data to train and tune a Machine Learning model using GridSearchCV. Finally the model will output as a .pkl file.

3. Flask App
The web app can receive an input of new message and returns classification results in several categories.

Instructions
Run the following commands in the project's root directory to set up your database and model.
To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run your web app. 'python run.py`

Go to http://0.0.0.0:3001/ I had to type in " http://localhost:3001"
