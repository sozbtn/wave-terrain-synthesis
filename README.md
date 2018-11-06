This repository contains an implementation of Dynamic Wave Terrain Synthesis with 3D visulisation and unique extensions. 
It implemented as part of my [masters thesis](https://projekter.aau.dk/projekter/files/286179553/thesisReport.pdf) for the MSc. Sound and Music Computing at Aalborg University Copenhagen. 

Extensions include:
- Interfacing  and mapping with MPE compatible instruments for expressive control of the orbit
- Unique modulation parameters:
  - Dynamic surface modulation
  - Chaotic orbit modulation based on the Lorenz attractor
  - Velocity adaptive orbit modulation

Parametric control parameters include: X/Y terrain iterations, scaling, oscillators, orbit size, wrap/fold boundary behaviour, chaotic range/sensitivity, terrain modulation speed and direction. 


This work stems from the original 1982 paper for WTS: [audio synthesis by functions of two variables](http://www.aes.org/e-lib/browse.cfm?elib=3815)

The RISE package by Cycling74 is required to run the instrument.
