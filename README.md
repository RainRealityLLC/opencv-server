# OpenCV-Server

Real-time eye detection using OpenCV, Node.js, and sockets.io.

Displays possible vuforia alternative, all packaged neatly in one node webapp using OpenCV, Sockets.io, and Three.js

## Requirements

* [Node.js](http://nodejs.org/)
* [OpenCV 2.4.x](http://opencv.org/) **MUST BE 2.4.x , NOT 3.x**
* A webcam, e.g. laptop-integrated webcam, USB webcam

## Installing Node.js packages

* Navigate to the `server` directory
* To install the packages: `npm install`

## Running the demo

* Make sure you are still in the `server` directory
* To run the server: `node server.js`
* To run the demo locally, open a browser and go to `localhost:8080`

The app should be up and running!

## To Do
* Integrate Three.js into stream (this will be  the biggest challenge)
* Find object detection xml file that will detect something useful to use
	* identifiable contour detection possibly?

