# Project: Browser-based 3D Pose Estimation

[Background information for our project is available here.](http://www.heuckroth.com/CS585_Project/proposal/)

## Demonstration

Since our solution is implemented in Javascript and HTML5, it can be run easily from most modern web browsers. We recommend Chrome, but 

[You can access the demo here.](https://nesciosquidsecure.github.io/CS585_Project/demo/)

You will need access to an augmented reality marker to display in front of the webcam to localize the "hologram." 

[Here is a pattern we created](https://raw.githubusercontent.com/Nesciosquid/CS585_Project/master/demo/markers/MultiMarkerDuo.png) which uses multiple markers to improve tracking quality, which can be either printed or displayed on an electronic screen. Be aware that glare from shiny cell phone screens can impede tracking performance.

You can view any standard STL file. We recommend checking out [Thingiverse](https://www.thingiverse.com/) to find interesting, 3D-printable models to display. Simply download one that looks interesting, then drag and drop it into the viewing window to load it up.

## Tools Used

* [js-aruco](https://github.com/jcmellado/js-aruco): Augmented reality library which provided both marker detection and basic 3D pose estimation functions
* [kalman.js](https://github.com/itamarwe/kalman): Kalman Filter library, used to smooth out position and rotation data between samples
* [sylvester.js](http://sylvester.jcoglan.com/): Matrix math library, required to support kalman.js 
* [three.js](https://github.com/mrdoob/three.js/): 3D graphics library, which provides support rendering 3D objects using WebGL
* [STL Viewer](https://gist.github.com/bellbind/477817982584ac8473ef/): Used for loading arbitrary STL files.
* [BadTV Shader](https://www.airtightinteractive.com/demos/js/badtvshader/): Used to provide hologram-like distortion effects to the rendered image.
* [webcam.js](https://github.com/jhuckaby/webcamjs): Provides cross-browser support for loading webcam images as standard HTML5 video.
* [Google Material Design Lite](http://www.getmdl.io/): Web framework for look and feel.
   

