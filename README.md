# Face Editing Collections
This repository is a collection of the face editing papers and projects.

## Optimization-based GAN Inversion Methods
| Methods  | Paper | Loss | Project |
| ------------- | ------------- | :-------------: | :-------------: |  
| StyleGANv2 official method  | [Analyzing and Improving the Image Quality of StyleGAN, CVPR2020](https://arxiv.org/pdf/1912.04958.pdf)  | LPIPS | [here](https://github.com/NVlabs/stylegan2)  |
| Puzer method  | Unpublished | Perceptual loss (conv3-3 of pre-trained VGG16) | [here](https://github.com/Puzer/stylegan-encoder)  |  
| Pbaylies method  | Unpublished | Unknown | [here](https://github.com/pbaylies/stylegan-encoder)  |  
| IDInvert | [In-Domain GAN Inversion for Real Image Editing, ECCV2020](https://arxiv.org/pdf/2004.00049.pdf) | Perceptual loss (conv4-3 of pre-trained VGG16) + MSE + domain-inversion loss | [here](https://github.com/genforce/idinvert)  |  
| Image2StyleGAN | [Image2StyleGAN: How to Embed Images Into the StyleGAN Latent Space?, ICCV2019](https://arxiv.org/pdf/1904.03189.pdf) | Perceptual loss (pre-trained VGG16) + MSE | Unopened | 

<p align="center">
<img src="https://user-images.githubusercontent.com/37034031/92896350-e08a2e00-f44e-11ea-92c0-9b5a87e91099.png" width=1000>
</p>  

<p align="center">
<img src="https://user-images.githubusercontent.com/37034031/94364810-99fb2b80-00fe-11eb-9932-11cf4911aecd.png" width=500>
</p>  

<p align="center">
<img src="https://user-images.githubusercontent.com/37034031/92896457-f861b200-f44e-11ea-8ccc-d470285f9e2c.png" width=1000>
</p>  

<p align="center">
<img src="https://user-images.githubusercontent.com/37034031/94364813-a2536680-00fe-11eb-970f-3c929ae51d36.png" width=500>
</p>  

## Interpretable GAN Controls  
| Methods  | Paper | Project | Public code | Without attribute | Without mask | Without interaction | Without re-training | Based on StyleGAN | Manipulation of the latent space |
| ------------- | ------------- | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| StyleFlow | [StyleFlow: Attribute-conditioned Exploration of StyleGAN-Generated Images using Conditional Continuous Normalizing Flows, arXiv2020](https://arxiv.org/pdf/1912.04958.pdf)  | [here](https://github.com/RameenAbdal/StyleFlow) | :x: (readme only) | :x: | :o: | :o: | :x: | :o: | :o: |  
| GANSpace | [GANSpace: Discovering Interpretable GAN Controls, arXiv2020](https://arxiv.org/pdf/2004.02546.pdf) | [here](https://github.com/harskish/ganspace) | :o: | :o: | :o: | :o: | :o: | :o: | :o: |  
| InterFaceGAN | [Interpreting the Latent Space of GANs for Semantic Face Editing, CVPR2020](https://openaccess.thecvf.com/content_CVPR_2020/papers/Shen_Interpreting_the_Latent_Space_of_GANs_for_Semantic_Face_Editing_CVPR_2020_paper.pdf) | [here](https://github.com/genforce/interfacegan) | :o: | :x: | :o: | :o: | :o: | :o: | :o: |  
| IDInvert | [In-Domain GAN Inversion for Real Image Editing, ECCV2020](https://arxiv.org/pdf/2004.00049.pdf) | [here](https://github.com/genforce/idinvert) | :o: | :x: | :o: | :o: | :x: | :o: | :o: |  
| SEAN | [SEAN: Image Synthesis with Semantic Region-Adaptive Normalization, CVPR2020](https://arxiv.org/pdf/1911.12861.pdf) | [here](https://github.com/ZPdesu/SEAN) | :o: | :o: | :x: | :x: | :x: | :x: | :x: |  
| ConfigNet | [CONFIG: Controllable Neural Face Image Generation, ECCV2020](https://arxiv.org/pdf/2005.02671.pdf) | [here](https://github.com/microsoft/ConfigNet) | :o: | :x: | :o: | :o: | :x: | :x: | :x: |  
| AttGAN | [AttGAN: Facial Attribute Editing by only Changing What You Want, TIP2019](https://arxiv.org/abs/1711.10678) | [here](https://github.com/LynnHo/AttGAN-Tensorflow) | :o: | :x: | :o: | :o: | :x: | :x: | :x: |  
| STGAN | [STGAN: A Unified Selective Transfer Network for Arbitrary Image Attribute Editing, ICCV2019](https://arxiv.org/abs/1904.09709) | [here](https://github.com/csmliu/STGAN) | :o: | :x: | :o: | :o: | :x: | :x: | :x: |  
| Hessian-Penalty | [The Hessian Penalty: A Weak Prior for Unsupervised Disentanglement, ECCV2020](https://arxiv.org/abs/2008.10599) | [here](https://github.com/wpeebles/hessian_penalty) | :o: | :o: | :o: | :o: | :x: | :x: | :x: |  

## Strategy of Data Collection and Training
| Paper | Description | Project |
| ------------- | ------------- | :-------------: |
| [StyleGAN2 Distillation for Feed-forward Image Manipulation, arXiv2020](https://github.com/EvgenyKashin/stylegan2-distillation)  | Manually collect the paired data using manipulation of latent code from StyleGANv2 and train a model based on pix2pixHD | [here](https://github.com/NVlabs/stylegan2) (readme only) |  
