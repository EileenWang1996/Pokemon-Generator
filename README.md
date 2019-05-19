# Generating Pokemon with wGANs. 
Generative adversial networks (GANs) are a type of artificial intelligence algorithm where two models are trained simultaneously. The algorithm usually involves two networks, the generator and the discriminator competing against each other in a zero-sum game framework. The main purpose of GANs is to learn the distribution of the training data in order to create new features and generate high-quality images.

This repository contains an implementation of the Wasserstein Generative Adversial Network (wGAN) which aims to generate new pokemon images from a training set of 919 images. The algorithm was trained on Google Colab's free GPU for 1,100 epochs (which took about a day to run). 

To run the code: 
 - Open the code in Google Colab or copy and paste into Google Colab.
 - Make sure that your notebook settings under 'Edit' are set to Python 3 for 'Runtime type' and GPU for 'Hardware accelerator.
 - Upload your favourite Pokemon dataset under the 'Files' tab on the left hand side. 
 - Simply run all the cells and watch the model train! 
 
## Examples of output: 
Output after 100 epochs: 
<p align="center">
  <img width = 400, height = 400 src="https://user-images.githubusercontent.com/35329219/57977660-5be8f480-7a40-11e9-9305-f3195883394a.jpg">
</p>

Output after 550 epochs: 
<p align="center">
  <img width = 400, height = 400 src="https://user-images.githubusercontent.com/35329219/57977668-85098500-7a40-11e9-946b-91d71974907f.jpg">
</p>

Output after 1000 epochs: 
<p align="center">
  <img width = 400, height = 400 src="https://user-images.githubusercontent.com/35329219/57977669-9b174580-7a40-11e9-9be4-b91de06c429e.jpg">
</p>
