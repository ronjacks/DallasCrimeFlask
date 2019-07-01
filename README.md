# DallasCrimeFlask

Project Overview
The purpose of this project is to analyze Dallas Crime Data. The main analysis will be where, what time, what type of location, and what time of year does majority of the crime occur in Dallas. The findings of my analysis was then reported on a website hosted by Heroku.

Website Here:

https://dallascrimeflask.herokuapp.com/


Project Components
Dallas Crime Analyis contains three parts:

1. Gather / Analysize Data - Did this within Jupyter Notebook File. Data Engineering is done in the notebook file. 
2. Flask /  App Creation - This is where the data in the previous parts is organized into the framework of the website that we want to build with Flask. The HTML coding was also done in this step.  
3. Heroku / GIT / Deploy - In this step an Heroku account was created. Heroku is hosts the app on its servers. The final parts of the app was pushed into GitHub. Heroku deploys the app directly from GitHub.

Data Engineering Process:
The data was downloaded from dallasopendata.com. I then explored the data. I then reduced the dataframe to only to columns we cared about. After the data is consolidated I did some data engineering to the columns to create a column that consolidates the type crime that had occured, where the crime had occured, time etc. Extra columns were added to rank the crime that happened. This synthesized dataframe was used for the advanced analytics and machine learning which helped gain deeper insights. I finally visualized where the crime is happened on maps. A heat map and interactive maps was to used to bring the analysis to life.

The initial file is too big to upload to this repository but can be downloaded here:

https://www.dallasopendata.com/Public-Safety/Police-Incident-location-and-pertinent-information/v3r6-776m

You will need to export it as a CSV. 


Instructions:
The Dallas Crime Anaysis website can be found here: https://dallascrimeflask.herokuapp.com/
