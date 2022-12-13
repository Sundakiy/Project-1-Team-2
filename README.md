# Project-1-Team-2

# Who’s up for a movie?

Team Members: Sunday Akiyesi, Benjamin Kidston, Kate (Xuan) Liu, Jane Enkhbaatar, Natasha Girdharry 

Data source: https://www.kaggle.com/datasets/anasmahmood000/netflix-movies-dataset

# Project Overview 
Who’s up for a good, old movie? During COVID-19 there was an increase in users for online streaming platforms including Netflix, Amazon Prime, and Crave. This  predominantly occurred because stores and entertainment outside of the household were closed and individuals were working from home on a full-time basis providing more time for entertainment. 

North America is home to one of the most influential film producing industries worldwide. Approximately 400 films were released during 2021 in the United States and Canada.  According to the New York Post, the average person has 16 movies on their Netflix watchlist, meaning they’d dedicate 104 hours to watching movies! However, how long is an average movie today? And have movie durations changed in the last 80 years? This project will extract data to analyze trends in movie duration by genres and audience recommended ratings (G, PG, 18, 14-A, NC-17). We will also assess whether there are differences in these movie duration trends between the early 1940s and 2022. 

# Research Purpose
Evaluate the length of average movie times based on genre and audience rating systems and assess whether there has been a change in movie lengths (general, by genre, by audience ratings)  between 1942 to 2022.  

# Research Questions
1. Have the average movie duration changed between 1942 to 2022? and what is the average length of a movie today? 

# Increased Library/Purchases of Movies from 2000s in Netflix
<img width="444" alt="Screen Shot 2022-12-12 at 10 40 30 AM" src="https://user-images.githubusercontent.com/115658965/207088234-d4877ad3-99c8-47b6-921c-593c107e3dfc.png">

# No Change in Average Duration between 1942-1952 and 2013-2022 
<img width="690" alt="Screen Shot 2022-12-11 at 4 50 46 PM" src="https://user-images.githubusercontent.com/115658965/207088412-9933f298-e45f-4a2c-aae1-7f05dbbbf347.png">

# Average Movie Duration
<img width="660" alt="Screen Shot 2022-12-11 at 4 49 39 PM" src="https://user-images.githubusercontent.com/115658965/207088540-8eba255b-7a2c-4aa8-9da6-e51a6d63dc33.png">

Therefore, the average movie duration is 99 +/- 29.5 minutes. The longest movie included in this dataset was 312 and the shorted was 3 minutes.

2. Is there a difference in movie duration by genre and have movie durations by genre, changed between 1942 to 2022? 

# Movie Genre Distribution 
<img width="394" alt="Screen Shot 2022-12-12 at 10 44 41 AM" src="https://user-images.githubusercontent.com/115658965/207089288-3f394a0d-d5e1-4b13-8ac5-9095ece925db.png">

<img width="391" alt="Screen Shot 2022-12-12 at 10 43 52 AM" src="https://user-images.githubusercontent.com/115658965/207089317-095d7776-a9c8-4f19-b8a7-965089dc6d7a.png">

The most popular genres in our dataset were Drama and Comedy, and the least common were Sci-Fi and Crime movies. Top 6 genre took 93% of total dataset. 

# Average Duration of Movie Varies with Genre
<img width="418" alt="Screen Shot 2022-12-12 at 10 44 47 AM" src="https://user-images.githubusercontent.com/115658965/207089586-e99d2546-4bc1-4ede-addb-9c8d62fa06de.png">

We identified a statistically significant difference between the longest genre (crime) in movie durations and the shortest (Family) suggesting that the average duration of a movie may vary depending on the genre. The ANOVA test (one-way) gave us 19.7 as result to proof of our hypothesis.

# Trends in Movie Duration Vary Across Our top 6 Genres Over time

<img width="722" alt="Screen Shot 2022-12-12 at 10 48 13 AM" src="https://user-images.githubusercontent.com/115658965/207090190-6046e055-bb6e-44a3-a38f-b83af580f780.png">

We observe trends of a decrease in movie duration over the last 60 years in categories of Drama, Comedy, and Family. Similarly, we also see a decreasing trend in movie duration over the last 20 years in Documentaries. Action/Adevnture doesn't seem to have any identifiable trends - movie duration is constant. Laslty, we observe that Thriller/Horror movies experienced an intial decline in duration from the 1980s until 2010 and the average movie duration has been steadily increasing since then.  

3. Is there a difference in movie duration by audience rating and what is the distribution of ratings among our top 4 genres? 

# Average Movie Duration by Movie Ratings 
<img width="705" alt="Screen Shot 2022-12-12 at 10 54 15 AM" src="https://user-images.githubusercontent.com/115658965/207092964-4c31c5a7-8b98-41c4-be62-b9be867cfcef.png">

We observed that there were no signficant differences in movie duration with movie ratings. 

# Movie Ratings by top 4 Genres 

<img width="402" alt="Screen Shot 2022-12-12 at 10 54 26 AM" src="https://user-images.githubusercontent.com/115658965/207093239-4085cc72-6284-4606-992d-966a33d9c92b.png">

We observe that the majority of our data is 18+ for the top 4 genres.

# Conclusions 

Movie production rapidly increased between 1942 to 2022 specifically in early 2000s.
Most movies are 90 to 119 minutes long. 
Average movie duration is 99 minutes. 
The most popular genres from our dataset are Comedy and Drama. 
Our data suggests that movie duration varies based on genre and these trends change overtime. As well, there is no difference in movie duration by audience ratings. 

Fun Fact! It would take you 534,090 minutes to watch all of the movies included in our database (that’s a full year!). 

# Limitations & Challenges 

Sample Size = 5,392 (Research questions are answered by sample dataset)
Sample Profile (Netflix popular movies only)
Data Collection (Kaggle Data Science Company - dataset)
Analysis (Not movie experts, analysis are done only based on dataset)
Categories of movies are sorted by first given genre
Audience Ratings sorted by Canadian Metrics

# Requirements 
MatPlotLib and Pandas Python libraries in Jupyter notebook. 

# Credits 
Thank you to EdX and the University of Toronto's School of Continuing Studies for their support. All participants contributed equally to this project. 
