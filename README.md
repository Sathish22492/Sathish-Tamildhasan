# YOUTUBE-DATA-HARVESTING-AND-DATA-WAREHOUSING

## INTRODUCTION
* Develop a user-friendly Streamlit web app for seamless YouTube data harvesting and exploration.  
* Integrate YouTube Data API seamlessly with Streamlit for real-time retrieval of video statistics, comments, and channel information.
* Utilize mySQL database to warehouse the harvested YouTube data, ensuring structured storage and easy querying capabilities.
* Enabling querying of the data using SQL and Visualize the data within the Streamlit.
  
## DOMAIN
* Social media
  
## SKILL-TAKEAWAY
* Python scripting,Data Collection,API integration,Data Management using SQL,Streamlit
  
## TECHNOLOGY USED
* Python 3.9.
* Youtube API
* MySQL 8.0
* Streamlit
* Plotly
  
## FEATURES OF APPLICATION
   * In the Streamlit application, users input the channel ID to trigger the retrieval of comprehensive details from the YouTube Data API.And by cliking 'submit' button the application presents an overview of the channel,videos,comments and playlist in dataframe format.
     
## Store data in database:
   * The collected YouTube data was transformed into pandas dataframes. Before that, a new database and tables were created using the MySQL connector. With the help of MySQL, the data was inserted into the respective tables. The database could be accessed and managed in the MySQL environment.
   * In the Streamlit application, users input the channel ID and by clicking 'migrate to sql" button the application automatically store the data in mysql.
     
## Analysis in SQL:
   *  By using details of channels stored in MySQL database, the results are derived using MySQL queries for 10 questions about the youtube channels. The results are displayed in streamlit application in form of tables.
     
## Data Visualization:
   *  By using details of channels stored in MySQL database, various statistical results about the channels are derived using MySQL queries and charts are created using plotly and displayed in streamlit page
     
## PACKAGES AND LIBRARIES
* googleapiclient.discovery
* pandas as pd
* mysql.connector
* streamlit as slt
* from streamlit_option_menu import option_menu
* plotly.express as px

