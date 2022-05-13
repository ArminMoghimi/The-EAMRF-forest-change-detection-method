# The edge-aware MRF (EAMRF) forest change detection method
This repository contains the closed MATLAB code of the EAMRF forest change detection method along with some samples of datasets used in our paper (Mohsenifar, A., Mohammadzadeh, A., Moghimi, A. and Salehi, B., 2021, A Novel Unsupervised Forest Change Detection Method Based on The Integration of a Multiresolution Singular Value Decomposition Fusion and an Edge-Aware Markov Random Field Algorithm. International Journal of Remote Sensing, https://doi.org/10.1080/01431161.2021.1995075) to detect changes in forested areas.
Required information about the code has also been elaborated in a notepad file named README.txt in a folder in which the code exists.
# Overview
The source code has two main steps. In the first step, an integrated difference image is achieved by fusing two difference images computed based on the spectral (reflectance) data (Ds) and vegetation indices (Dv). In this case, it's worth mentioning that any of the vegetation indices must be normalized between 0 and 1 before they are used to compute the vegetation indices-based difference image (Dv). In the second step, the EAMRF model is applied to the fused difference image in order to produce a binary forest change map.

Being completed ...
