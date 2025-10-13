---
layout: page
title: My work
subtitle: Some of My Favorite Projects
---

### Graph Neural Networks for Rainfall Variablity 

I am developing a Graph Neural Network model that uses historical rainfall data from a few locations in India to predict rainfall variability.
I am using ISRO's GSMaP dataset for the task at hand. The model allows us to:

- Predict rainfall stability for a given year based on previous year 
- Plan water management for floods and droughts well in advance
- Identify optimal locations to build raingauge stations with minimal cost

<img src="/assets/img/rainfall_variability.png" 
     alt="Rainfall Variability in India" 
     style="display: block; margin: 0 auto; width: 80%; max-width: 500px;">

In the above picture, we can see the variation of rainfall across mainland India. By identify the various zones of variances, models can be trained better to yield better results across the country for minimal training. The <a href="https://github.com/Prad-R/rainfall_stability_gnn"> GitHub Repository</a>  is linked.

<hr style="border: 0; height: 5px; background-color: #ccc; margin: 50px 0;">

### Adaptive Sampling Approach for Voronoi Diagrams of 3D Spheres

In this project, I came up with a radial projection based adaptive sampling algorithm that allows an computation of Voronoi diagrams for 3D spheres. This would be useful for optimal sensor location and protein studies. Benchmarks on the Voronota protein dataset have been run and have given accurate results.

<img src="/assets/img/Voronoi.png" 
     alt="Adaptive Sampling of 3D Spheres" 
     style="display: block; margin: 0 auto; width: 100%; max-width: 500px;">

The image shows the sequential results of implementing the algorithm on 4 arbitrary spheres in space. The same algorithm is extended with no changes for an arbitrary number of spheres.

<hr style="border: 0; height: 5px; background-color: #ccc; margin: 50px 0;">

### DiceForge: A PRNG in C++

DiceForge is a C++ library for **Pseudo Random Number Generation (PRNG)**. It provides functionality similar to that of the python standard library _random_. It implements several non-standard algorithms to improve the efficiency over standard PRNGs.

<img src="/assets/img/DiceForge.png" 
     alt="DiceForge vs Standard PRNGs" 
     style="display: block; margin: 0 auto; width: 100%; max-width: 500px;">

The comparison between our best PRNG, the XORShift 64 and other standard PRNGs is given in the graph above. We can see that our PRNG is about **9x faster than C++'s own PRNG**. The <a href="https://github.com/Mathematics-Club-IIT-Madras/DiceForge">GitHub Repository</a> containing the library is linked.

<hr style="border: 0; height: 5px; background-color: #ccc; margin: 50px 0;">

### DSMC for Simulating Rarefied Gas Flow

SPARTA (Stochastic PArallel Rarefied-gas Time-accurate Analyzer) is a parallel Direct Simuation Monte Carlo (DSMC) solver for performing simulations of low-density gases in 2D or 3D. SPARTA was primarily developed at Sandia National Laboratories, a US Department of Energy (DOE) laboratory. I used SPARTA to simulate 2D flow around cylinders in Martian atmosphere after curating a <a href="https://github.com/Prad-R/SRFP_2024_Project">repository on Martian atmospheric data</a>. 

<img src="/assets/img/SPARTA.png" 
     alt="DSMC Simulation" 
     style="display: block; margin: 0 auto; width: 100%; max-width: 500px;">

We can see a ray-traced image of a snapshot of the simulation above.