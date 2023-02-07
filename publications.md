---
layout: page
title: Publications
permalink: /publications/
---

# Journal articles  


#### 2022  

[On the formulation and implementation of extrinsic cohesive zone models with contact](https://www.sciencedirect.com/science/article/pii/S0045782522005369)  
N.A. Collins-Craft, F. Bourrier, V. Acary, _Computer Methods in Applied Mechanics and Engineering_, Volume 400, page 115545, DOI: [10.1016/j.cma.2022.115545](10.1016/j.cma.2022.115545)  
HAL link: [https://hal.science/hal-03371667](https://hal.science/hal-03371667)  

#### 2020  

[A Cosserat Breakage Mechanics model for brittle granular media](https://linkinghub.elsevier.com/retrieve/pii/S0022509620302106)  
N.A. Collins-Craft, I. Stefanou, J. Sulem, I. Einav, _Journal of the Mechanics and Physics of Solids_, 141, page 103975, DOI: [10.1016/j.jmps.2020.103975](10.1016/j.jmps.2020.103975)  
HAL link: [https://hal.science/hal-03120686v1](https://hal.science/hal-03120686v1)  


# Software  

#### On the formulation and implementation of extrinsic cohesive zone models with contact  

Codes that accompany the paper of the same name, written in Python to interface with TRIPOP's in-house non-smooth solver [Siconos](https://nonsmooth.gricad-pages.univ-grenoble-alpes.fr/siconos/).  
Software Heritage link: [https://archive.softwareheritage.org/swh:1:dir:9e7bfbdad8111df26f6a13f2c47a0258c47d0528;origin=https://github.com/nickcollins-craft/On-the-formulation-and-implementation-of-extrinsic-cohesive-zone-models-with-contact;visit=swh:1:snp:47b52930b84c595623e9b13f031afcc474ff8b6b;anchor=swh:1:rev:5d5de7e9a1f477585bc177677ffeef8881b20473](https://archive.softwareheritage.org/swh:1:dir:9e7bfbdad8111df26f6a13f2c47a0258c47d0528;origin=https://github.com/nickcollins-craft/On-the-formulation-and-implementation-of-extrinsic-cohesive-zone-models-with-contact;visit=swh:1:snp:47b52930b84c595623e9b13f031afcc474ff8b6b;anchor=swh:1:rev:5d5de7e9a1f477585bc177677ffeef8881b20473)  
Zenodo link: [https://zenodo.org/record/6939392#.Y-Jgy6fMI5k](https://zenodo.org/record/6939392#.Y-Jgy6fMI5k)  

#### Julia constitutive model integration  

A Julia translation of the codes used to perform single material point integration and linear stability analyses in the Cosserat Breakage Mechanics paper, which were originally a mix of Python and Mathematica. As Julia is still a fast-evolving language, and I wrote this repository before becoming aware of good principles of good replicability, I cannot guarantee that the suite will work out-of-the-box, although if it doesn't, it shouldn't be too far away, and I am happy to help in making it work for anyone interested in using it for science.  
Github link: [https://github.com/nickcollins-craft/julia_constitutive_model_integration](https://github.com/nickcollins-craft/julia_constitutive_model_integration)  

# Data sets  

#### On the formulation and implementation of extrinsic cohesive zone models with contact  

The data set accompanying the paper (and codes) of the same name. This includes the input meshes used in the finite element analyses, the outputs of the simulations in Python pickles and .vtk files, and certain large images used to demonstrate the mesh (which are used as inputs in some of the plotting codes contained in the codebase).  
Zenodo link: [https://zenodo.org/record/6939154#.Y-Jj16fMI5k](https://zenodo.org/record/6939154#.Y-Jj16fMI5k)  
