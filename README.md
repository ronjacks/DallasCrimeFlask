# DallasCrimeFlask

Project Overview. 

The purpose of this project is to analyze Dallas Crime Data. The main analysis will be where, what time, what type of location, and what time of year does majority of the crime occur in Dallas. The findings of my analysis was then reported on a website hosted by Heroku. I am from and currently live in Dallas and have a vested interest in the analysis.  

Website Here:

https://dallascrimeflask.herokuapp.com/


Project Components
Dallas Crime Analyis contains three parts:

1. Gather / Analysize Data - Did this within Jupyter Notebook File. Data Engineering is done in the notebook file. 
2. Flask /  App Creation - This is where the data in the previous parts is organized into the framework of the website that we want to build with Flask. The HTML coding was also done in this step.  
3. Heroku / GIT / Deploy - In this step an Heroku account was created. Heroku is hosts the app on its servers. The final parts of the app was pushed into GitHub. Heroku deploys the app directly from GitHub.

I used Jupyter Notebook to edit the data file and create the vizualizations. 

Here is a list of the Python packages used:
pandas,
numpy,
re,
folium,
IPython.display,
FileLink, FileLinks,
seaborn,
matplotlib,
matplotlib.colors,
matplotlib.pyplot,
holoviews,
hvplot.pandas,
hv.extension ('bokeh' , 'matplotlib'), 
sklearn.model_selection ,
train_test_split,
StandardScaler,
accuracy_score,
KMeans,
classification_report, confusion_matrix,
itertools,
XGBClassifier,
Flask 

Data Engineering Process:
The data was downloaded from dallasopendata.com. I then explored the data. I then reduced the dataframe to only to columns we cared about. After the data is consolidated I did some data engineering to the columns to create a column that consolidates the type crime that had occured, where the crime had occured, time etc. Extra columns were added to rank the crime that happened. This synthesized dataframe was used for the advanced analytics and machine learning which helped gain deeper insights. I finally visualized where the crime is happened on maps. A heat map and interactive maps was to used to bring the analysis to life.

The initial file is too big to upload to this repository but can be downloaded here:

https://www.dallasopendata.com/Public-Safety/Police-Incident-location-and-pertinent-information/v3r6-776m

You will need to export it as a CSV. 

Files Used:
The Templates folder contains the html templates for the some the visualizations and template for the website. 

The Dallas Crime Analysis v5.ipynb file is the Jupyter file I used to run analysis and create visualizations. 

The Procfile is a file that Heroku needs to run the app. Heroku apps include a Procfile that specifies the commands that are executed by the app on startup. You can use a Procfile to declare a variety of process types, including:

The app.py is the file that configures the website/ app. This file is created to help the user include any application configuration for the app. Using this, you can configure some of the attributes of the application.

The requirements.txt file is just a list of pip install arguments placed in a file. Note that you should not rely on the items in the file being installed by pip in any particular order.


Instructions:
The Dallas Crime Anaysis website can be found here: https://dallascrimeflask.herokuapp.com/

Results of Analysis:
The most crimes happen at 12am, on the street, in the southeast part of Dallas, and in July. Something that could make this analysis more impactful would be adding more columns. Columns such as the police badge number were dropped from the final dataframe that was used for the analysis. This would be something that could hold police accountable while patroling the communities. It also it could give public an idea on what cops are actually dealing with, which can bring some clarity and understanding.

Improvements:
Some additional things can be done to make the analysis more insightful. For instance there could be a deeper level of granularity. The Types of crime and location of the crime columns have a lot of records bucketed into 'Other'. These columns could be explored further with some data engineering to improve the analysis. I could also add more compononents with the interactive maps that explore lower level crime. 

