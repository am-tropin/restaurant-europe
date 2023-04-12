# European restaurants: Classification, Hypotheses & Recommender

The project classifies restaurants by various features using XGBoost and scikit-learn models and gives content-based recommendations of European restaurants using Jaccard metric from SciPy. Also aggregates the data for the Tableau Public dashboard.

Libraries: numpy, pandas, SciPy, scikit-learn, xgboost, matplotlib


## Table of contents
- [Dataset](#dataset)
- [Machine Learning problems](#machine-learning-problems)
- [The Dashboard](#the-dashboard)


## Dataset

- The dataset of TripAdvisor's data is from [Kaggle](https://www.kaggle.com/datasets/stefanoleone992/tripadvisor-european-restaurants). 


## Machine Learning problems

- The first ML problem is classification of restaurants. The given problem was solved by using a few classifiers using **scikit-learn**. 

    - Classificaton of Italian restaurants by "Serves Alcohol" feature. The **XGBoost** model has the best accuracy score - **77%**.
    - Classificaton of the UK restaurants by "Vegetarian Friendly" feature. The **Random Forest** model has the best accuracy score - **95%**.
    - Classificaton of German restaurants by "price_level" feature. The **Gradient Boosting** model has the best accuracy score - **74%**.

The result is in the [restaurant_classification.ipynb](https://github.com/am-tropin/restaurant-europe/blob/main/restaurant_classification.ipynb) notebook.

- The second ML problem is building a **content-based recommender** by restaurant features. The given problem was solved by using **the SciPy's Jaccord metric** in the [restaurant_recommender.ipynb](https://github.com/am-tropin/restaurant-europe/blob/main/restaurant_recommender.ipynb) notebook.

- The third problem is **hypothesis testing** about relationship between average rating and some restaurant features (Spanish cuisine, Cheap Food, Vegetarian Friendly) for different countries. The given problem was solved by using **Student's and Welch's t-tests** from **SciPy** in the [restaurant_hypothesis_testing.ipynb](https://github.com/am-tropin/restaurant-europe/blob/main/restaurant_hypothesis_testing.ipynb) notebook.


## The Dashboard

- The result is used in the [Tableau public dashboard](https://public.tableau.com/app/profile/aleksandr.tropin/viz/RestaurantEurope/DBRestaurantEurope).