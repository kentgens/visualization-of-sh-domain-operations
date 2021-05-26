# Visualization of Linear Operations in the Spherical Harmonics Domain

This repository contains the companion MATLAB code for the 2021 publication "Visualization of Linear Operations in the Spherical Harmonics Domain" by Maximilian Kentgens and Peter Jax.

![Spherical Harmonics Linear Transform](sh_linear_operation.png)

The proposed method allows to visualize arbitrary linear operations in the spherical harmonics domain. Such operations comprise rotations, spatially selective filters, and many other modifications for various applications, or describe a MIMO system's response to an excitation.

Find the [paper pre-print on arXiv](https://arxiv.org/abs/2104.13069).

Cite as follows: TBA

For instance, the following MATLAB code:
```matlab
load('examples/example_adaptive_space_warping.mat','T');
visualizeTransformation(T);
```
creates the following plot:
![Example Visualization](examples/example_adaptive_space_warping.png)

Note that we use real-valued N3D-normalized spherical harmonics.

---

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
