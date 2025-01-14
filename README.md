# Spotify Tracks DB Analysis in Looker Studio

This repository demonstrates data analysis and visualizations using Looker Studio (formerly Google Data Studio) on the Spotify Tracks DB dataset.

## Dataset
Dataset Link: https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db?resource=download

The dataset used in this analysis includes the following fields:

- `genre`: Genre of the track
- `artist_name`: Name of the artist
- `track_name`: Name of the track
- `track_id`: Unique identifier for the track
- `popularity`: Popularity score of the track
- `acousticness`: Measure of acoustic sound in the track
- `danceability`: Measure of danceability
- `duration_ms`: Duration of the track in milliseconds
- `energy`: Energy level of the track
- `instrumentalness`: Measure of instrumental content
- `key`: Musical key of the track
- `liveness`: Measure of presence of a live audience
- `loudness`: Loudness of the track
- `mode`: Musical mode of the track
- `speechiness`: Measure of speech content
- `tempo`: Tempo of the track
- `time_signature`: Time signature of the track
- `valence`: Mood of the track

## Computations

The following computations were performed to transform and analyze the data:

1. Artists - Number of Unique Artists
2. Track Length Category (categorizes tracks based on duration)
3. Energy Intensity Category - categorizes energy into Low, Medium, and High
4. Mood Classification - classifies mood based on energy and valence
5. Duration in Minutes - converts duration from milliseconds to minutes

## Visualizations

The following visualizations were created to explore trends and patterns within the data:

1. **Bar Chart (Horizontal)** - Most Popular Tracks based on `popularity`.
2. **Bar Chart (Horizontal)** - Most Popular Artists (average `popularity`), broken down by `genre`.
3. **Bar Chart (Vertical)** - Track Length Distribution (categorized into Short, Medium, Long based on record count).
4. **Bar Chart (Vertical)** - Energy Intensity Distribution (categorized into High, Medium, Low based on record count).
5. **Bar Chart (Vertical)** - Mood Distribution (categorized into Happy, Energetic, Sad, Calm based on record count).
6. **Pie Chart** - Genre Popularity (slices represent genres, size based on average `popularity`).

## Conclusion

These visualizations and computations provide insights into the Spotify Tracks DB, including the distribution of track lengths, energy intensity, mood classification, and genre popularity. By analyzing these trends, users can better understand the characteristics that define popular tracks and genres on Spotify.
