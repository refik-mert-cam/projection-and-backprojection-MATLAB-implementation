# projection-and-backprojection-MATLAB-implementation
This repository contains the term project for EE415 (Introduction to Biomedical Imaging) Course for
2019-2020 Fall Semester.

In this term project, some of the mathematical tools, which are widely used in x-ray imaging, will be implemented.
The theory can be applied to other imaging modalities that use non-diffracting sources.

**Line Integrals and Projections**

A line integral is the integral of a physical parameter of the object along a line. For the case of x-ray tomography,
the line integral is the total attenuation of an x-ray beam when the ray passes through the object along a straight line. 
A projection function can be formed, by combining a set of line integrals corresponding to multiple x-ray beams.
In parallel projection, the object is illuminated by parallel x-ray beams and line integrals for each case are combined to
form a projection. Calculation of projections for known attenuation coefficient distribution and incident beam intensity is 
defined as forward problem of x-ray imaging.

**Image Reconstruction**

Image reconstruction is the calculation of attenuation coefficient distribution using the projections. 
This process can also be named as the inverse problem. Depending on the nature of the problem, some filtering may be 
applied on the projection data before reconstruction.

In this repository, one can find the final report and projection and back-projection implementation codes with MATLAB Appdesigner platform.
You can simply download the repository and test it in your computer.

A Sample Screen View of GUI

![A Sample Screen View of GUI](https://github.com/refik-mert-cam/projection-and-backprojection-MATLAB-implementation/blob/master/screen%20of%20GUI.JPG)
