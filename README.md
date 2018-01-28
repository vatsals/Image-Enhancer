# Image-Enhancer

Image noise is random (not present in the object imaged) variation of brightness or color information in images, and is usually an aspect of electronic noise. It can be produced by the sensor and circuitry of a scanner or digital camera. Image noise can also originate in film grain and in the unavoidable shot noise of an ideal photon detector. Image noise is an undesirable by-product of image capture that adds spurious and extraneous information.
Salt & Pepper Noise:
Fat-tail distributed or "impulsive" noise is sometimes called salt-and-pepper noise or spike noise. An image containing salt-and-pepper noise will have dark pixels in bright regions and bright pixels in dark regions. This type of noise can be caused by analog-to-digital converter errors, bit errors in transmission, etc.It can be mostly eliminated by using dark frame subtraction, median filtering and interpolating around dark/bright pixels.Dead pixels in an LCD monitor produce a similar, but non-random, display.


OBJECTIVE: 

Analyzing the Noises in Images and the applying the suitable filter (we have used Median) for different mask sizes (odd and even) and find out which mask size fits best for a given input image.

Tools/stack used:
Matlab 11. 


Algorithm and Modules

Noises: All images consist of different types of noise in them, be it be any kind of images such as Medical Images, Satellite Images etc. The different types of noises are Gaussian noise, Salt & Pepper noise etc. 

Mask: Mask size is one of the key factor in smoothing the images using filters, we’ve figured out which is the best mask size for a particular image with respect to odd/even mask size.

Median Filter: Median filter is used to remove salt & pepper noise from images and smoothen them, since this type of noise is very common, so we have chosen Median filter in our project.

Psnr : This is the value which determines how good the image is, this is used for comparison between two images. Higher the PSNR value, more good the image is.
