Movie Recommender System Using Machine Learning

Developed a Movie Recommender System that suggests similar movies based on user-selected preferences. The system uses content-based filtering techniques and Natural Language Processing (NLP) to analyze movie metadata such as genres, keywords, cast, and crew. Text data is preprocessed using stemming and transformed into numerical vectors using CountVectorizer. Cosine Similarity is then applied to identify and recommend the most relevant movies. The application is built with Python and deployed using Streamlit, providing an interactive web interface where users can select a movie and receive personalized recommendations along with movie posters fetched through the TMDB API.

Technologies Used: Python, Pandas, NumPy, Scikit-learn, NLTK, Streamlit, TMDB API, Pickle

Key Features:

Content-based movie recommendation engine
NLP preprocessing using stemming and text vectorization
Cosine similarity for movie matching
Interactive Streamlit web application
Real-time movie poster retrieval using TMDB API
Fast recommendation generation using precomputed similarity matrices
