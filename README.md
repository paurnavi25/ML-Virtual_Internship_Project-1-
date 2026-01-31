# ML-Virtual_Internship_Project-1-
Task 1: Predicting Restaurant Ratings

Objective:
Build a machine learning model to predict the rating of a restaurant based on various features.

What I did:

Loaded and explored the dataset.
Performed basic preprocessing like converting data types.
Selected the important columns for model training.
Trained a regression model to predict restaurant ratings.

Output files:

- restaurant_rating_model(task1).pkl
- Task1_Paurnavi.ipynb

Task 2: Restaurant Recommendation System

Objective:
Recommend similar restaurants based on user input.

What I did:

Cleaned text columns such as restaurant name, cuisines, and reviews.
Created a combined text feature for each restaurant.
Applied TF-IDF vectorization to convert text into numerical form.
Used cosine similarity to find similar restaurants.
Added an optional feature to return top N recommendations.

Output files:

- tfidf_vectorizer(task2).pkl
- recommender_data(task2).csv
- Task2_Paurnavi.ipynb

Task 3: Location-Based Restaurant Analysis

Objective:
Analyze restaurants based on geographical locations.

What I did:

Explored latitude and longitude coordinates from the dataset.
Created visual maps to show restaurant distributions.
Grouped restaurants by city and locality for comparison.
Calculated statistics like:
Most common cuisines by city,
Cities with highest number of restaurants,
Cities with higher average ratings.
Generated HTML maps for interactive viewing.

Output files:

- city_stats(task4).csv
- locality_stats(task4).csv
- locality_stats_top20(task4).csv
- df_loc_for_maps(task4).csv
- high_avg_rating_cities(task4).csv
- Interactive maps (HTML files)
- Task3_Paurnavi.ipynb
