# Background
Moosic is a little start-up that creates playlists curated by music experts and specialists in old and new trends. Users can subscribe to their website and listen to these playlists through their preferred Music App (be it Spotify, Apple Music, Youtube Music…). They love the fact that their playlists have a personal touch, and that each playlist encapsulates a certain “mood” or “style”.
Business is scaling up fast and the music experts are slow in creating new playlists. They have hired me with a clear mission: use Data Science to add a degree of automatisation to the creation of playlists.
They want you to use a dataset that has been collected from the Spotify API and contains the audio features (tempo, energy, danceability…) for a few thousand songs and use a basic clustering algorithm such as K-Means to divide the dataset into a few clusters (which will become playlists).

# Business requirement
Development unsupervised Machine Learning Moosic Model for 5000 songs
# Content
Business requirement, product results and activities description
Algorithm methodology
Playlists presentation
Example of 1 song from a few different clusters.
PROs and CONs of using clustering to create playlists
K-Means method advantages and disadvantages to create playlists
Recommendation for moving forward with K-Means algorithm
Recommendation for moving forward with other methods to create playlists (not considered)
PRESENT DATA SET FROM KMEANS
Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria? 
Additional data for better user experience (production years)
Recommendation and next steps
Learnings from the project
# Business requirement: 
Development unsupervised Machine Learning Moosic Model (MLM) by “Automatisation of Moosic playlists”
# Results:
R1. Algorithm for unsupervised Machine learning  Model (MLM) developed
R2. Algorithm successful tested and functionality confirmed 
# Main activities:
A1. Importing and reviewing data frame quality
A2. Cleaning and scaling data frame
A3. Plotting dataframe in Histogram to visually check correlation between several pairs of  chosen data values to be used for K-Clustering
A4. Plotting data frame in scatter plot to visually check correlation between several pairs of  chosen data values to be used for K-Clustering
A5. Choosing the right number of cluster, using inertia
A6. Bringing decision on optimum number of clusters and set of data pairs which will be used for algorithm development
A7. Data scaling Quantile transformer
A8. K-means calculation for chosen pairs of data for clustering x="energy", y="acousticness"
A9. Plotting and exploring our KMeans results / Comparing our centroids and our dataset
A10. Adding new cluster column to our data frame and defining the names of 10 clusters based on music genre
A11. Data frame analysis to check cluster structure
A12. Visualizing the clusters in a scatterplot with K-means features x="energy", y="acousticness"
A13. Explore relation between sum of energy and accusticness
A14. Ploting relation between energy and accusticness

