# Movie Recommender System
The project involves creating a movie recommendation system using data manipulation, natural language processing, and similarity analysis.

The steps involved in the creation of the recommender system are:

## 1) Data Preparation:
- Combined and processed data from multiple dataframes to create a comprehensive dataset.
- Selected relevant columns such as movie_id, title, overview, keywords, cast, and crew.

## 2) Feature Engineering:
- Consolidated the selected columns (overview, keywords, cast, and crew) into a single column named tags.

## 3) Text Processing:
- Applied stemming on the tags column to standardize and preprocess the text.

## 4) Vectorization:
- Utilized CountVectorizer to convert the textual data within the tags column into vectors.

## 5) Similarity Calculation:
- Computed the cosine similarity of the vectors to determine the similarity between movies.

## 6) Recommendation Generation:
- Retrieved the top 5 movies based on their similarity scores.

# Demo:
<img width="1392" alt="Screenshot 2023-11-06 at 1 09 20 PM" src="https://github.com/naveedeveloper/movie-recommender-system/assets/64096661/927810a8-744e-4c4c-865c-a86fd42c042c">
<img width="1392" alt="Screenshot 2023-11-06 at 1 09 46 PM" src="https://github.com/naveedeveloper/movie-recommender-system/assets/64096661/8f074fcf-344b-4296-bf13-9eb34207a71a">
<img width="1392" alt="Screenshot 2023-11-06 at 1 09 58 PM" src="https://github.com/naveedeveloper/movie-recommender-system/assets/64096661/7f64bb0d-63a5-4af4-a2c1-4083b90608b4">
<img width="1392" alt="Screenshot 2023-11-06 at 1 10 15 PM" src="https://github.com/naveedeveloper/movie-recommender-system/assets/64096661/8bd17dba-2efd-4829-8547-3a3f143a3c69">
