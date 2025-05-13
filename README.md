# Movie-Recommendation-System
Welcome to the Movie Recommendation System, a content-based recommendation engine built using Python and Streamlit, with development and prototyping done in Jupyter Notebook. This web application suggests movies based on a user's favorite film by analyzing movie metadata like genres, cast, director, and plot overviews.

The system is designed to be simple, fast, and user-friendly, making it easy for users to explore new films based on their interests.

🧠 How It Works
This recommendation system uses content-based filtering, which means it suggests movies that are similar in content to the one provided by the user. We calculate similarity between movies using text vectorization techniques like TF-IDF and cosine similarity on relevant features such as:

Genre

Keywords

Cast

Crew

Overview

By combining and processing this metadata, we compute a similarity score and display the top recommendations in the Streamlit web interface.

💻 Tech Stack & Tools
Python 3

Jupyter Notebook – for exploratory data analysis and model development

Pandas, NumPy – for data manipulation

scikit-learn – for TF-IDF vectorization and similarity computation

Streamlit – to create the web application interface

TMDB Dataset – movie metadata (title, overview, cast, crew, etc.)

