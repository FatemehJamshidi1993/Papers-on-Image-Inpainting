
# Papers-on-Image-Inpainting

Image inpainting is the process of reconstructing missing parts of an image so that observers are unable to tell that these regions have undergone restoration. This technique is often used to remove unwanted objects from an image or to restore damaged portions of old photos. The figures below show example image-inpainting results.

-------------------------------------

# Methods that can be tried out or has code
## A. Single Source Image
  ### A.1. Structure-Based
   * A.1.1. PDE and Variational Based
     * A.1.1.1. Linear Isotropic
     * A.1.1.2. Nonlinear isotropic
     * A.1.1.3. Anisotropic Diffusion
   * A.1.2. Convolution Based
   
 Year|Proceeding|Title|dataset|code
  --|:--:|:--:|:--:|--
   2018| |[Deep_image_prior](https://arxiv.org/abs/1711.10925)|ImageNet ISLVRC|[code](https://github.com/DmitryUlyanov/deep-image-prior)          
 2018 | |[Generative_inpainting_release](https://arxiv.org/abs/1801.07892)|Faces (CelebA, CelebA-HQ), textures (DTD) and natural images (ImageNet, Places2)|[code](https://github.com/JiahuiYu/generative_inpainting)    
 2018||[Deep laplacian pyramid networks for fast and accurate superresolution](https://arxiv.org/abs/1704.03915)|bench_mark datasets|[code](https://github.com/phoenix104104/LapSRN)
 2015|NIPS|[Shepard Convolutional Neural Networks](https://papers.nips.cc/paper/5774-shepard-convolutional-neural-networks.pdf)||[code](https://github.com/jimmy-ren/vcnn_double-bladed/tree/master/applications/Shepard_CNN)

   * A.1.3. Wavelet Based
  ### A.2. Texture Based
   * A.2.1. Statistical Based
   * A.2.2. Pixel Based
   * A.2.3. Patch Based
  ### A.3 Hybrid Based
   * A.3.1. Exemplar-based
     * A.3.1.1. Greedy Optimization
     * A.3.1.2. Global Optimization
   * A.3.2. Decomposition Based
  ### A.4. Sparsity-based
   * A.4.1. Fixed Basis
   * A.4.2 Adaptive Basis
  ### A.5. diffusion based
  Year|Proceeding|Title|dataset|code
--|:--:|:--:|:--:|--
2000|SIGGRAPH 2000|[**Image Inpainting**](https://dl.acm.org/citation.cfm?id=344972)  ||||
2001|TIP 2001|[Filling-in by joint interpolation of vector fields and gray levels](https://conservancy.umn.edu/bitstream/handle/11299/3462/1/1706.pdf)||||
  ### A.6. Generative Adversarial Networks

## B. Multiple Source Images












