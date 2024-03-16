# Movie Recommendation System

This project implements a movie recommendation system using data from the MovieLens dataset (https://movielens.org/).

**Project Steps:**

1. **Data Loading and Cleaning:**
    - Load movie data from "movies.csv".
    - Clean movie titles using regular expressions.

2. **Feature Engineering:**
    - Create TF-IDF vectors to represent movie titles.

3. **Recommendation Algorithm:**
    - Implement a collaborative filtering approach based on user ratings.
    - Find users who liked similar movies to the target movie.
    - Recommend movies highly rated by these similar users.
    - Prioritize recommendations based on a score combining user and overall popularity.

4. **Interactive Interface:**
    - Build a user interface using Jupyter widgets.
    - Allow users to search for movies by title.
    - Display a list of recommended movies for the chosen movie.

**Code Structure:**

* `movies.csv`: Contains movie data (title, genres, etc.).
* `ratings.csv`: Contains user ratings for movies.
* `movie_recommendation.ipynb`: Jupyter notebook containing the main code.

**Libraries Used:**

* pandas
* scikit-learn
* NumPy
* ipywidgets

**Running the Code:**

1. Install required libraries (`pandas`, `scikit-learn`, `NumPy`, `ipywidgets`).
2. Open `movie_recommendation.ipynb` in a Jupyter notebook environment.
3. Run the notebook cells sequentially.

**Example Usage:**

* Enter a movie title in the search bar.
* Click "Enter" or the search icon.
* The system will recommend similar movies based on user ratings.
