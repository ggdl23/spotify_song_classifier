# Spotify Song Classifier
Written on Oct 2019
This is like 3 weeks into learning python

# Aim
Our aim was to use features provided by Spotify for each of their songs to predict the genre of a song. Since this is done merely as proof of concept, we narrowed down the number of genres we attemped to predict to 4: 'hip hop', 'classical', 'metal' and 'country. 

# Contents
1. genre_getter.ipynb
This script is used to request the song genre from Spotify's endpoint. You will have to access your developer account at developer.spotify.com in order to obtain your unique client id and client secret.

2. genre_classifier.ipynb
This notebook documents the process of feature selection, unsupervised clustering via K-means clustering, and supervised K-Nearest neighbors classification. Accuracy without hyperparameter optimization was 80%

# Dataset
The dataset used in this analysis is Spotify Song Attributes by George McIntire at https://www.kaggle.com/geomack/spotifyclassification.
