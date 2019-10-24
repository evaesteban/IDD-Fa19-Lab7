# Video Doorbell, Lab 7

*A lab report by Eva Pilar Esteban Velasco*

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Link to HelloYou Video](helloYouVideo_Muted.mp4)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

The variables that pictureServer.js and server.js have in common are initialized as general variables in pictureServer.js, whereas in server.js they are initialized as constants. The variable NodeWebcam only appears in pictureServer.js, and it allows the webcam functionality. There is a default webcam setup section, which includes a few options – stored in the structure opts - to define how the webcam is operated. The variable NodeWebcam is initialized according to these options. The pictureServer.js code also includes a function at the end to take a picture when the user presses the ‘Take a picture’ button. 

**b. Include a video of your working video doorbell**



## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

**b. Upload a video of your working modified project**
