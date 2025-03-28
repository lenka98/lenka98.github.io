---
title: "Blind Deblurring Using GANs" 
date: 2019-07-27
url: /deblur_gan/
tags: ["Deblurring","Deep Learning","Image Processing","Generative Adversarial Networks"]
author: ["Manoj Kumar Lenka", "Anubha Pandey", "Anurag Mittal"]
description: "Deblurring is the task of restoring a blurred image to a sharp one, retrieving the information lost due to the blur. In blind deblurring we have no information regarding the blur kernel. As deblurring can be considered as an image to image translation task, deep learning based solutions, including the ones which use GAN (Generative Adversarial Network), have been proven effective for deblurring. Most of them have an encoder-decoder structure. Our objective is to try different GAN structures and improve its performance through various modifications to the existing structure for supervised deblurring. In supervised deblurring we have pairs of blurred and their corresponding sharp images, while in the unsupervised case we have a set of blurred and sharp images but their is no correspondence between them. Modifications to the structures is done to improve the global perception of the model. As blur is non-uniform in nature, for deblurring we require global information of the entire image, whereas convolution used in CNN is able to provide only local perception. Deep models can be used to improve global perception but due to large number of parameters it becomes difficult for it to converge and inference time increases, to solve this we propose the use of attention module (non-local block) which was previously used in language translation and other image to image translation tasks in deblurring. Use of residual connection also improves the performance of deblurring as features from the lower layers are added to the upper layers of the model. It has been found that classical losses like L1, L2, and perceptual loss also help in training of GANs when added together with adversarial loss. We also concatenate edge information of the image to observe its effects on deblurring. We also use feedback modules to retain long term dependencies " 
summary: "Deblurring is the task of restoring a blurred image to a sharp one, retrieving the information lost due to the blur. In blind deblurring we have no information regarding the blur kernel. As deblurring can be considered as an image to image translation task, deep learning based solutions, including the ones which use GAN (Generative Adversarial Network), have been proven effective for deblurring. Most of them have an encoder-decoder structure. Our objective is to try different GAN structures and improve its performance through various modifications to the existing structure for supervised deblurring. In supervised deblurring we have pairs of blurred and their corresponding sharp images, while in the unsupervised case we have a set of blurred and sharp images but their is no correspondence between them. Modifications to the structures is done to improve the global perception of the model. As blur is non-uniform in nature, for deblurring we require global information of the entire image, whereas convolution used in CNN is able to provide only local perception. Deep models can be used to improve global perception but due to large number of parameters it becomes difficult for it to converge and inference time increases, to solve this we propose the use of attention module (non-local block) which was previously used in language translation and other image to image translation tasks in deblurring. Use of residual connection also improves the performance of deblurring as features from the lower layers are added to the upper layers of the model. It has been found that classical losses like L1, L2, and perceptual loss also help in training of GANs when added together with adversarial loss. We also concatenate edge information of the image to observe its effects on deblurring. We also use feedback modules to retain long term dependencies " 
editPost:
    Text: "arXiV"

---

##### View

+ [Paper](https://arxiv.org/pdf/1907.11880.pdf)
+ [Code](https://github.com/lenka98/Bind-Deblurring-using-GANs)

---

##### Abstract

Deblurring is the task of restoring a blurred image to a sharp one, retrieving the information lost due to the blur. In blind deblurring we have no information regarding the blur kernel. As deblurring can be considered as an image to image translation task, deep learning based solutions, including the ones which use GAN (Generative Adversarial Network), have been proven effective for deblurring. Most of them have an encoder-decoder structure. Our objective is to try different GAN structures and improve its performance through various modifications to the existing structure for supervised deblurring. In supervised deblurring we have pairs of blurred and their corresponding sharp images, while in the unsupervised case we have a set of blurred and sharp images but their is no correspondence between them. Modifications to the structures is done to improve the global perception of the model. As blur is non-uniform in nature, for deblurring we require global information of the entire image, whereas convolution used in CNN is able to provide only local perception. Deep models can be used to improve global perception but due to large number of parameters it becomes difficult for it to converge and inference time increases, to solve this we propose the use of attention module (non-local block) which was previously used in language translation and other image to image translation tasks in deblurring. Use of residual connection also improves the performance of deblurring as features from the lower layers are added to the upper layers of the model. It has been found that classical losses like L1, L2, and perceptual loss also help in training of GANs when added together with adversarial loss. We also concatenate edge information of the image to observe its effects on deblurring. We also use feedback modules to retain long term dependencies 

---

##### Citation

M. Lenka and A. Chakraborty, “On-Device Deep Learning for IoT-based Wireless Sensing Applications,” in 2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops), Biarritz, France, 2024

```BibTeX
@misc{lenka2019blind,
      title={Blind Deblurring Using GANs}, 
      author={Lenka, Manoj and Pandey, Anubha and Mittal, Anurag},
      year={2019},
      eprint={1907.11880},
      archivePrefix={arXiv},
}
```

