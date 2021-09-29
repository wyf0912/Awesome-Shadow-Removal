# Awesome-Shadow-Removal
Collection of recent shadow removal works. Questions and discussions are most welcome!

## Papers and Codes

### Supervised-Deep-Learning Algorithm 

* `CVPR2017` DeshadowNet: A Multi-Context Embedding Deep Network for Shadow Removal [[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Qu_DeshadowNet_A_Multi-Context_CVPR_2017_paper.pdf) [[Code]](https://github.com/zylix666/DeshadowNet)

* `CVPR2018` Stacked Conditional Generative Adversarial Networks for Jointly Learning Shadow Detection and Shadow Removal [[Paper]](https://arxiv.org/pdf/1712.02478v1.pdf) [[Code]](https://github.com/IsHYuhi/ST-CGAN_Stacked_Conditional_Generative_Adversarial_Networks)

* `ICCV2019` Shadow Removal via Shadow Image Decomposition [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Le_Shadow_Removal_via_Shadow_Image_Decomposition_ICCV_2019_paper.pdf) [[Code]](https://github.com/cvlab-stonybrook/SID)

* `TPAMI2019` Direction-Aware Spatial Context Features for Shadow Detection and Removal [[Paper]](https://arxiv.org/pdf/1805.04635.pdf) [[Code]](https://github.com/xw-hu/DSC)

* `AAAI2020` RIS-GAN: Explore Residual and Illumination with Generative Adversarial Networks for Shadow Removal [[Paper]](http://www.chengjianglong.com/publications/RISGAN_AAAI.pdf) [[Code]](https://github.com/zhling2020/RIS-GAN)

* `AAAI2020` Towards Ghost-Free Shadow Removal via Dual Hierarchical Aggregation Network and Shadow Matting GAN [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6695) [[Code]](https://github.com/vinthony/ghost-free-shadow-removal)

* `SPL2021` Mask-ShadowNet: Towards Shadow Removal via Masked Adaptive Instance Normalization [[Paper]](https://ieeexplore.ieee.org/document/9408351) [[Code]](https://github.com/penguinbing/Mask-ShadowNet)

* `CVPR2021` Auto-Exposure Fusion for Single-Image Shadow Removal [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Fu_Auto-Exposure_Fusion_for_Single-Image_Shadow_Removal_CVPR_2021_paper.html) [[Code]](https://github.com/tsingqguo/exposure-fusion-shadow-removal)

* `Arxiv2021` CANet: A Context-Aware Network for Shadow Removal [[Paper]](https://arxiv.org/pdf/2108.09894.pdf) [[Code]](https://github.com/Zipei-Chen/CANet)

### Weakly-Supervised-Deep-Learning Algorithm 

* `ICCV2019` Mask-ShadowGAN: Learning to Remove Shadows from Unpaired Data [[Paper]](https://arxiv.org/abs/1903.10683) [[Code]](https://github.com/xw-hu/Mask-ShadowGAN)

* `ECCV2020` From Shadow Segmentation to Shadow Removal [[Paper]](https://arxiv.org/pdf/2008.00267.pdf) [[Code]](https://github.com/lmhieu612/FSS2SR)

* `TIP2021` Shadow Removal by a Lightness-Guided Network With Training on Unpaired Data [[Paper]](https://ieeexplore.ieee.org/abstract/document/9318562) [[Code]](https://github.com/hhqweasd/LG-ShadowNet)

### Unsupervised-Deep-Learning Algorithm

* `CVPR2021` From Shadow Generation to Shadow Removal [[Paper]](https://arxiv.org/pdf/2103.12997v1.pdf) [[Code]](https://github.com/hhqweasd/G2R-ShadowNet)


### Shadow Generation

* `AAAI2020` Towards Ghost-Free Shadow Removal via Dual Hierarchical Aggregation Network and Shadow Matting GAN [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6695) [[Code]](https://github.com/vinthony/ghost-free-shadow-removal)

* `TCSVT2020` Learning from Synthetic Shadows for Shadow Detection and Removal [[Paper]](https://arxiv.org/abs/2101.01713) [[Code]](https://github.com/naoto0804/SynShadow)

* `CVPR2021` From Shadow Generation to Shadow Removal [[Paper]](https://arxiv.org/pdf/2103.12997v1.pdf) [[Code]](https://github.com/hhqweasd/G2R-ShadowNet)


### Application

* `ICASSP2020` Shadow removal of text document images by estimating local and global background colors [[Paper]](https://ieeexplore.ieee.org/document/9053378)

* `CVPR2020` BEDSR-Net: A Deep Shadow Removal Network From a Single Document Image [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_BEDSR-Net_A_Deep_Shadow_Removal_Network_From_a_Single_Document_CVPR_2020_paper.html)

## Datasets

* ISTD [[link]](https://github.com/DeepInsight-PCALab/ST-CGAN)
* ISTD+ [[link]](https://github.com/cvlab-stonybrook/SID)
* SRD (please email the [authors](https://openaccess.thecvf.com/content_cvpr_2017/papers/Qu_DeshadowNet_A_Multi-Context_CVPR_2017_paper.pdf) to get assess).
* USR: Unpaired Shadow Removal Dataset [[link]](https://drive.google.com/file/d/1PPAX0W4eyfn1cUrb2aBefnbrmhB1htoJ/view)

## Metrics

 * RMSE (Root-Mean-Square Error) [[Wiki]](https://en.wikipedia.org/wiki/Root-mean-square_deviation) [[Matlab Code]](https://www.mathworks.com/matlabcentral/fileexchange/21383-rmse) 
 * PSNR (Peak Signal-to-Noise Ratio) [[Wiki]](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) [[Matlab Code]](https://www.mathworks.com/help/images/ref/psnr.html) [[Python Code]](https://github.com/aizvorski/video-quality)
 * SSIM (Structural similarity) [[Wiki]](https://en.wikipedia.org/wiki/Structural_similarity) [[Matlab Code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[Python Code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py)
 * NIQE (Naturalness Image Quality Evaluator) [[Web]](http://live.ece.utexas.edu/research/Quality/nrqa.htm) [[Matlab Code]](http://live.ece.utexas.edu/research/Quality/nrqa.htm) [[Python Code]](https://github.com/aizvorski/video-quality/blob/master/niqe.py)
