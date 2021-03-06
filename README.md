# ESRGAN-pytorch

This repository implements a deep-running model for super resolution.
 Super resolution allows you to pass low resolution images to CNN and restore them to high resolution. 
 We refer to the following article.  
 [ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks](https://arxiv.org/abs/1809.00219)  
 
 ## architecture
 [Overall Architecture]
 ![ESRGAN architecture](./image/architecture.PNG)  
 [Basic block]  
 ![BasicBlock](./image/basicBlock.PNG)
 
 ## Sample
From the top is a low resolution image, a restored high resolution image, and ground truth.  

The sample is still being imported during the training, and the completeness is low.  

 ![Sample](./image/sample1.png)
 ![Sample](./image/sample2.png)
 ![Sample](./image/sample3.png)
 
 ## how to train
Create a datasets directory and put the images in it
