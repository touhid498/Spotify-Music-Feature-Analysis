# Spotify-Music-Feature-Analysis
## Overview
I have done a simple analysis of song features extracted from spotify. The data has several features of audio such as danceability, loudness, tempo etc. The songs are taken from a user playlist and also contains the data if the user liked it or not.</br>
## Goal
My goal is to do some data analysis to check the correlation of the target varieable which is liked or not liked with the audio features.</br>
## Motivation & Background
This project is motivated by the following projec: [Spotify music analysis](https://www.kaggle.com/aeryan/spotify-music-analysist)</br>
## Data
Data is taken from [Kaggle](https://www.kaggle.com/aeryan/spotify-music-analysis)</br>
After importing the data I have analysed the correlation between the target and the features of the audio</br>
<img src='https://github.com/touhid498/Spotify-Music-Feature-Analysis/blob/main/IMG/img1.PNG'>
<img src='https://github.com/touhid498/Spotify-Music-Feature-Analysis/blob/main/IMG/img2.PNG'></br>
The following heatmap shows the correlation and the value</br>
</br>
<img src='https://github.com/touhid498/Spotify-Music-Feature-Analysis/blob/main/IMG/img3.png'>
</br>
I have used 80% data for training and rest for testing. Then I have used three classification model which are Decision Tree, K nearest neighbour and Random forest classification model and their prediction accuracy were 68.4%, 69.4% and 76.5% respectively.

## Table of Content
Dependency
-Seaborn</br>
[Data](https://github.com/touhid498/Spotify-Music-Feature-Analysis#data)</br>
[Packages](https://github.com/touhid498/Spotify-Music-Feature-Analysis/blob/main/README.md#packages-and-software)
## Limitations
I have not checked for the best parameters for the model. So, my accuracy data is not optimized.
## Packages and Software
-Sklearn</br>
-Numpy</br>
-Panda</br>
-Matplotlib
