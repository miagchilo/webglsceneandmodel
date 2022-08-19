# webglsceneandmodel

3D model of a car in dark scene with different light and moving boxes using react-three-fiber https://docs.pmnd.rs/react-three-fiber/getting-started/introduction and react-three-drei https://github.com/pmndrs/drei#readme

preview: https://webglsceneandmodel.vercel.app/

Model Information:
* title:	Toyota AE86 Sprinter Trueno Zenki
* source:	https://sketchfab.com/3d-models/toyota-ae86-sprinter-trueno-zenki-a5737bf3cc9b4179a6e5ebe173ff70d9
* author:	Martin Trafas (https://sketchfab.com/Bexxie)

Model License:
* license type:	CC-BY-4.0 (http://creativecommons.org/licenses/by/4.0/)
* requirements:	Author must be credited. Commercial use is allowed.

I decided to download a good model from the website, since blender is still complicated for me ( however i will practise), 
I did not change the model because i wanted it to be detailed since i was planning not to have a lot of stuff in the web page. 



I used the postprocesing in this project. Post-processing is a widely used approach to implement such effects. First, the scene is rendered to a render target which represents a buffer in the video card's memory. In the next step one or more post-processing passes apply filters and effects to the image buffer before it is eventually rendered to the screen.The Chromatic Aberration effect was implimented in the project, it mimics the effect a real-world camera produces when its lens fails to join all colors to the same point. Also bloom effect was added.( https://threejs.org/examples/?q=postproc#webgl_postprocessing_unreal_bloom ) The Bloom effect makes bright areas in your image glow. To do this, it creates fringes of light that extend from bright areas in your image. This simulates the effect a real-world camera gives when light overwhelms the lens. 

In terms of perfermance I admit I have to work on it. 
