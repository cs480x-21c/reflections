
Biomedical imaging visualization is a fascinating and growing area. There are two general data types: Volume and surface.
The volume can be described as a 3D matrix in which all the elements have different pixel intensity.
The surface is constructed by many triangles in which each node connect to three other nodes.
The brain image visualization is a growing area, and this is also related to my internship 
(I am working on the skull surface generation from the Pseudo-CT and MRI T1, T2 image.). 
One of the brain
segmentation and visualization tool is FreeSurfer which is developed in Havard University. https://surfer.nmr.mgh.harvard.edu/

The FreeView visualization tool can visualize segmented volumes and surfaces. After the segmentation, the brain will be labelled with a different colour. 
Each segmented volume has acorresponding surface. After loading the surfaces and the volume into the app, users can rotate them in a 3D graph. Meanwhile, 
the cross-section over X, Y, Z are displayed.
The user can use the slider on the 3D graph to change the X, Y, and Z cross-section. By using the zooming in function, users can view more detail of the
volume and it also display all the related information of the section where users put their mouse on.

This visualization is super powerful in that it allows user to control all the property of all the surfaces and volumes such as colour, layer, and transparency.
However, this tool also has a long way to go. Users sometimes need use terminal to control the visualization if they want more advances data processing and visualization, such as
surface correction and editing.


![FreeSurferDemo](https://user-images.githubusercontent.com/59973823/107198604-49a4ac00-69c3-11eb-884c-122285e17c12.png)


