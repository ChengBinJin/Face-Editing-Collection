# Face Editing Collections
This repository is a collection of the face editing papers and projects.

## Optimization-based GAN Inversion Methods
| Methods  | Paper | Project |
| ------------- | ------------- | :-------------: |
| StyleGANv2 official method  | [Analyzing and Improving the Image Quality of StyleGAN, CVPR2020](https://arxiv.org/pdf/1912.04958.pdf)  | [here](https://github.com/NVlabs/stylegan2)  |
| Puzer method  | Unpublished | [here](https://github.com/Puzer/stylegan-encoder)  |  
| Pbaylies method  | Unpublished | [here](https://github.com/pbaylies/stylegan-encoder)  |  

<p align="center">
<img src="https://user-images.githubusercontent.com/37034031/92347051-52860e80-f101-11ea-9dcb-755f4d1872e8.png" width=1000>
</p>  

<p align="center">
<img src="https://user-images.githubusercontent.com/37034031/92347126-8c571500-f101-11ea-873e-8a44b2dfbbee.png" width=1000>
</p>  

## Interpretable GAN Controls  
| Methods  | Paper | Project | Public code | Without attribute | Without mask | Without interaction | Without re-training | Based on StyleGAN | Manipulation of the latent space |
| ------------- | ------------- | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| StyleFlow | [StyleFlow: Attribute-conditioned Exploration of StyleGAN-Generated Images using Conditional Continuous Normalizing Flows, arXiv2020](https://arxiv.org/pdf/1912.04958.pdf)  | [here](https://github.com/RameenAbdal/StyleFlow) | :x: (readme only) | :x: | :o: | :o: | :x: | :o: | :o: |  
| GANSpace | [GANSpace: Discovering Interpretable GAN Controls, arXiv2020](https://arxiv.org/pdf/2004.02546.pdf) | [here](https://github.com/harskish/ganspace) | :o: | :o: | :o: | :o: | :o: | :o: | :o: |  
| SEAN | [SEAN: Image Synthesis with Semantic Region-Adaptive Normalization, CVPR2020](https://arxiv.org/pdf/1911.12861.pdf) | [here](https://github.com/ZPdesu/SEAN) | :o: | :o: | :x: | :x: | :x: | :x: | :x: |  

## Strategy of Data Collection and Training
| Paper | Description | Project |
| ------------- | ------------- | :-------------: |
| [StyleGAN2 Distillation for Feed-forward Image Manipulation, arXiv2020](https://github.com/EvgenyKashin/stylegan2-distillation)  | Manually collect the paired data using manipulation of latent code from StyleGANv2 and train a model based on pix2pixHD | [here](https://github.com/NVlabs/stylegan2) (readme only) |  
