# Borders
Implemented stretching frames inside the window in which the robot's camera image was broadcast using JavaScript and ROS, as well as Html and CSS
### My part of the job
At the start I had a site that can only broadcast a robot image. My task was to make it so that right in the window with the image you can stretch the frames, after which you can sign them and send everything to a certain topic ROS. I modified the index.html file by adding js code to it and changing the Html code of the page itself. I also added an after.css file in the folder with the css files. These frames are needed to highlight objects and name them, and the robot remembers them.
### How to use the site 
While selecting frames, the image stops updating until the user submits the selected frames or cancels them all. If you enter an empty name for a frame, the frame will disappear. The site was made in Russian, the green button is needed to send data about the selected image (width, height, coordinates of the center of the image, as well as the name you gave the frame).
## WARNING
To get the image on the site from the TurtleBro robot you need to start it and connect to the same network with it, otherwise the framework can only be tested on an empty area on the site where the video from the robot should be broadcast.

<img src="https://github.com/gleverrr/BordersJS/blob/main/screen.png" alt="screen" height = "350">
