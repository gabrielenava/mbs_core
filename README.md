# matlab-multi-body-sim

Matlab simulator of dynamics, kinematics and control of rigid multi-body systems. The simulator is based on the [iDyntree](https://github.com/robotology/idyntree) library.

## Dependencies

- This repository requires [iDyntree](https://github.com/robotology/idyntree) (and its dependencies) and [Matlab](https://it.mathworks.com/products/matlab.html) to be installed on your machine. When compiling `iDyntree`, it is required to set the option `IDYNTREE_USES_MATLAB` to `ON`. In order to use the `wrappers`, add to the Matlab path the `path/where/the/iDyntree/mex/file/is`. 

- To use the [wrappers associated with the idyntree visualizer](https://github.com/gabrielenava/matlab-multi-body-sim/blob/master/idyntree-high-level-wrappers/idyn_initializeVisualizer.m), it is also required to install the `Irrlicht` library (see also this [README](idyntree-high-level-wrappers#visualizer-class)). To install the library on Ubuntu, just run on a terminal:

```
sudo apt-get install libirrlicht-dev
```

- Optional dependencies on other software (e.g. [whole-body-controllers](https://github.com/robotology/whole-body-controllers)) are listed inside the [external](external) folder.

## Structure of the repo

- **external**: external (optional) sources. [[README]](external/README.md)

- **idyntree-high-level-wrappers**: the available `iDyntree` methods wrapped in Matlab functions. [[README]](idyntree-high-level-wrappers/README.md)

- **matlab-simulator**: the matlab simulator of rigid multi-body dynamics and kinematics. [[README]](matlab-simulator/README.md)

- **utility-functions**: a library of utility functions. [[README]](utility-functions/README.md)

## Installation and usage

**If all the required dependencies are correctly installed and configured**, it is just necessary to clone this repository on your pc. 

## Mantainer

Gabriele Nava ([@gabrielenava](https://github.com/gabrielenava)).
