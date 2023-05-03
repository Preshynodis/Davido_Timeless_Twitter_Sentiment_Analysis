# Davido's Timeless Album: Twitter Sentiment and Engagement Analysis
Timeless is the fourth studio album by singer Davido, which was released on the 31st March 2023. The album made a lot of buzz and trends across social media and streaming platforms during it's first moments of release. This project is aimed at uncovering insights on this album using Natural Language Processing (NLP) to know the user engagements on Twitter. 

The project is a python-based project, where by the scraped using hashtags #timeless and #timelessalbum. After the analysis on python, I used Microsoft Power BI to do further analysis and created a [dashboard](). The full project documentation can be found on [medium](https//:). 

# Process Methodology
- **Data Requirement Gathering**: For this stage, I generated the questions I needed to answer from my analysis. This in turn guided my insights during the later course of this project. 
- **Data Collection**: Using Snscrape python library, I scraped the data from the release date to 10th April.
- **Data Cleaning and Preprocessing** : This is a very important stage in this project as it involves cleaning text data using NLP and Pandas, to ensure data is safe and reliable for usage.
-  **Sentiment Analysis**: Using TextBlob library, the polarity of the tweets were extracted. Polarity ranges from -1 to 1, such that if polarity score is below 0 it **Negative**, else if 0 - it is **Neutral**, otherwise **Positive**. These scores show the overall sentiment conveyed by tweeter users regarding Timeless Album.
- **Exploratory Data Analysis/Visualization** : This stage comprised text mining and data wrangling to extract relevant data and information to generate meaningful insights. Visualizations were made to easier represent the findings, for better understanding.
- **Dashboard Making and Documentation**: Project documentation is an important aspect while building projects as a data analyst. Asides keeping accountability on oneself, it is also a possible means to show recruiters and fellows your skills. The data was pushed to Power BI for dashboard making and the project documented on Github and [medium](https//:). 

# Insights
**Sentiment Analysis** : The visual below shows distribution of Twitter-user sentiments on the album. So far, there have been good neutral and positive reactions for this duration of data collection used in this analysis. 

<img width="335" alt="Sentiments" src="https://user-images.githubusercontent.com/100964410/236053628-fa149fb5-1b40-4d5e-b158-f090b67776c1.png">

**Track Rankings** : The rankings of the tracks of Timeless album is shown below.  

<img width="524" alt="Tracks' ranking" src="https://user-images.githubusercontent.com/100964410/236053730-3905c807-b433-4954-bc58-c741b033a7df.png">

**Top Hashtags** : When this album was released, even days before, it was already trending not only on Twitter space but also other social media platforms. I extrated the popular hashtags whose visual is shown below;

<img width="331" alt="Top Hashtags" src="https://user-images.githubusercontent.com/100964410/236053808-e7833991-26c1-4e4a-a52b-1075cafb1a76.png">

# Conclusion
- Overall, the album has gotten 6.9% negrative reactions, compared to 93.1% which is distributed among positive and neutral reactions.
- Top 3 most mentioned track from the tweets are kante, feel and away. 

Generally, I would say this project was quite chanllenging as I needed to learn about NLP and Regex functions in order for me to have gotten relevant data to be used for the analysis. At the end of the day, it's all about the learning process and I'm grateful to myslef for that. 

Thank you for reading!
