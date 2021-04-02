# HISR-Spectral-Mixup-Heterogeneous-Datasets-PyTorch
arXiv link:  https://arxiv.org/abs/2101.07589

## Hyperspectral Image Super-Resolution with Spectral Mixup and Heterogeneous Datasets

Abstract: This  work  studies  Hyperspectral  image  (HSI)  super-resolution   (SR).   HSI   SR   is   characterized   by   high-dimensional data and a limited amount of training exam-ples.   This  exacerbates  the  undesirable  behaviors  of  neu-ral networks such as memorization and sensitivity to out-of-distribution samples.   This work addresses these issueswith three contributions. First, we propose a simple, yet ef-fective data augmentation routine, termed Spectral Mixup,to construct effective virtual training samples.  Second, weobserve that HSI SR and RGB image SR are correlated anddevelop a novel multi-tasking network to train them jointlyso that the auxiliary task RGB image SR can provide addi-tional supervision. Finally, we extend the network to a semi-supervised setting so that it can learn from datasets contain-ing low-resolution HSIs only. With these contributions, ourmethod is able to learn from heterogeneous datasets and liftthe requirement for having a large amount of HD HSI train-ing samples.  Extensive experiments on four datasets showthat our method outperforms existing methods significantlyand underpin the relevance of our contributions. 

## Datasets
Cave, Harvard, NTIRE2020, DIV2K, and Chikusei

## Requirement
Python 3.8, PyTorch 1.7.0, cuda v10.1.243

## trained models with conditions: RGBSR + SSL + SMixup
1. CAVE: models/Cave_DeepShare_Blocks=3_Subs8_Ovls2_Feats=256_epoch_10_Wed_Mar_31_03:00:46_2021.pth
2. Harvard: models/Harvard_DeepShare_Blocks=3_Subs8_Ovls2_Feats=256_epoch_10_Fri_Apr__2_15:35:55_2021.pth
3. NTIRE2020: models/NTIRE2020_DeepShare_Blocks=3_Subs8_Ovls2_Feats=256_epoch_10_Thu_Apr__1_17:20:30_2021.pth


