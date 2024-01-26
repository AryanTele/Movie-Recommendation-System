# Movie-Recommendation-System

### 1. Project Overview
This project focuses on the development of a content-based recommendation system for movies using machine learning techniques. The primary goal is to build an application that suggests movies similar to a user-provided input. The dataset for this project is obtained from The Movie Database (TMDB) API, and the system is designed to recommend movies based on textual features using a bag-of-words model.

### 2. Objectives
    - Build a content-based recommendation system for movies.
    - Utilize the TMDB API for obtaining movie data.
    - Implement a bag-of-words model for text vectorization.
    - Recommend 5 movies similar to the input movie based on textual features.

### 3. High Level Overiew of the Project

![Recommendation Model ](https://github.com/AryanTele/Movie-Recommendation-System/assets/58328909/25217583-56dc-4aae-a86f-df9a29ce3e6c)

### 4. Methodology
    - 4.1 Dataset
    The TMDB API provides a rich dataset with details about various movies, including titles, 
    synopses, genres, and more. The dataset is preprocessed to extract relevant textual features 
    for the recommendation system.

    - 4.2 Text Vectorization
    Text vectorization is performed using a bag-of-words model. This model represents each movie's 
    synopsis as a vector of word frequencies, disregarding the order of words. This allows for a numerical 
    representation of textual data suitable for machine learning algorithms.

    - 4.3 Recommendation Algorithm
    The recommendation algorithm compares the bag-of-words vectors of movies to identify similarities. 
    Cosine similarity is used as a measure, producing a score for each movie pair. The top 5 movies with the 
    highest similarity scores to the input movie are recommended.

### 5. Results

<img width="1440" alt="Screenshot 2024-01-26 at 9 08 58 PM" src="https://github.com/AryanTele/Movie-Recommendation-System/assets/58328909/2e2dc837-240b-4c03-8c85-162cec7a1204">

<img width="1440" alt="Screenshot 2024-01-26 at 9 09 11 PM" src="https://github.com/AryanTele/Movie-Recommendation-System/assets/58328909/4157beeb-dac8-47ac-8179-102fe4ae6f72">

### 6. Conclusion
The content-based movie recommendation system demonstrates the feasibility of leveraging textual features for personalized suggestions. The project successfully integrates the TMDB API, implements text vectorization, and offers a functional recommendation engine.

### 7. References
    1. The Movie Database (TMDB) API Documentation: https://www.themoviedb.org/documentation/api
    2. Scikit-learn Documentation: https://scikit-learn.org/stable/documentation.html
    3. Natural Language Toolkit (NLTK) Documentation: https://www.nltk.org/





