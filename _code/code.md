---
permalink: /code/
title: "Code"
---

You can find below the scripts developed in my research projects.

# IP3R-dependant Ca2+ signaling in fine astrocytic processes
![Summary of Denizot et al 2019 Model](/images/code/model-denizot2019.png)

This model has been developed and presented in [Denizot et al., PLOS Computational Biology, 2019](https://journals.plos.org/ploscompbiol/article/metrics?id=10.1371/journal.pcbi.1006795#discussedHeader). 
The code can be found [here](https://senselab.med.yale.edu/modeldb/ShowModel?model=247694#tabs-1). 4 different implementations of the model are available: 
- ODEs: deterministic, well-mixed implementation of the model with [XPPAUT software](http://www.math.pitt.edu/~bard/xpp/xpp.html)
- Gillespie: stochastic, well-mixed implementation of the model in Python
- Particle-based: stochastic, spatial, in 2 spatial dimensions, implemented in C language
- Voxel-based: stochastic, spatial, in 3 spatial dimensions, implented in python, using [STEPS software](http://steps.sourceforge.net/STEPS/default.php)

# Simulations in idealistic 3D geometries of fine processes based on recent super-resolution microscopy data 
![Summary of Denizot et al 2021](/images/code/idealizedPAP-summary.png)

 Simulations published in [Denizot et al., bioRxiv, 2021](https://www.biorxiv.org/content/10.1101/2021.02.24.432635v4). Reaction-diffusion simulations were performed in 3D meshes that were designed from the latest data available from super-resolution microscopy on astrocytes from [Arizono et al., Nature Communications, 2020](https://www.nature.com/articles/s41467-020-15648-4). The high spatial resolution of this model allows to propose plausible mechanisms by which astrocyte morphology at the nanoscale, notably shaft width, can influence local calcium dynamics and thus affect specialized neuron-astrocyte communication. 
 The simulation code and 3D meshes designed in this study can be downloaded [here](https://senselab.med.yale.edu/ModelDB/showmodel.cshtml?model=266928#tabs-1).
 
# Analysis of geometrical properties of 3D meshes
 Scripts implemented in python to quantify geometrical properties of 3D meshes using [Blender software](https://www.blender.org/). They have been used in [Denizot et al., bioRxiv, 2022](https://www.biorxiv.org/content/10.1101/2022.02.28.482292v2) and are available [here](https://gitfront.io/r/user-8990396/a5089704537f197d16b59d40ede3859b9d43f959/PAP-ER/tree/GeometryAnalysis/).
 
# Generation of realistic perisynaptic astrocytic processes meshes with various endoplasmic reticulum distributions and constant shape
![Automated PAP mesh generation 2022](/images/code/PAP-ER-meshgen.png)

 Scripts implemented in python to generate 3D meshes of perisynaptic astrocytic processes with various ER distributions and constant shape using [Blender software](https://www.blender.org/). The code and resulting meshes are available [here](https://gitfront.io/r/user-8990396/a5089704537f197d16b59d40ede3859b9d43f959/PAP-ER/tree/PAPMeshGeneration/) and were used in [Denizot et al., bioRxiv, 2022](https://www.biorxiv.org/content/10.1101/2022.02.28.482292v2).
  
