# Video Doorbell, Lab 7

*A lab report by Fei Gao*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[HelloYou](https://www.youtube.com/watch?v=GY_Iy3ZSAF4)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

In order to enable the web camera, we need to import the `node-webcam` library into our webapp. Then we need to create a webcam instance with some pre-defined parameters. Then we bind the "Take a picture" key press with the webcam library's `capture()` method.

**b. Include a video of your working video doorbell**

[Doorbell](https://www.youtube.com/watch?v=P-3-B8mdE0U)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I installed the gm library to resize the image captured. I spent quite some time debugging, but later realized I needed to install the underlying libraries such as `GraphicsMagick` and `ImageMagick`.

**b. Upload a video of your working modified project**

[Zoom Doorbell](https://www.youtube.com/watch?v=jGnmPLySIpM)  
[Source Code](newPictureServer.js)
