### Photorealistic Rendering using pbrt
<p align="justify">
A high quality augmented reality still image was created by combining a real-world photograph with an image obtained using a photo-realistic renderer, while ensuring that the lighting, reﬂections and shadows in the rendered image were consistent with the viewer’s expectation of the real scene.
</p>

<br>

<div align="center">
<img src="https://github.com/sukriti27/photorealistic-rendering-pbrt/blob/master/Original.jpg" width="300" height="300" /> &nbsp; &nbsp; &nbsp; <img src="https://github.com/sukriti27/photorealistic-rendering-pbrt/blob/master/Composited.jpg" width="300" height="300" />
</div>

<br>

<p align="justify">
A real-world image was captured using a phone camera. The surface of the cardboard box and the wooden plane were photographed separately as they would be inﬂuencing the appearance of the rendered objects. A 3D model of a human skull was chosen from an online 3D model library. A texture was chosen for the human skull. The real-world scene was modelled using the freely available 3D modelling software Blender. Texture was added to the box, plane and skull. Appropriate colours were deﬁned for the two walls. Mirror was selected as the material for the cuboid placed below the human skull.
</p>

<br>

<div align="center">
<img src="https://github.com/sukriti27/photorealistic-rendering-pbrt/blob/master/BlenderModelCameraView.png" width="200" height="200" /> &nbsp; <img src="https://github.com/sukriti27/photorealistic-rendering-pbrt/blob/master/BlenderModelPerspective.png" width="286" height="200" /> &nbsp; <img src="https://github.com/sukriti27/photorealistic-rendering-pbrt/blob/master/PBRTRendered.jpg" width="200" height="200" />
</div>

<br>

<p align="justify">
Blender exporter for PBRT was used to obtain the PBRT input ﬁle for the modelled scene. The input ﬁle was modiﬁed and the synthetic scene was rendered. Gimp was used to composite the virtual objects with the real-world photograph.
</p>

