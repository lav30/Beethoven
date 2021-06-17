# Visualizing Ludwig van Beethoven's Musical Journey

[Ludwig van Beethoven](https://en.wikipedia.org/wiki/Ludwig_van_Beethoven) was a German composer, who is one of the most popular composers in classical music history. The main inspiration behind this project was in honor of Beethoven's 250th birth anniversary celebrated in 2020. Beethoven's compositions are mainstays of Western classical music and are performed regularly by symphony orchestras around the world. 


* **Data Acquisition (Spotify API)** : The dataset was accessed using the Spotify API using the spotipy package. The Spotify API returns an artist's metadata in JSON format and this has been transformed into a Pandas dataframe for easier data analysis. 

* **Data Storytelling** : Visual analysis has been performed using Matplotlib and Seaborn packages.

* **Dataset Information** : This dataset has all the compositions from Beethoven's repertoire. The observations describe several audio features of each track including valence, acousticness, loudness,etc. Detailed information about the descriptive features can be found here [Audio features of tracks](https://developer.spotify.com/documentation/web-api/reference/#category-tracks).

## Initial Overview 

- The table below shows the distribution of three features in the dataset.

*Valence is the positiveness of a track, tempo is the speed of the track and key measures the key the track is in, where the pitch is mapped to integers*. 

|    Valence    |     Tempo     |    Key      | 
| ------------- | ------------- | ------------
|![Alt text](Images/11.png?raw=true "Title")  | ![Alt text](Images/12.png?raw=true "Title")  | ![Alt text](Images/13.png?raw=true "Title")

- This table displays the distribution of features over the duration of the tracks.

*Most of the compositions are relatively short, as evident from the graphs below.*

| Loudness  | Valence |
| ------------- | ------------- |
| ![Alt text](Images/3.png?raw=true "Title")| ![Alt text](Images/5.png?raw=true "Title")  |


- The table below displays pairwise scatterplots and jointplots to better understand the interaction between features. 


| Tempo & Loudness  | Valence & Tempo | Valence & Danceability |
| ------------- | ------------- | --------------------------------
| ![Alt text](Images/26.png?raw=true "Title")| ![Alt text](Images/25.png?raw=true "Title")  | ![Alt text](Images/23.png?raw=true "Title") 






