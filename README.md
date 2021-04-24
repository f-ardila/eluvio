# Eluvio data challenge
## Problem
Can we predict the number of upvotes a reddit post in the `r/worldnews` subreddit will have, given limited additional data for a post?

## Notebooks
- [Data_Exploration.ipynb](Data_Exploration.ipynb): Exploratory data analysis. Determining which columns might be informative and what problem to attempt to solve.
- [Word_Embeddings_in_Title.ipynb](Word_Embeddings_in_Title.ipynb): Feature engineering for titles using vector embeddings for each word.
- [Create_feature_set.ipynb](Create_feature_set.ipynb): Combine all features to create a clean data set on which to train and test models.
- [Predict_upvotes.ipynb](Predict_upvotes.ipynb): Develop and test models to predict the number of upvotes for a post given other features.
