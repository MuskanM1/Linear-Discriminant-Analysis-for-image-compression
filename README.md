# Linear Discriminant Analysis for Image compression

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Summary](#Summary)

## General info
This project takes in input grayscale image and outputs LDA vectors for that image that helps in reducing dimensionality, thereby, compressing the image.

## Technologies
Project is created with:
* Software: MATLAB R2018b, Xilinx ISE
* Language: MATLAB, Verilog
* Hardware: FPGA

## Summary
This project is implmented in Verilog and MATLAB, that takes in input grayscale image and outputs LDA vectors for that image that helps in reducing dimensionality, thereby, compressing the image. Linear Discriminant Analysis (LDA) had been a popular method for extracting features which preserve class separability. LDA works better with large dataset having multiple classes. Class separability is an important factor while DR. The projection matrix of LDA
is usually obtained by simultaneously maximizing the between-class covarince and minimizing the with-in class covariance. However, the computation of LDA involves dense matrices eigen-decomposition which is
computationally expensive both in time and memory requirement when the number of samples and the number of features are large which is not the case here because here the number of features are very small. We
can easily project data-points corresponds to features into lesser dimeson of space using LDA. It is widely used for image compression, SR and PR. ILDA, which
is extended version of LDA also helps us to add more feature in classes without recalculating.
	
