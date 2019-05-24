
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
   
  Year|Proceeding|Title|dataset|code
--|:--:|:--:|:--:|--
   2003|TOG 2003|[Fragment-based image completion](http://delivery.acm.org/10.1145/890000/882267/p303-drori.pdf?ip=222.195.92.10&id=882267&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2EA4F9C023AC60E700%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1553430113_8d3cc7f5adde2fb3894043de791d9150) | |
2004|TIP 2004|[**Region Filling and Object Removal by Exemplar-Based Image Inpainting**](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/criminisi_tip2004.pdf)||
2005|SIGGRAPH 2005|[Image Completion with Structure Propagation](http://jiansun.org/papers/ImageCompletion_SIGGRAPH05.pdf)|| |
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












