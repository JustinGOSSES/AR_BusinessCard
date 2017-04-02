# An Augmented Reality Business Card of Gale Crater on Mars
AR Images in Action
<img src="https://github.com/JustinGOSSES/AR_BusinessCard/blob/master/images/Screen%20Shot%202017-04-01%20at%209.39.35%20PM.png" width="500">
Icon that is AR Target
<img src="https://github.com/JustinGOSSES/AR_BusinessCard/blob/master/images/kanji.png" width="100">


## Instructions & Browser Limitations
- This should work on any browser with WebGL and WebRTC. It doesn't require any special hardware. iOS currently doesn't work right now, but it should work soon apparently. 
- Instructions:
  - Open the <a href="https://justingosses.github.io/AR_BusinessCard/">page</a> and click the window that asks for permission to use your camera.
  - Point the phone or laptop camera at the Y shaped icon on the business card. The 3D object should pop up. 

## Purpose
This is an attempt at using AR, augmented reality, on a business card. It is largely an experiment to figure out how the technolog works for browser based AR. 

## Open Source Libraries Used
To save space, I've not referenced or included full libaries Instead, I've only included the parts I'm using. You can find examples and licenses at the following repos. 
- <a href="https://github.com/jeromeetienne/AR.js">AR.js</a>
- <a href="https://threejs.org/">Three.js</a>
- <a href="https://aframe.io/">Aframe.js
- <a href="https://github.com/artoolkit/jsartoolkit5">Artoolkit.js</a>

## Data Source for Object
Taken from the meta data: This STL file is a topographic model of Gale Crater with 3x vertical exageration derived from data collected by the HRSC camera onboard the ESA's Mars Express mission. Gale Crater is currently being explored by NASA's Curiosity Rover. Printed at its default size (11cm across) this model cover an area approximately 200km across at a scale of 1.9 million to one ( 1 cm = 19 km ) Data Credit : K. Gwinner,J. Oberst,R. Jaumann, G.Neukum, ESA/DLR/FU Berlin
<a href="https://nasa3d.arc.nasa.gov/detail/gale-crater">Author/Origin: Doug Ellison / NASA-JPL</a>

## Preparation
Due to the size limits on individual files on github, I decimated the resolution of this stl file by 50%. 
