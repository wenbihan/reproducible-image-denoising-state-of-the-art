# reproducible-image-denoising-state-of-the-art
Collection of popular and reproducible image denoising works.

Criteria: works must have codes available, and the reproducible results demonstrate state-of-the-art performances.

This collection is inspired by the [summary by flyywh](https://github.com/flyywh/Image-Denoising-State-of-the-art)


## Denoising Algorithms
#### Filter
 * NLM [[Web]](http://imagej.net/Non_Local_Means_Denoise) [[Code]](https://github.com/thorstenwagner/ij-nl-means) [[PDF]](http://www.cs.tut.fi/~foi/GCF-BM3D/SPIE08_deblurring.pdf)
   * A non-local algorithm for image denoising (CVPR 05), Buades et al.
 * BM3D [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Code]](http://www.cs.tut.fi/~foi/GCF-BM3D/BM3D.zip) [[PDF]](http://www.cs.tut.fi/~foi/GCF-BM3D/SPIE08_deblurring.pdf)
   * Image restoration by sparse 3D transform-domain collaborative filtering (SPIE Electronic Imaging 2008), Dabov et al.

#### Sparse Coding
 * KSVD [[Web]](http://www.cs.technion.ac.il/~ronrubin/software.html) [[Code]](https://github.com/jbhuang0604/SelfSimSR/tree/master/Lib/KSVD) [[PDF]](http://www.egr.msu.edu/~aviyente/elad06.pdf)
   * Image Denoising Via Sparse and Redundant Representations Over Learned Dictionaries (TIP 2006), Elad et al.
 * LSSC [[Web]](https://lear.inrialpes.fr/people/mairal/) [[Code]](https://lear.inrialpes.fr/people/mairal/resources/denoise_ICCV09.tar.gz) [[PDF]](http://www.di.ens.fr/~fbach/iccv09_mairal.pdf)
   * Non-local Sparse Models for Image Restoration (ICCV 2009), Mairal et al.
 * NCSR [[Web]](http://www4.comp.polyu.edu.hk/~cslzhang/NCSR.htm) [[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/NCSR.rar) [[PDF]](http://www4.comp.polyu.edu.hk/~cslzhang/paper/NCSR_TIP_final.pdf)
   * Nonlocally Centralized Sparse Representation for Image Restoration (TIP 2012), Dong et al.  
 * OCTOBOS [[Web]](http://transformlearning.csl.illinois.edu/projects/) [[Code]](https://github.com/wenbihan/octobos_IJCV2016) [[PDF]](http://transformlearning.csl.illinois.edu/assets/Sai/JournalPapers/SaiBihanIJCV2014OCTOBOS.pdf)
   * Structured Overcomplete Sparsifying Transform Learning with Convergence Guarantees and Applications (IJCV 2015), Wen et al. 
 * GSR [[Web]](https://jianzhang.tech/projects/GSR/) [[Code]](http://csjianzhang.github.io/codes/GSR_Code_Package_3.0.zip) [[PDF]](http://csjianzhang.github.io/papers/TIP2014_single.pdf)
   * Group-based Sparse Representation for Image Restoration (TIP 2014), Zhang et al.
  
#### Effective Prior
 * EPLL [[Web]](https://people.csail.mit.edu/danielzoran/) [[Code]](https://people.csail.mit.edu/danielzoran/epllcode.zip) [[PDF]](http://people.ee.duke.edu/~lcarin/EPLICCVCameraReady.pdf)
   * From Learning Models of Natural Image Patches to Whole Image Restoration (ICCV2011), Zoran et al.
 * GHP [[Web]][[Code]](https://github.com/tingfengainiaini/GHPBasedImageRestoration) [[PDF]](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Zuo_Texture_Enhanced_Image_2013_CVPR_paper.pdf)
   * Texture Enhanced Image Denoising via Gradient Histogram Preservation (CVPR2013), Zuo et al.
 * PGPD [[Web]][[Code]](https://github.com/csjunxu/PGPD_Offline_BID) [[PDF]](http://www4.comp.polyu.edu.hk/~cslzhang/paper/PGPD.pdf)
   * Patch Group Based Nonlocal Self-Similarity Prior Learning for Image Denoising (ICCV 2015), Xu et al.
 * PCLR [[Web]][[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/PCLR.zip) [[PDF]](http://www4.comp.polyu.edu.hk/~cslzhang/paper/PCLR.pdf)
   * External Patch Prior Guided Internal Clustering for Image Denoising (ICCV 2015), Chen et al.
   
#### Low Rank
 * SAIST [[Web]](http://see.xidian.edu.cn/faculty/wsdong/wsdong_Publication.htm) [Code by request] [[PDF]](http://see.xidian.edu.cn/faculty/wsdong/Papers/Journal/TIP_LASSC.pdf)
   * Nonlocal image restoration with bilateral variance estimation: a low-rank approach (TIP2013), Dong et al.
 * WNNM [[Web]](https://sites.google.com/site/shuhanggu/home) [[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/WNNM_code.zip) [[PDF]](https://pdfs.semanticscholar.org/6d55/6272625b672ba54b5ab3d9e6474088a4b78f.pdf)
   * Weighted Nuclear Norm Minimization with Application to Image Denoising (CVPR2014), Gu et al.
 * Multi-channel Weighted Nuclear Norm [[Web]](http://www4.comp.polyu.edu.hk/~csjunxu/Publications.html) [[Code]](http://www4.comp.polyu.edu.hk/~csjunxu/code/MCWNNM.zip) [[PDF]](http://www4.comp.polyu.edu.hk/~csjunxu/paper/MCWNNM.pdf)
   * Multi-channel Weighted Nuclear Norm Minimization for Real Color Image Denoising (ICCV 2017), Xu et al.
   
#### Deep Learning
 * SF [[Web]](http://www.visinf.tu-darmstadt.de/vi_research/code/index.en.jsp#shrinkage_fields) [[Code]](https://github.com/uschmidt83/shrinkage-fields) [[PDF]](http://research.uweschmidt.org/pubs/cvpr14schmidt.pdf)
   * Shrinkage Fields for Effective Image Restoration (CVPR 2014), Schmidt et al.
 * TNRD [[Web]](http://www.icg.tugraz.at/Members/Chenyunjin/about-yunjin-chen) [[Code]](https://www.dropbox.com/s/8j6b880m6ddxtee/TNRD-Codes.zip?dl=0) [[PDF]](https://arxiv.org/pdf/1508.02848.pdf)
   * Trainable nonlinear reaction diffusion: A flexible framework for fast and effective image restoration (TPAMI 2016), Chen et al.
 * DnCNN [[Web]](https://github.com/cszn/DnCNN) [[Code]](https://github.com/cszn/DnCNN) [[PDF]](https://arxiv.org/pdf/1608.03981v1.pdf)
   * Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising (TIP2017), Zhang et al.
   
#### Combined with High-Level Tasks
 * Meets High-level Tasks [[PDF]](https://arxiv.org/pdf/1706.04284.pdf) [[Code]](https://github.com/wenbihan/DeepDenoising) 
   * When Image Denoising Meets High-Level Vision Tasks: A Deep Learning Approach (Arxiv2017), Ding Liu, Bihan Wen, Xianming Liu, Thomas S. Huang.

#### Benchmark
 * Darmstadt [[Web]](https://noise.visinf.tu-darmstadt.de/) [[Data]](https://noise.visinf.tu-darmstadt.de/downloads/) [[PDF]](https://download.visinf.tu-darmstadt.de/papers/2017-cvpr-ploetz-benchmarking_denoising_algorithms-preprint.pdf)
   * Benchmarking Denoising Algorithms with Real Photographs (CVPR 2017), Tobias Plotz, Stefan Roth.
