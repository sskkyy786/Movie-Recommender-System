Movie Recommender System

An advanced content-based movie recommender system employing cosine similarity with a seamless user interface powered by Streamlit.

Introduction:
The content-based movie recommender system is designed to offer personalized movie recommendations to users based on their preferences and the content of the movies they have enjoyed in the past. The system utilizes cosine similarity to measure the similarity between movies, enabling it to suggest movies that share similar attributes.



Key Components:

Data Collection:
The first step involves gathering movie data, including information about the movie title, genre, cast, director, and other relevant attributes. This dataset will be used to build the recommendation engine.

Feature Extraction:
Next, the relevant features for each movie are extracted from the dataset. These features could include genre vectors, actor embeddings, director information, and other numeric or text-based attributes that define a movie.

Cosine Similarity:
Cosine similarity is applied to calculate the similarity between the features of different movies. This metric measures the cosine of the angle between two non-zero vectors, providing a similarity score between 0 and 1. Higher scores indicate higher similarity.

Recommendation Engine:
The recommendation engine ranks the movies based on their similarity scores with respect to the user's selected movie. The system suggests the top 5 movies with the highest similarity scores.

Streamlit Web Application:
Streamlit is used to create an interactive and user-friendly web application to showcase the movie recommendations. The interface allows users to enter the title of a movie to get personalized movie suggestions.

Workflow:

The user visits the Streamlit website and is presented with an input field to enter the title of a movie they liked or choose from a list of movies.

The system takes the user's input and retrieves the relevant features of the selected movie from the dataset.

Cosine similarity is then computed between the selected movie and all other movies in the dataset based on their features.

The movies with the highest similarity scores are recommended to the user, and the top N recommendations are displayed on the web application.

Users can view the names of 5 recommended movies.

Benefits:

Personalized Recommendations: Users receive movie suggestions tailored to their individual preferences based on their previous interactions with the system.

Content-based Filtering: The system recommends movies with similar content, which ensures that the suggestions align with the user's interests.

User-Friendly Interface: Streamlit provides an intuitive and visually appealing web interface, making it easy for users to interact with the recommendation system.

Real-time Updates: The system can be continuously updated with new movie data, ensuring that users receive the latest and most relevant recommendations.

No Dependency on Ratings: Unlike collaborative filtering methods, content-based recommendation does not rely on user ratings, making it suitable for new users or those with limited interaction history.

Conclusion:
By combining a content-based movie recommender system with cosine similarity and presenting the recommendations through a Streamlit-powered website, users can enjoy personalized movie suggestions based on their preferences and explore new movies that align with their tastes, creating a more engaging movie-watching experience.



Datasets:

You can download the data sets from the below links-

https://drive.google.com/file/d/1ts5r4bfW6XnZqkBJYbXZMgBZXbWCbuyS/view?usp=sharing

https://drive.google.com/file/d/1XTkdDObuvnLtnqsJOg7R-d-xSpAhrVnw/view?usp=sharing

