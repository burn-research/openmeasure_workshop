# Workshop on OpenMEASURE

[OpenMEASURE](https://github.com/albertoprocacci/OpenMEASURE) is a bunch of pyhton libraries bundled in a pypi [package](https://pypi.org/project/OpenMEASURE/), meaning that it can be easily installed using pip. 
For now, it contains 4 modules but we will focus on the module for building Reduced-Order Models (ROMs). 

The ROMs are built using Proper Orthogonal Decomposition (POD) and Gaussian Process Regression (GPR). In OpenMEASURE, we use the [GPyTorch](https://gpytorch.ai/) package to build the GPR model. 
GPyTorch is built on top of [PyTorch](https://pytorch.org/), which is attractive because it allows for GPU accelerations and other cool features (eventually).

The first exercise is a toy problem to illustrate the idea behind the GPR-based ROM. 
The second exercise is an example on how to build a ROM of the ULB furnace. The data is published on [Zenodo](https://doi.org/10.5281/zenodo.7786311).
