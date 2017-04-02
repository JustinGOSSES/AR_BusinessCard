# An Augmented Reality Object of Gale Crater on Mars Triggered By Icon on Backside of Business Card
AR Images in Action
<img src="https://github.com/JustinGOSSES/AR_BusinessCard/blob/master/images/Screen%20Shot%202017-04-01%20at%209.39.35%20PM.png" width="400">
Icon that is AR Target
<img src="https://github.com/JustinGOSSES/AR_BusinessCard/blob/master/images/kanji.png" width="100">

## Instructions & Browser Limitations
- This should work on any browser with WebGL and WebRTC. It doesn't require any special hardware. iOS currently doesn't work right now, but it should work soon apparently. 
- Instructions:
  - Webpage is live at <a href="https://justingosses.github.io/AR_BusinessCard/">https://justingosses.github.io/AR_BusinessCard/</a>
  - Open the <a href="https://justingosses.github.io/AR_BusinessCard/">page</a> and click the window that asks for permission to use your camera.
  - Point the phone or laptop camera at the Y shaped icon on the business card. The 3D object should pop up. 
- <a href="https://twitter.com/JustinGosses/status/848636777028096001">Video</a> on twitter. 

## Purpose
This is an attempt at using AR, augmented reality, on a business card. It is largely an experiment to figure out how the technolog works for browser based AR. 

## Open Source Libraries Used
To save space, I've not referenced or included full libaries Instead, I've only included the parts I'm using. You can find examples and licenses at the following repos. 
- <a href="https://github.com/jeromeetienne/AR.js">AR.js</a>
- <a href="https://threejs.org/">Three.js</a>
- <a href="https://aframe.io/">Aframe.js
- <a href="https://github.com/artoolkit/jsartoolkit5">Artoolkit.js</a>

## Data Source for Object
Information modified slightly from the original object meta data: The original STL file is a topographic model of Gale Crater with 3x vertical exageration derived from data collected by the HRSC camera onboard the ESA's Mars Express mission. The augmented reality version has vertical exaggerated 4x.  Gale Crater is currently being explored by NASA's Curiosity Rover. This model cover an area approximately 200km across. Data Credit : K. Gwinner,J. Oberst,R. Jaumann, G.Neukum, ESA/DLR/FU Berlin

<a href="https://nasa3d.arc.nasa.gov/detail/gale-crater">Author/Origin: Doug Ellison / NASA-JPL</a>

## Preparation
Due to the size limits on individual files on github, I decimated the resolution of this stl file by 50%. 
