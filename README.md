# Song-Popularity-Predection
This project aims to develop a machine-learning model that predicts the popularity of song on a scale of 0-100. We use a data set from Spotify that includes 13 key audio user engagement features, excluding song titles because they have little effect on popularity.
# Type of Problem:
This is a regression problem because we're aiming to predict a continuous numerical value which is the song's popularity on a scale of 0-100. All the information we're using to make this prediction (the 13 features) are also numbers.
# Motive:
Predicting song popularity is important in the current digital music industry because it provides valuable insights for music professionals and can give them a competitive advantage. By estimating the success of a song before its release, industry professionals can make informed decisions about marketing strategies, resource allocation, and artist promotion. Additionally, predicting song popularity can help in identifying the characteristics and factors that contribute to a song's success, such as intrinsic lyrical and acoustic characteristics, extrinsic factors like publisher influence and support, and the social components of the spreading of song popularity. Understanding these factors can aid in the creation of more popular and commercially successful songs. (scispace, 2024)
# Meta Data:
**1: song_name**

This feature is the object type, and defines the name of the song.

**2: song_popularity**

This is a number type feature on top of that it is the target feature of the project which defines the popularity of a song on a scale of 0-100.

**3: Song_duration_ms**

It is a number and defines the duration of the song in milliseconds.

**4: acousticness**

It is a number, confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.

**5: danceability**

It is a number data type, and danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.

**6: energy**

It is a number type feature, and it is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.

**7: instrumentalness**

It is a number type feature, Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.

**8: key**

It is a number type feature, The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.

**9: liveness**

It is a number type feature and detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides a strong likelihood that the track is live.

**10: loudness**

It is a number type feature and describes the overall loudness of a track in decibels.

**11: audio_mode**

It is a number type feature and it indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.

**12: speechiness**

It is a number type feature and it represents the presence of spoken words in a track.

**13: tempo**

It is a number type feature and in musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.

**14: time_signature**

It is a number type feature and the time signature (meter) is a notational convention to specify how many beats are in each bar (or measure). The time signature ranges from 3 to 7 indicating time signatures of "3/4", to "7/4".

**15: audio_valence**

