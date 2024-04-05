## Movie-Recommendation-System-Using-BS4

**Title: IMDb Movie Recommendation System**

**Overview:**
The IMDb Movie Recommendation System is a Python script that allows users to input a movie title and retrieves information about the movie, including its director and a list of recommended movies based on the director's known works. The script scrapes data from IMDb's top-rated movies page and utilizes web scraping techniques to extract relevant information.

**Features:**

**1. User input:** Users can enter a movie title to retrieve information about the movie.

**2. Data scraping:** The script fetches data from IMDb's website using requests and BeautifulSoup libraries.

**3. Movie details:** It provides details about the requested movie, including its director and a list of recommended movies.

**4. Recommendation system:** Based on the director's known works, the script suggests similar movies for users to explore.

**Usage:**
Run the script imdb_movie_recommendation.py.
Enter the name of the movie you want to search for.
The script will display the IMDb URL of the movie, the director's name along with their IMDb profile URL, and a list of recommended movies.

**Dependencies:**
Python 3, requests, BeautifulSoup
