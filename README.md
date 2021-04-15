# Hand-Gesture-Volume Control
Inroder to control the volume of a particular track, you can use your hand to change the volume among these distinct values :0%,40%,60%,80%,100%.
First step is that you have to copy the path of a partilcular audio file and paste it in the .ipynb file. now when you run the code, the camera window will pop up and you can show the fingers, the way you want to adjust your volume to.

Now the way it works is that, it considers distinct contours formed with your fingers. If there is no gap in betwen your fingers, it will count it as 1 and volume will be 0%.
If there is decent separation between the fingers, it will consider them as its count of fingers and adjust the volume accordingly.

A module of vlc player is used to play the song, but it does require path of that audio file in order to run it.
