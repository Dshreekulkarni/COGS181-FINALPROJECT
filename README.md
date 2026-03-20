# COGS181-FINALPROJECT

This is our final project for COGS 181: Neural Networks and Deep Learning.
Group Members: Naomi and Dhanashree. 

The Cropped Yale dataset of face images can be found here: http://pages.ucsd.edu/~ztu/courses/CroppedYale.zip

Abstract:
Image inpainting is the task of reconstructing occluded or missing regions of an image, with important applications in face restoration and image recognition under partial visibility. In this project, we compare three fundamentally different approaches for reconstructing occluded facial images: Robust PCA (RPCA), U-Net, and Masked Autoencoder (MAE). Using the Cropped Yale Face Dataset, we simulate occlusions through randomly generated masks and evaluate model performance using pixel-level metrics (MAE, MSE, PSNR) over masked regions, along with SSIM to assess perceptual quality over the full image. Our results show that MAE outperforms both U-Net and RPCA, achieving the lowest reconstruction errors and highest perceptual similarity. While RPCA serves as a reasonable baseline, it is less efficient in producing reconstructions of high perceptual quality. These findings highlight the importance of model architecture in masked image reconstruction and suggest that transformer-based approaches offer a significant advantage in handling structured occlusions.
