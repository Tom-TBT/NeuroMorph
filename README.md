### NeuroMorph Toolkit

Download the lastest version of the Blender add-ons from the **NeuroMorph_Toolkit** folder.

Example meshes, objects, and image files for use with the add-ons are available in the **NeuroMorph_Samples** folder.

### Documentation
[**Blender Wiki**](http://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts/Neuro_tool)

[**Video Tutorial**](https://www.youtube.com/watch?v=CVkcYjWgceM&vq=hd720)  
(Installation Note: In the most recent versions of Blender, the panel tools are found in the "Misc" tab on the far left.)

### Description
NeuroMorph is a toolset designed to import, analyze, and visualize mesh models in [Blender](https://www.blender.org/). It has been designed specifically for the morphological analysis of 3D objects derived from serial electron microscopy images of brain tissue, although much of its functionality can be applied to any 3D mesh.  These models can be generated by software that allows the images to be segmented so that 3D objects can be built.  These objects can be generated by any 3D image segmentation software, such as [ilastik](http://ilastik.org/) or [Fiji](http://fiji.sc/Fiji).

If you find our tool useful, please cite our [paper](http://link.springer.com/article/10.1007%2Fs12021-014-9242-5):  
A. Jorstad, B. Nigro, C. Cali, M. Wawrzyniak, P. Fua, G. Knott.  "NeuroMorph: A Toolset for the Morphometric Analysis and Visualization of 3D Models Derived from Electron Microscopy Image Stacks." Neuroinformatics, 2014.

### Measuring Synapse-Vesicle Density (*new*)
Given a 3D mesh representation of a synapse and balls marking the synaptic vesicles, this plug-in computes and outputs the closest distance from each vesicle to the synapse.  See the **NeuroMorph_Density_Measurements** folder.
