# PotterHead
Harry Potter's Invisible Cloak
This project is exactly what you are thinking about. Yes,a high contrast coloured object brought into the frame gets invisible.Through it we can see the background.Interesting isn't it?

Firstly we capture the background frame for about 2-3 seconds.
Soon whenever we bring any high contrast object of the designated colour values it gets invisible.
We use the HSV colour conversion to seperate out the necessary colour from the frames captured by the camera.
Mainly the concept of seperating the foreground and the background is used using the morphological transformations.We use to to remove the noises and then dilate it to make it accurate and easy to identify.Morph Erosion mainly erodes some features of the background and foreground seperation.
Using mask we add both the Morphological transformations.
Incorpoating the bitwise_AND feature we just add the background and the foreground together in a single frame and show it to the user.

We can also generate a soft copy of the video being produced
