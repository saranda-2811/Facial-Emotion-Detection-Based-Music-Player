# Facial-Emotion-Detection-Based-Music-Player
This detects the mood of the user, using the facial features. Then it plays music based on the mood detected.
The model is trained on the FER dataset taken from Kaggle. The model is a simple CNN. 
Then, OpenCV is used to get the live feed from the webcam, and the facial mood is detected. The moods which maybe detected are - 'angry', 'disgust', 'fear', 'happy', 'sad', 'surprise', 'neutral'.
Then the Spotipy library is used to play the music based on the mood detected. 
Playlists can be added as needed, but I have taken 65 playlists, based on different moods. 
