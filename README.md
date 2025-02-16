# MUSIC-RECOMMENDATION-SYSTEM
# Problem Statement
- This project aims to develop a music recommendation system using Spotify data, leveraging machine learning techniques and data analysis to provide personalized song recommendations based on user preferences, song features, and genre distributions.
# Important Feature in Data
 
 - Track Name – Name of the song.
 - Artist – Name of the artist/band.
  - Album – Name of the album the song belongs to.
  - Genre – The genre of the track (e.g., Pop, Rock, Jazz).
  - Popularity – A numeric score representing how popular the song is on Spotify.
  - Danceability – A measure (0-1) of how suitable the track is for dancing.
  - Energy – A measure (0-1) of the song’s intensity and activity level.
  - Loudness – The overall loudness of the track in decibels (dB).
  - Speechiness – The presence of spoken words in the track.
  - Acousticness – A measure (0-1) of how acoustic the track is.
  - Instrumentalness – The likelihood of a track containing no vocals.
  - Liveness – Detects the presence of a live audience in the recording.
  - Valence – A measure of how positive or happy a song feels.
  - Tempo – The speed of the track in beats per minute (BPM).
  - Explicit – Whether the track has explicit lyrics (0 or 1).
  - released date - show the date when the movie is relased.
# Libraries 
  - base64 : This library is used to encode the client ID and secret into a base64 string for authentication with the Spotify API.
   - requests : requests library for to send the request to the server.
   - Pandas : is used for data manipulation and analysis.
    - time : Pandas is used for data manipulation and analysis.
# Steps perform for Data Fetching
  1. Importing libraries.
  2. Authentication : client_id,client_secret
  3. Access token
  4. Data Fetching
  5. Rate limit
  6. Data saving
