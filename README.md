# FDM-Dynamical Friction
## Dynamical friction in Fuzzy Dark Matter (FDM) universe

FDMDynamicalFrictionForce is a new class of the package [galpy](https://www.galpy.org/), used to perform orbit integration of point masses that undergo dynamical friction in galactic potentials, assuming a FDM universe. This is subclass is derived from the classical dynamical friction class [ChandrasekharDynamicalFrictionForce](https://docs.galpy.org/en/v1.10.1/reference/potentialchandrasekhardynfric.html). 

Dynamical friction is a key physical process in galaxies responsible for the energy loss of massive objects such as black holes, galaxy satellites, or globular clusters (GCs). Since dynamical friction directly depends on the distribution of background particles within the galaxy, its behavior can serve as an indirect probe of dark matter properties. Among various alternative dark matter models, FDM has received increasing attention for addressing several shortcomings of the standard cold DM (CDM) paradigm. This alternative model leads to significant modifications of the dark matter density distribution on galactic scales. One of the distinctive dynamical features consist on a reduction or even a suppression of dynamical friction compared to the CDM case. See [Szpilfidel et al. +25]() for more details.

### Usage
This repository contains : 
* FuzzyDarkMatterDynamicalFriction.ipynb, a Jupyter notebook presenting the class FDMDynamicalFrictionForce and simple examples.
* infallingGCs.ipynb, a Jupyter notebook that generate number of GCs in a dark matter halo and calculate their infall time as a function of their initial energy-angular momentum state.
* DFefficiency.ipynb, a Jupyter notebook that draws a map of the efficiency of dynamical friction as a function of the halo-GC mass ratio and the mass of the FDM constituent particle. 

## Authors
If you use FDMDynamicalFrictionForce in a publication, please cite the code paper [Szpilfidel et al. +25]() and the galpy paper [Bovy +15](https://arxiv.org/abs/1412.3451).

* [Adrian Szpilfidel](mailto:adrian.szpilfidel@obspm.fr) -- Paris Sciences & Lettres (PSL), Observatoire de Paris, France
* [Pierre Boldrini](mailto:pierre.boldrini@obspm.fr) -- Paris Sciences & Lettres (PSL), Observatoire de Paris, France
* [Jo Bovy](mailto:boldrini@iap.fr) -- University of Toronto, Canada
