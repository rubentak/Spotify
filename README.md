# Spotify
Getting started with Spotify in python

Spotify Library Analyzer

This project is a Python script that retrieves information about the user's Spotify library, including the saved tracks and their audio features. The user credentials are stored in a separate file called "credentials.py" for security purposes. The script uses the Spotipy library, which is a Python library for the Spotify Web API, to interact with the Spotify API.

Credentials
The user's Spotify API credentials are stored in the "credentials.py" file. The "USER", "CID", "SECRET", and "REDIRECT" variables in the "credentials.py" file need to be filled with the user's own credentials. These credentials are used to create a token that is used to access the user's Spotify data.

Retrieve User Data
The script retrieves the user's data, including their name, number of followers, and Spotify profile link, using the Spotify API and the created token.

Retrieve Saved Tracks
The script retrieves the user's saved tracks from their Spotify library using the Spotify API and stores the tracks in a dataframe. The dataframe contains information about each track, including the track's ID, name, popularity, artist, album, release date, and duration.

Retrieve Audio Features
The script retrieves the audio features of the saved tracks using the Spotify API and stores the features in a dataframe. The audio features include acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, tempo, time signature, valence, and mode. These features provide insights into the musical characteristics of the saved tracks.

Save Data
The retrieved track information and audio features are saved as CSV files for further analysis and visualization.


This project can be used to gain insights into the user's Spotify library, such as understanding the musical characteristics of their saved tracks and analyzing trends in their listening habits.
