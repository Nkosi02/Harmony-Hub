Harmony Hub


Introduction


Music serves as a powerful universal language. It plays a huge role in connecting our communities and also sharing our moods. Truly music brings a colourful experience in our lives. However, It can be easy to stick to a few songs that we know and quite difficult to discover  new artists. This is why we created our Music Recommendation App, Harmony Hub.


Harmony Hub discovers songs and artists based on your mood. It looks at the artists and songs that the user repeatedly plays and recommends similar songs . Users can discover new songs and also find out more information about the artist.


Team members

Nkosinathi Mabizela : Owner , Software engineer




Description

The emotion recognition model is trained on FER 2013 dataset. It can detect 7 emotions. The project works by getting a live video feed from a webcam, passing it through the model to get a prediction of emotion. Then according to the emotion predicted, the app will fetch a playlist of songs from Spotify through spotify wrapper and recommend the songs by displaying them on the screen.


DATA

The file contains more than 160,000 songs collected from Spotify Web API, and also you can find data grouped by artist, year, or genre in the data section.
It has features like acousticness, energy, loudness and danceability which make the clustering algorithm work more effectively.


How to use

This application can be used by executing the run.py file which then opens up a GUI asking the user to enter the name of the artist.
This will then collect required albums from the API and then will open up your WebCam .
Just click the 'q' button on the keyboard to stop capturing the image and the GUI will lead you through.
Clicking on the print button will make the recommendations ready for you.






Libraries to Use

OpenCV.
Tensorflow and Keras.
Sklearn.
LightGBM.
Spotipy.
Tkinter.
Pillow.







