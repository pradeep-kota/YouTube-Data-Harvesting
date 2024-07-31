# YouTube-Data-Harvesting
The problem statement is to create a Stream-lit application that allows users to access and analyze data from multiple YouTube channels. 

This is a project given by Guvi Geek networks, IIT-Madras.

### Tools Used
1. pycharm
2. python>=3.11
3. MySQL, MongoDB
4. google account for youtube api keys
5. Find requirements.txt file in main branch for libraries used

### Steps followed
1. Install libraries using requirements.txt in a virtual env in IDE of your choice.
   #### a. We use googleapiclient.discovery to pull API data from google.
   #### b. pymongo to connect with mongoDB server.
   #### c. mysql.connector, sqlalchemy, create_engine, pymysql we use these modules to connect MySQL server and run scripts.
   #### d. re and pandas to manipulate data
   #### e. plotly and streamlit to visualize data in streamlit app
2. Get YouTube api keys by following instructions listed in the project description file  (You can create 10 projects per google account,
   and each project gives 10000 quota to pull requrired data.
   #### Channel, comments, playlist, video data is pulled for a channel data for example if a channel has 100 videos and 10 playlists, we pull all
   100 videos data, their comment data and playlist data.
4. streamlit is running on session state so that we retain session state data to perform sequential processing.
5. MongoDB and MySql in integrated using connector & pymysql, stored and retrieved data in analysis section.
6. You can follow me on linkedIn to see the video description on how to use the app to get data
https://www.linkedin.com/in/kota-pradeep/ 

###Video explaining the project is below



https://github.com/user-attachments/assets/1884517e-c19c-4145-8be4-334fc972f6bd



https://github.com/user-attachments/assets/12dd2cc8-0b5f-4780-8dfd-e7c1c0f4abda


