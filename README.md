# Video Doorbell, Lab 7

*A lab report by Eva Pilar Esteban Velasco*

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Link to HelloYou Video](helloYouVideo_Muted.mp4)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

The variables that pictureServer.js and server.js have in common are initialized as general variables in pictureServer.js, whereas in server.js they are initialized as constants. The variable NodeWebcam only appears in pictureServer.js, and it allows the webcam functionality. There is a default webcam setup section, which includes a few options – stored in the structure opts - to define how the webcam is operated. The variable NodeWebcam is initialized according to these options. The pictureServer.js code also includes a function at the end to take a picture when the user presses the ‘Take a picture’ button. 

**b. Include a video of your working video doorbell**

[Link to Video Doorbell](VideoDoorbell_Muted.mp4)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

First, I tried the 'email' library because my idea was to notify someone via email when someone rang the doorbell. It did not work and after debugging it for some time, I decided to try a new idea, which was to display the picture of an animal to mock the person ringing the doorbell in a friendly way, implying that the camera took a picture of them and the animal in the picture is how they look. I used the 'random-animal-pictures' library for this. But then, I came up with another idea that I liked more, which was to display random funny gifs from the internet to entertain the visitor while they wait at the door. This is my final product. The library I used is 'animals-api', which can get either cat, dog, duck, fox or other animal gifs from the internet. I chose to display cats. Every time the person presses the button, they can see a new funny gif. The code for this can be found in the repository. I also left the code for the previous video doorbell commented on the same file. 

**b. Upload a video of your working modified project**

(Link to Cat Gif Doorbell)[CatGit_Muted.mp4]
