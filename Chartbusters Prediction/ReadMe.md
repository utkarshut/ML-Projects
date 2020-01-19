
## chartbusters-prediction-foretell-the-popularity-of-songs

In this hackathon Project done by https://www.machinehack.com/course/chartbusters-prediction-foretell-the-popularity-of-songs/. we have to create prediction algorithm that can predict the views for a given song.

### Getting Started

In this project, we will analyze a dataset that describes popularity of songs. One of the objectives of this project is to help our customer understand user behaviour and personalize the user experience. 

The dataset can be found in the same directory. The dataset includes features such as

- **Unique_ID** : Unique Identifier.
- **Name** : Name of the Artist.
- **Genre** : Genre of the Song.
- **Country** : Origin Country of Artist.
- **Song_Name** : Name of the Song.
- **Timestamp** : Release Date and Time.
- **Views** : Number of times the song was played/viewed (*Target/Dependent Variable*).
- **Comments** : Count of comments for the song.
- **Likes** : Count of Likes.
- **Popularity** : Popularity score for the artist.
- **Followers** : Number of Followers.

### Steps Involved:

Data Cleaning and Wrangling: Dealing with missing and invalid values.
Data Exploration: Data distribution visualizations using correlation and regression plots.
Feature Engineering:Created new derived feature using date old 
Model Training: Train model on linear ,lasso , Random Forest , XgBoost model.
Evaluation: Comparing RMSE for different models

**Model RMSE**
<img src="../data/evaluation.png" alt="Final Output"/>

**Important Features**
<img src="..data/feature_importance.png" alt="Final Output"/>

Conclusion:
As per competition we are getting highest score with XGBosst Regressor for unseen data.

In case of feature importance to **help Customerst to understand user behaviour and personalize the user experience** we will select random forest.

As per Random forest important features are **Likes ,Comments	,Popularity	,like_per_date	,Popularity_per_date**	
