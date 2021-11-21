# Generative-Adversarial-Networks(GAN)

This repository contains material about Generative-Adversarial-Networks(GAN) with keras and Tensorflow. It consists of notebooks as well as python file for various deep learning topics. In most cases, the notebooks lead you through implementing models such as Vinalia GAN, DCGAN, cGAN,Pix2Pix, CycleGAN, SRGAN and others.


# `GAN`
GANs are a hot topic of research today in the field of deep learning. Popularity has soared with this architecture style, with its ability to produce generative models that are typically hard to learn. There are a number of advantages to using this architecture: it generalizes with limited data, conceives new scenes from small datasets, and makes simulated data look more realistic.

The GAN composes of three different names such as Generative, Adversarial and Network. Generative means we will generate some probability distribution which becomes close to the original data that we want to approximate. Adversarial means conflict or opposition. So, there will be two networks that we call them discriminator and generator. So, these two neutral networks fight against each other in order to learn the probability distribution function

## `Generative models over the years`
+Based on maximum likelihood we can compare the models
<p align="center">
  <img src="static/GAN.png"><br/>
  <i>GAN over the years.</i>
</p>

 
# Fully Visible Belief Networks
They use the chain rule of probability to decompose the probability
distribution over a vector, into a product over each of the members of the vector.
The biggest drawback with FVBNs is that the rate of generating samples is very slow. Every time you want to generate a new sample, you will have to run the model again. This cannot be done in parallel.
# Models based on change of variables (Non-linear ICA)
Such models begin with a simple distribution like a Gaussian and use a non-linear function to transform the distribution to another space. So, if you want to generate 5000 pixels, you need to have 5000 latent variables.
# Variational Autoencoder
The way Variational autoencoders work is by marginalizing out the random variable z from the density function log p(x). Another disadvantage is that the samples generated are of relatively low quality. (blirry)
# Boltzmann Machines
The drawback is that these methods, especially the Markov Chain Monte Carlo methods, don’t perform well in high dimensional spaces. 
# Generative Adversarial Networks
GANs were designed to overcome many of the drawbacks stated in the above models. As opposed to Fully Visible Belief Networks, GANs use a latent code, and can generate samples in parallel. Unlike Variational Autoencoders, GANs are asymptotically consistent. Also, GANs do not require Markov chains, which is an advantage over Boltzmann Machines. Finally, GANs are often highly regarded as producing the best samples.
# Scaling GANs
The initial GANs themselves don’t really scale well to large applications. To overcome this, the Deep Convolution GAN architecture was introduced by Radfort at al. Although originally, GANs were already deep and convolutional, DCGANs stress on having more convolutional layers, and additionally use techniques such as batch normalization. Batch normalization is applied to every layer except the last layer of the generator in order to make the learning process more stable.


### GAN applications into the following areas:
+ Generate Examples for Image Datasets
+ Semantic-Image-to-Photo Translation
+ Generate Photographs of Human Faces
+ Generate Realistic Photographs
+ Face Frontal View Generation
+ Generate Cartoon Characters
+ Image-to-Image Translation
+ Text-to-Image Translation
+ Generate New Human Poses
+ 3D Object Generation
+ Clothing Translation
+ Photograph Editing
+ Video Prediction
+ Photos to Emojis
+ Photo Inpainting
+ Super Resolution
+ Photo Blending
+ Face Aging



## Author
+ Name: Md. Shahin Alom
+ 𝐏𝐡𝐨𝐧𝐞:   (+880) 1704801703(Whatsapp)
+ 𝘔𝘢𝘪𝘭:     ashahin200@gmail.com
+ LinkedIn: http://linkedin.com/in/ashahin200