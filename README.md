# Spotify-Recommender-System
A music recommender system implemented using K Means clustering

Spotify recommending personalized music and creating customized playlists is one of the most common and widespread use of predictive tasks in music. Spotify has a web API that helps to retrieve the audio features and metadata about the songs.

In this project, the Spotify Song Dataset from Kaggle has been used, along with Spotipy, a python client for Spotify, to build a content based recommender system.
The metadata of all the music in the dataset has been analyzed to find insights into the audio features.

I have next used K-means clustering to group the various genres in appropriate clusters based on the audio features. Further, I have used PCA for dimensionality reduction.
For the prediction, the average vector of the audio and metadata features for each song listened by the user is calculated. The nearest few points are calculated to this average vector. The songs corresponding to those points are thus been recommended. 
