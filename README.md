# BEM-3D-Python
3D Python boundary element method solver

This is a boundary element solver library devloped and maintained by the Biofluids Research Group, Department of Mechanical Engineering and Mechanics, P.C. Rossin College of Engineering and Applied Science, Lehigh University.

Other related projects:

* [kmoored/BEM-2D-Matlab](https://github.com/kmoored/BEM-2D-Matlab)
* [wcs211/BEM-2D-Python](https://github.com/wcs211/BEM-2D-Python)

## Getting Started
* Edit the simulation input file [input_parameters.py](https://github.com/wcs211/BEM-3D-Python/blob/master/input_parameters.py)
* Execuite the file [bem3d.py](https://github.com/wcs211/BEM-2D-Python/blob/BEM2DFSI/bem2d.py) at the terminal prompt:

	$ python bem3d.py

## Features

* Modular code structure allows easier implementation of new features
* Saves time-step data for post-processing
* Start from a previous data save


## Future Features
The following features have planned implementation in the code:

* Remove dependency on Octave/MATLAB
* Fluid Structure Interaction (FSI)
* Implicit and Explicit Kutta condition enforcement
* Multiple body interactions
* Vortex Particle wake representation
* Lumped wake representation
* Equations of motion solver
* Boundary layer solver for skin friction estimation
* Quadtree collision detection (fencing scheme)
* Fast Multipole solver
* Parallel processing
* GPGPU processing
