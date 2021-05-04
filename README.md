# Denoising_Img
This repository provides a way to deal with image that are noisy. You can learn how to Process the image , add noise to them and how to remove noise from an image. 

Image denoising is one of the important applications in Deep Learning. Processing images and try to do applications with them has been the interest of most programmers. 

Applications such as : 

1- Image compression/decompression. 
2- Image coloring.
3- Image denosing.
4- Image transformation. 
5- Image classifiaction. 
6- Image regression. 

In this repository, Image denoising will be explained !! in terms of noise and how to remove this noise. 
--------------------------------------------------------------------------------------------------------------------
Images processing has a wide range in deep learning. Many Deep learning algorithms such as Autoencoders, GAN Networks and many other algorithms are used to deal with images. 

Of of this application is, **Image Denoising**.

Noise exits in nature, different noise could affect the signals that we send to others. This noise might affect the quality of the signal. For example, we try to have a clear picture so we can see it. but because of some noise that are added to this picture, we cannot see it clearly. 

So, One of the important application in DL is to use some methods to remove this noise and then be able to see the image clealy.

One of the method of DL in such application is AUTOENCODERS. 
---------------------------------------------------------------------------------------------------------------------
1- Autoencoders: 

"Autoencoding" is a data compression algorithm where the compression and decompression functions are 1) data-specific, 2) lossy, and 3) learned automatically from examples rather than engineered by a human. 1) **Autoencoders are data-specific,** which means that they will only be able to compress data similar to what they have been trained on.2) **Autoencoders are lossy,** which means that the decompressed outputs will be degraded compared to the original inputs. 3) **Autoencoders are learned automatically from data examples,** which is a useful property: it means that it is easy to train specialized instances of the algorithm that will perform well on a specific type of input. It doesn't require any new engineering, just appropriate training data.

To build an autoencoder, you need three things: 
- an encoding function,
- a decoding function, 
- a distance function between the amount of information loss between the compressed representation of your data and the decompressed representation,




