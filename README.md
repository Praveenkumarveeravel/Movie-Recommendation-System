Project Overview:

	This project is a Movie Recommendation System that suggests movies to users based on their preferences. It utilizes Collaborative Filtering (K-NN) and Content-Based Filtering techniques to make personalized movie recommendations. The system analyzes user behavior (such as ratings) and movie metadata to provide accurate and relevant recommendations.

 Technologies Used
 
Python: Programming language for developing the model.

Pandas: For data manipulation and analysis

NumPy: For numerical computations.

Scikit-learn: For building the K-NN model and other machine learning tasks.

Cosine Similarity: For calculating similarity in content-based filtering.

Jupyter Notebook: For interactive development and testing.

Approach

Collaborative Filtering (K-NN):

Based on user ratings. If two users have similar tastes (rated similar movies highly), movies liked by one user can be recommended to the other.
Uses K-Nearest Neighbors (K-NN) to find similar users or items.

Content-Based Filtering:

Recommends movies that are similar to the ones the user liked, based on movie metadata such as genre, director, and cast.
Cosine Similarity is used to compute the similarity between movies.
