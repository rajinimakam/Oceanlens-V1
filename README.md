# OceanLens
Underwater environments present significant challenges due to the selective absorption and scattering of light by water, which affects image clarity, contrast, and color fidelity. In this paper, we tackle these challenges with OceanLens. We model underwater image physics, including backscatter and attenuation, using neural networks with new loss functions such as adaptive backscatter loss and edge correction losses that address variance and luminance. We also demonstrate the relevance of pre-trained monocular depth estimation models for generating underwater depth maps. Our evaluation compares the performance of various loss functions against state-of-the-art methods using the "SeeThru" dataset, revealing significant improvements. Specifically, we observe a roughly 65% reduction in Grayscale Patch Mean Angular Error (GPMAE) and a 60% increase in the Underwater Image Quality Metric (UIQM) compared to the SeeThru and DeepSeeColor methods. Two additional convolutional layers are added to capture subtle image details more effectively with OceanLens. This architecture is validated on the UIEB dataset, with model performance assessed using Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index Measure (SSIM) metrics. OceanLens with 2-layer CNN achieves up to a 12-15% improvement in SSIM and a marginal improvement in PSNR. 
