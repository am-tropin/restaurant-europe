# Restaurant Europe

The project gives content-based recommendations of European restaurants using Jaccard metric from SciPy. Also aggregates the data for the Tableau Public dashboard.

Libraries: numpy, pandas, SciPy


## Table of contents
- [Datasets](#datasets)
- [Machine learning approach](#machine-learning-approach)
- [The Dashboard](#the-dashboard)


## Dataset

- The dataset of TripAdvisor's data is from [Kaggle](https://www.kaggle.com/datasets/stefanoleone992/tripadvisor-european-restaurants). 


## Machine learning approach

- The problem is building a **content-based recommender** by restaurant features. The given problem was solved by using **the SciPy's Jaccord metric** in the [restaurant_recommender.ipynb](https://github.com/am-tropin/restaurant-europe/blob/main/restaurant_recommender.ipynb) notebook.


## The Dashboard

- The result is used in the [Tableau public dashboard](https://public.tableau.com/app/profile/aleksandr.tropin/viz/RestaurantEurope/DBRestaurantEurope).