# Seismic elastic parameter estimation using Bayesian framework

## Introduction

<p></p>
The goal of this project is to use reflection seismic data and well logging data to estimate underground elastic parameters that are used for finding potential oil and gas reservoirs. By wrangling and analyzing well logging data in R, the missing well data can be estimated using Bayesian framework. And the Bayesian prior information can be obtained by using interpolation method. The Bayesian model is also derived. Finally, the user graphic interface for elastic parameters estimation is implemented in Python.

<img src="usr/fig1.png" alt="Figure 1" width="700"/>

## Elastic Parameters
Based on Bayesian inference theory, the elastic parameters that are used for estimation are the sonic wave velocity Vp and the shear wave velocity Vs. The ratio between the sonic wave velocity and the shear wave velocity is sensitive to the reservoir characterization.

<img src="usr/fig2.png" alt="Figure 2" width="700"/>

## Graphic User Interface (GUI) Development
The graphic user interface is developed using Python for easy data and computation management. The kernel algorithms are implemented by Fortran, C++ and shell scripts with efficient multi-level parallelization (OpenMP + MPI) and optimization on CPU multiprocessor platforms.

https://user-images.githubusercontent.com/110936252/184060747-2cb085bb-41d3-49f8-8b85-0d1e5b114db1.mov





