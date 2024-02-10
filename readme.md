In this repository I am pushing my code where I am analyzing my YouTube data and finding out Top 50 songs that I have in one of my playlist. Based on the type of songs that I have in the playlist I will recommend some songs that align my taste.
I am also using Apache Airflow to create the pipeline as I will continuously going to add new recommended songs in my playlist
In future I will create website where I will upload Top 50 songs on Heroku

Project Steps:
1- Using YouTube API to pull the necessary data and doing some Exploratory Analysis on it
2- Getting top 50 songs in my playlist based on total number of views, total number of likes on the video and total number of comments on the video.
I am first normalizing the data using MinMaxScaler and after normalizing the data I am giving 50% weightage to views, 30% weightage to likes and 20% weightage to comments and getting a rating to get the Top 50 songs
3- Will create data pipeline using Apache Airflow(Trying to learn Airflow) and upload the list on S3