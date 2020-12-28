# Augmented Reality Business Card
One of the business cards I used to give out has an augmented reality marker on it. When you go to the website listed, <a href="https://justingosses.github.io/AR_BusinessCard/">https://justingosses.github.io/AR_BusinessCard/</a>, and let the browser access your camera, you'll see a 3D model of Jezero Crater, the landing site of the <a href="https://mars.nasa.gov/mars2020/">Persevarance Mars Rover</a>. 

In the past, a globe was seen and before that, Gale Crater, the landing site of the Curiosity Rover.

## Instructions & Browser Limitations
- This should work on any browser with WebGL and WebRTC. It doesn't require any special hardware. 
- Augmented Reality is still pretty young on the web and as browswers have adopted different standards this site has occasionally broke as the JavaScript libraries it uses has lagged how the browsers prefer to work by a little. iOS in particular tends to break as they like doing their own thing. 
- Instructions:
  - Webpage is live at <a href="https://justingosses.github.io/AR_BusinessCard/">https://justingosses.github.io/AR_BusinessCard/</a>
  - Open the <a href="https://justingosses.github.io/AR_BusinessCard/">page</a> and click the window that asks for permission to use your camera.
  - Point the phone or laptop camera at the Y shaped icon on the business card. The 3D object should pop up. 
- This <a href="https://twitter.com/JustinGosses/status/848636777028096001">Video</a> on twitter shows the first version in action with a different 3D model . 

## Current model & marker
- This <a href="https://github.com/JustinGOSSES/AR_BusinessCard/blob/main/assets/asset.gltf">model</a> was created from <a href="https://sketchfab.com/3d-models/jezero-crater-ctx-dtm-5e1c1400fbc844979cebc894889088a2">this gltf model</a> on sketchfab by <a href="https://martinjpratt.wordpress.com/
">Martin Pratt</a>. I believe it may have been generated from an image & DEM from <a href="https://www.uahirise.org/results.php?keyword=Jezero&order=release_date&submit=Search">HiRise</a>, but I'm not 100% sure. 
- The <a href="https://github.com/JustinGOSSES/AR_BusinessCard/blob/main/assets/marker.patt">marker</a> is a standard Kanji marker.

## How the site was created.
The original version of the site leveraged several JavaScript libraries and wrote the code to combine them together. 
- <a href="https://github.com/jeromeetienne/AR.js">AR.js</a>
- <a href="https://threejs.org/">Three.js</a>
- <a href="https://aframe.io/">Aframe.js
- <a href="https://github.com/artoolkit/jsartoolkit5">Artoolkit.js</a>

<b>However, now building this type of thing is much simplier as you can leverage <a href="https://ar-js-org.github.io/studio/pages/marker/index.html">AR.js Studio</a>, which is a front-end webpage that takes in your preferred marker and 3D model and outputs a fully built webpage for you.</b>

The only slightly confusing thing about this is that when I tried to use my old kanji.png file to create a marker, it added an extra black border, which then caused the JavaScript to not be able to recognize the marker correctly. I was able to solve this problem by editing the Kanji PNG file I had to take out the black border. The tool then adds a black border. The result can be recognized and is identical to the business cards I have already distributed. 


# Other

Screenshot of current model of Jezero Crater in Augmented Reality via marker on business card.
<img src="https://github.com/JustinGOSSES/AR_BusinessCard/blob/main/assets/Jezero_Crater_ar_screenshot.png" width="400">

Previous AR Images in Action
<img src="https://github.com/JustinGOSSES/AR_BusinessCard/blob/main/development_tests_and_unused_currently_assets/images/Screen%20Shot%202017-04-01%20at%209.39.35%20PM.png" width="400">

Icon that is AR Target 
<img src="https://stemkoski.github.io/AR-Examples/markers/kanji.png" width="100">

Previous model used was a 3D image of Gale Crater created by <a href="https://nasa3d.arc.nasa.gov/detail/gale-crater">Author/Origin: Doug Ellison / NASA-JPL</a>
