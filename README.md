# Gaussian-Deblur-OpenMP
Programs implementing open multi-processing to 'speed up' the Gaussian Deblur method used in MRI machines

This program includes 4 separate files, 2 of which implement OpenMP and 2 of which undergo the normal sequential process for a Gaussian Deblur. 
The OpenMP version is roughly 16x as fast as the sequential speedup, showcasing the benefits of the OpenMP style.
These programs are run primarily to demonstrate OpenMP, and not to actually perform the deblur. They were originally run on the UCLA servers that
allowed for the comparison of speeds. 
