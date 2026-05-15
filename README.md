# DEMiCo
DEMiCo: A Music-Induced Emotion Dataset Integrating Physiological Signals, Dual Emotion Models and Listener Profiles

This anonymized repository provides review-time resources associated with the submitted paper. 
Due to double-anonymous review and copyright/privacy considerations, the full dataset release is currently under preparation. 
The complete release will include anonymized metadata, music links with timestamps, emotion annotations, physiological signal data, and listener-level profile data.

```text
Dataset /
├─ README.md
│
├─ Metadata.csv  # spotify_id, track_title, artist_name, album_name, duration_m_s, 
│               genres
│
├─ Audio_Features.csv  #spotify_id, acousticness, danceability, energy,
│                   instrumentalness, liveness, loudness, speechiness, tempo,
│                   valence.
│
├─ Physiological_signals
│  └─ User_id (User1 ~ User20)
│    ├─ bvp
│     │  └─song_index_id.csv (song_index_0.csv ~ song_index_20.csv)
│    ├─ eda
│     │  └─song_index_id.csv (song_index_0.csv ~ song_index_20.csv)
│    └─ temp
│        └─song_index_id.csv (song_index_0.csv ~ song_index_20.csv)
│
├─ Listener_level_profiles.csv  # user_id, age, gender, music preferences,
│                           personality traits (TIPI)​​
│ 
├─Emotion_Annotations.csv  # user_id, song_index, spotify_id, Arousal, Valence,
│                         GEMS-9
│
└─Music_Reference.csv # spotify_id, link, start_timestamp_m_s, end_timestamp_m_s
```
