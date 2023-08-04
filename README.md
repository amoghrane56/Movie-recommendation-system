# Movie-recommendation-system

1. Explanation of the Chosen Dataset:
For the movie recommendation system, the dataset of choice is "tmdb_5000." 
The dataset consists of two data frames, namely "movies" and "credits." The 
"movies" dataset contains movie metadata, including budget, genres, 
homepage, keywords, overview, runtime, popularity, language, and other 
relevant features. On the other hand, the "credits" dataset provides 
information about movie id, title, cast, and crew.
The "tmdb_5000" dataset is widely recognized and extensively used in the 
recommendation system community. It offers valuable movie ratings and 
metadata, making it an ideal choice for developing a content-based 
recommendation system. The availability of user-movie interactions and movie 
characteristics is crucial for building a recommendation system that can 
effectively personalize movie suggestions based on users' preferences and 
movie attributes. The combination of these features from both datasets allows 
the system to provide relevant and tailored movie recommendations to users.

2. Method of Approach:
The approach used to build the recommendation system is a content-based 
filtering method based on cosine similarity. The content-based filtering 
technique leverages movie attributes, such as genres and other metadata, to 
recommend movies to users with similar preferences. Cosine similarity is 
employed to measure the similarity between movies based on their features. 
The movies with the highest cosine similarity to a user's preferred movie are 
recommended to the user

3. AI Tools Used:
The primary AI tool used in this project is the Scikit-learn library, which 
provides robust tools for natural language processing and machine learning. 
We utilized Scikit-learn to implement the content-based filtering algorithm and 
cosine similarity calculation.

4. Derived Data Parameters and Insights:
The derived data parameters used in the recommendation system are the TFIDF vectors of movie genres. These vectors capture the importance of each 
genre in a movie's description. The cosine similarity between movies based on 
their genre vectors helps in identifying similar movies.
Insights drawn from the content-based recommendation system include 
understanding how movie genres influence recommendations. The system 
suggests movies to users based on their preferred movie's genre, making it 
relevant to their interests.

5. Model Demonstration:
During an interview round, I am prepared to demonstrate the content-based 
movie recommender system live. I will showcase how the system takes a user's 
preferred movie as input and provides personalized movie recommendations 
based on content similarity.

Conclusion:
The content-based movie recommender system based on cosine similarity 
offers efficient and personalized movie recommendations. It considers user 
dynamics and preferences by suggesting movies like the user's preferred movie 
in terms of genres and other metadata. The system is implemented using 
Python and Scikit-learn, providing a robust and effective approach to movie 
recommendation based on content similarity
