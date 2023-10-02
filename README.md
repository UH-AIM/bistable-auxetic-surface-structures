# bistable-auxetic-surface-structures

Bistable auxetic surface structures (BASS) is a free and open source application for the generation of the fabrication patterns of morphing structures. BASS allows users to directly specify the shape of a deployed 3D surface, and generates a flat Kirigami pattern that when deployed, transforms to that specified surface. These patterns are 2D in nature and can be fabricated in a number of ways including laser cutting. 

The BASS application is based on the paper, “Bistable auxetic surface structures” by Tian Chen, Julian Panetta, Max Schaubelt and Mark Pauly: https://doi.org/10.1145/3450626.3459940

This repository contains the design algorithm (using Rhinoceros 3D + grasshopper interface, https://www.rhino3d.com/) to generate the cut pattern for user supplied input geometries. It has a number of pre-programmed surfaces for demonstration and fabrication.

# Dependencies
Boundary first flattening is necessary to pre-process custom input geometries by computing their conformal map: https://geometrycollective.github.io/boundary-first-flattening/

# Authors
[Tian Chen](https://aim.me.uh.edu/)<br/>
[Julian Panetta](https://julianpanetta.com/)<br/>
[Max Schaubelt]<br/>
[Mark Pauly](https://gcm.epfl.ch/)

# Citation

The algorithm is described in the paper (see .bib file in the repo):

>    **[Bistable auxetic surface structures]([https://arxiv.org/abs/1704.06873](https://doi.org/10.1145/3450626.3459940))**<br/>
>    Chen, Panetta, Schaubelt, Pauly<br/>
>    ACM Transactions on Graphics
