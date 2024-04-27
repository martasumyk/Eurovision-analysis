# Eurovision analysis

## Aim

The aim of the project is to identify components of performance that influence its success at the Eurovision Song Contest.

## Data
Dataset containing all participants of Eurovision and their places in different stages from 2009 to 2023 was taken from Kaggle: https://www.kaggle.com/datasets/diamondsnake/eurovision-song-contest-data

After that, Spotify API was applied to gather song characteristics. You can find code for that in spotify_api.ipynb and resulting data set in dataset_with_spotify.csv

Explanatory data analysis you can find in explanatory_data_analysis.ipynb

After helding EDA, we cleaned our dataset for more comfortable using. You can find code in cleaning_dataset.ipynb. Resulting dataset is preprocessed_data.csv

## Methods 

Testing significance of countries, years, genders, styles using Likalihood Ration Test in testing_significance.ipynb

Selecting model using AIC in selecting_model.ipynb (written in R)
