# Spotify EDA Analysis

## INTRODUCTION
- #### Spotify is a Swedish audio streaming and media services provider founded in April 2006. It is the world's largest music streaming service provider and has over 381 million monthly active users, which also includes 172 million paid subscribers.

Here, We'll exploring and quantify data about music and drawing valuable insights.

Perform an exploratory data analysis (EDA) and data visualization project using data from Spotify using Python.

- Data analysis exploring the relationship between the audio features of a song and how positive or negative its lyrics are, involving sentiment analysis.

- Includes data collection script that scrapes audio feature data from the Spotify API, as well as lyrical data from the LyricWikiAPI

- Spotify Data Analysis makes use of secondary data from Spotify. Learners will use data to identify patterns and relationships between different characteristics. The activity will support learners in developing their ability to review and interpret a dataset. The activity starts by encouraging learners to think of questions that the dataset might answer and thus develop their “Problem” skills. Once the dataset has been analysed learners will have the opportunity to reorganise and restructure data to help them answer their questions.

## Importing Dataset
![Datasetforspotify](https://github.com/user-attachments/assets/76acc657-1e49-44c9-a832-0fdf2349f790)


- ### null  values
![remove](https://github.com/user-attachments/assets/8e4a3b5c-3c7b-49d2-8a25-70e06531d7b3)

- ### tranpose()
![traspose](https://github.com/user-attachments/assets/abbd9543-cb19-4ca2-9ed3-87fa362361df)

## FEATURES
- Data Cleaning: Handling missing values, duplicates, and other data quality- issues.

- Data Exploration: Visualizing trends, distributions, and relationships between different variables.

- Feature Engineering: Creating new features or modifying existing ones for deeper insights.

- Visualization: Using libraries like Matplotlib, Seaborn, or Plotly to create interactive and informative charts.

## USAGE
1) Clone the repository:

git clone https://github.com/Bharathi123208/Spotify_EDA.git

2) Navigate to the project directory:

cd Spotify_EDA

3) Open the Jupyter Notebook

jupyter notebook Spotify_EDA.ipynb

4) Run the respective cells for Analysis

# Snapshots of the Analytics
## Pearson
![Spotify_Pearson](https://github.com/user-attachments/assets/16f734bd-6940-400b-ba5e-e39a03e3535c)


## Loudness Vs Energy Correlation
![Loudness](https://github.com/user-attachments/assets/969b836d-3fdd-4dfa-88dd-47b01c173b46)



## Popularity Vs Acousticness
![Popularity](https://github.com/user-attachments/assets/5167eff9-425a-4e77-ae45-fce39d17d4a5)


## Duration of songs in different Genre
![genre](https://github.com/user-attachments/assets/9e7b0e5b-c4cc-494c-bf54-3bbfdc1e0c28)


## Top Genres by Popularity
![Top Genres by Popularity](https://github.com/user-attachments/assets/845373f2-b028-47c6-809e-d41e1debe466)

# CONCLUSION
### The Exploratory Data Analysis (EDA) on the Spotify dataset provided valuable insights into the trends and patterns in music streaming data. Through data cleaning, exploration, and visualization, we were able to:

- #### Identify key features that influence the popularity of songs.
- #### Explore the distribution of various audio features such as tempo, loudness, and energy.
- #### Uncover relationships between different attributes, such as the correlation between danceability and energy.
- #### Highlight the most common genres and their characteristics.
- #### This analysis serves as a foundational step for further machine learning models or more in-depth analysis. The findings can be used by music analysts, producers, and marketers to better understand listener preferences and tailor their strategies accordingly.
