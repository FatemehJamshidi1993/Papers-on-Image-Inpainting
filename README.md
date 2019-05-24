
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
  2018|ECCV|[Image inpainting for irregular holes using partial convolutions](https://arxiv.org/abs/1804.07723)||[code](https://github.com/Jasonnor/PConv-Keras-Food)|
  2018|Arxiv|[Free-Form Image Inpainting with Gated Convolution](https://arxiv.org/abs/1806.03589)| |Places2 [Zhou et al. 2017] and CelebA-HQ faces [Karras et al. 2017]| [code](http://jiahuiyu.com/deepfill2/)|
   2018| |[Deep_image_prior](https://arxiv.org/abs/1711.10925)|ImageNet ISLVRC|[code](https://github.com/DmitryUlyanov/deep-image-prior)|         
 2018 | |[Generative_inpainting_release](https://arxiv.org/abs/1801.07892)|Faces (CelebA, CelebA-HQ), textures (DTD) and natural images (ImageNet, Places2)|[code](https://github.com/JiahuiYu/generative_inpainting)|   
 2018||[Deep laplacian pyramid networks for fast and accurate superresolution](https://arxiv.org/abs/1704.03915)|bench_mark datasets|[code](https://github.com/phoenix104104/LapSRN)|
 2015|NIPS|[Shepard Convolutional Neural Networks](https://papers.nips.cc/paper/5774-shepard-convolutional-neural-networks.pdf)||[code](https://github.com/jimmy-ren/vcnn_double-bladed/tree/master/applications/Shepard_CNN)|

   * A.1.3. Wavelet Based
  ### A.2. Texture Based
   * A.2.1. Statistical Based
   * A.2.2. Pixel Based
   * A.2.3. Patch Based
   
  Year|Proceeding|Title|dataset|code
--|:--:|:--:|:--:|--
   2003|TOG 2003|[Fragment-based image completion](http://delivery.acm.org/10.1145/890000/882267/p303-drori.pdf?ip=222.195.92.10&id=882267&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2EA4F9C023AC60E700%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1553430113_8d3cc7f5adde2fb3894043de791d9150) | |
2004|TIP 2004|[**Region Filling and Object Removal by Exemplar-Based Image Inpainting**](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/criminisi_tip2004.pdf)||
2005|SIGGRAPH 2005|[Image Completion with Structure Propagation](http://jiansun.org/papers/ImageCompletion_SIGGRAPH05.pdf)|| 
2009|SIGGRAPH 2009|[**PatchMatch: a randomized correspondence algorithm for structural image editing**](http://www.faculty.idc.ac.il/arik/seminar2009/papers/patchMatch.pdf)  ||
2010| TIP 2010|[Image inpainting by patch propagation using patch sparsity](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5404308) ||
2011|ICIP 2011|[Examplar-based inpainting based on local geometry](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6116441)||
2012|TOG 2012|[Combining inconsistent images using patch-based synthesis](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.364.5147&rep=rep1&type=pdf)||
2014|TOG 2014|[**Image completion using Planar structure guidance**](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/structure_completion_small.pdf)||
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
2000|SIGGRAPH 2000|[**Image Inpainting**](https://dl.acm.org/citation.cfm?id=344972)  ||
2001|TIP 2001|[Filling-in by joint interpolation of vector fields and gray levels](https://conservancy.umn.edu/bitstream/handle/11299/3462/1/1706.pdf)||
2002|EJAM 2002|[Digital inpainting based on the mumford–shah–euler image model](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/26ACC4694C7F064B6F40D55C09ACA9A1/S0956792502004904a.pdf/digital_inpainting_based_on_the_mumfordshaheuler_image_model.pdf)  |||
2003|TIP 2003|[Simultaneous structure and texture image inpainting](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1217265)|| 
2003|ICCV 2003|[Learning How to Inpaint from Global Image Statistics](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1238360)| |
2007|CSVT 2007|[Image Compression With Edge-Based Inpainting](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/inpainting_csvt_07.pdf)||
  ### A.6. Generative Adversarial Networks
  Year|Proceeding|Title|dataset|code
--|:--:|:--:|:--:|--
 2017|Siggraph |[Globally and Locally Consistent Image Completion](http://hi.cs.waseda.ac.jp/~iizuka/projects/completion/data/completion_sig2017.pdf)||[code](https://github.com/satoshiiizuka/siggraph2017_inpainting)|
  2019||[Photo-realistic single image super-resolution using a generative adversarial network](https://arxiv.org/abs/1609.04802)|benchmark datasets Set5, Set14, and BSD100, the testing set of BSD300|[code](https://github.com/tensorlayer/srgan)|
 2018||[Pluralistic Image Completion](https://arxiv.org/abs/1903.04227)| buildings (Paris), faces (CelebA-HQ), and natural images (ImageNet)|[code](https://github.com/lyndonzheng/Pluralistic-Inpainting)|
 2018|CVPR|[Eye In-Painting With Exemplar Generative Adversarial Networks](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dolhansky_Eye_In-Painting_With_CVPR_2018_paper.pdf)||[code](https://github.com/bdol/exemplar_gans)|
2018|CVPR|[UV-GAN: Adversarial Facial UV Map Completion for Pose-invariant Face Recognition](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_UV-GAN_Adversarial_Facial_CVPR_2018_paper.pdf)||



## B. Multiple Source Images
### B.1. Video Based

  Year|Proceeding|Title|dataset|code
--|:--:|:--:|:--:|--
2019|AAAI 2019|[Video Inpainting by Jointly Learning Temporal Structure and Spatial Details](https://arxiv.org/pdf/1806.08482.pdf)| |
2019|arXiv:1904.10247 |[Free-form Video Inpainting with 3D Gated Convolution and Temporal PatchGAN](https://arxiv.org/pdf/1904.10247.pdf) ||












