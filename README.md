# Your-Next-Movie
A recommendation system for movies deployed on streamlit.
This project exemplifies the practical application of machine learning in the domain of personalized content recommendation. The system leverages data from TMDB dataset and employs a unique approach based on movie tags (cast, crew, keywords, overview). Tags are associated with each movie, and through the utilization of bag of words technique, these tags are transformed into numerical vectors. 
When vectorizing the data, we don't calculate the Euclidian distance. We calculate the cosine distance, meaning the angle between two vectors. This is due to the fact that we are dealing with vectors of high dimension, where Euclidian distance get inaccurate, but cosine does not.
Through this, we are able to recommend 5 similar movies based off of a movie the user has watched.
[Your Next Movie](https://yournextmovie.streamlit.app/)
