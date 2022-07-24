# Movie-Recommender-System that Can Predict the Movie based on your Taste

To get the app Click(https://movierecommenderml.herokuapp.com/)
![image](https://user-images.githubusercontent.com/43883469/180660447-0c1ac1bf-b645-4c82-8a1b-e4414fde25ff.png)

“What movie should I watch this evening?”

Have you ever had to answer this question at least once when you came home from work? As for me — yes, and more than once. From Netflix to Hulu, the need to build robust 
movie recommendation systems is extremely important given the huge demand for personalized content of modern consumers.

An example of recommendation system is such as this:

    User A watches Game of Thrones and Breaking Bad.
    User B does search on Game of Thrones, then the system suggests Breaking Bad from data collected about user A.

Recommendation systems are used not only for movies, but on multiple other products and services like Amazon (Books, Items), 
Pandora/Spotify (Music), Google (News, Search), YouTube (Videos) etc.

Netflix Recommendations

In this post, I will show you how to implement the 5 different movie recommendation approaches and evaluate them to see which one has the best performance.
The MovieLens Dataset

The dataset that I’m working with is MovieLens, one of the most common datasets that is available on the internet for building a Recommender System. The version of the dataset that I’m working with (1M) contains 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.

After processing the data and doing some exploratory analysis, here are the most interesting features of this dataset:

Here’s a word-cloud visualization of the movie titles
