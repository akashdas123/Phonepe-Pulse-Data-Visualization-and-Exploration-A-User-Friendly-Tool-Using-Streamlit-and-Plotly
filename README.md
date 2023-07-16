# Phonepe-Pulse-Data-Visualization-and-Exploration-A-User-Friendly-Tool-Using-Streamlit-and-Plotly
Phonepe Pulse Data Visualization Clone ,Python.Pandas, Numpy , MySQL ,Streamlit ,Plotly ,Geo visualization 


The result of this project will be a live geo visualization dashboard that displays
information and insights from the Phonepe pulse Github repository in an interactive
and visually appealing manner. The dashboard will have at least 10 different
dropdown options for users to select different facts and figures to display. The data
will be stored in a MySQL database for efficient retrieval and the dashboard will be
dynamically updated to reflect the latest data.
Users will be able to access the dashboard from a web browser and easily navigate
the different visualizations and facts and figures displayed. The dashboard will
provide valuable insights and information about the data in the Phonepe pulse
Github repository, making it a valuable tool for data analysis and decision-making.
Overall, the result of this project will be a comprehensive and user-friendly solution
for extracting, transforming, and visualizing data from the Phonepe pulse Github
repository.


<b>Tools</b><p>
Python 3.11.0
MySQL
pycharm

<b>libraries </b><p?
pip install 
pandas 
numpy 
os 
json 
requests 
subprocess 
mysql.connector 
sqlalchemy 
pymysql 
streamlit 
plotly.expres

<b>clone libraries</b><p>

import requests
import subprocess
pandas, numpy and file handling libraries

import pandas as pd
import numpy as np
import os
import json
SQL libraries

import mysql.connector
import sqlalchemy
from sqlalchemy import create_engine
import pymysql
Dashboard libraries

import streamlit as st
import plotly.express as px


<b>E T L PROCESS</b><p>
a) Extract data
 Clone the data from the Phonepe GitHub repository by using Python libraries. https://github.com/PhonePe/pulse.git
b) Process and Transform the data
Process the clone data  and transform the processed data into DataFrame formate.
c) Load data
 create a Database and stored the Transformed data in the MySQL server by using the given method. df.to_sql('table_name', connection, if_exists = 'replace', index = False, dtype={'Col_name':sqlalchemy.types.datatype()})

<b>E D A process</b><p>
Create a connection to the MySQL server and access the specified MySQL DataBase by using pymysql library

Filter and process the collected data depending on the given requirements by using SQL queries

Finally, create a Dashboard by using Streamlit and applying selection and dropdown options on the Dashboard and show the output are Geo visualization, bar chart, and Dataframe Table

