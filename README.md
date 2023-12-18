# SRCNN-Implementation

A deep Convolutional Neural Network that learns end-to-end mapping of low resolution to high resolution images.
This project is an implementation of the SRCNN [research paper](https://arxiv.org/abs/1501.00092) by Chao Dong, Chen Change Loy, Kaiming He, Xiaoou Tang.

**Data:** Images used in the project is taken from DIV2K dataset that can be found [here](https://www.kaggle.com/datasets/soumikrakshit/div2k-high-resolution-images).

## Output

![old_man_srcnn](https://github.com/Amann09/SRCNN-Implementation/assets/100956289/fe999864-3bea-4a43-809b-39d0ddbf6de3)

| Parameter | Degraded Image  | SRCNN  |
| :-------- | :-------------- | :----  |
| `PSNR`    | 28.88           | 30.95  |
| `MSE`     | 251.96          | 156.50 |
| `SSIM`    | 0.807           | 0.851  |

![woman_srcnn](https://github.com/Amann09/SRCNN-Implementation/assets/100956289/e746e212-883f-45cd-8668-4ddfcbfd05a6)

| Parameter | Degraded Image  | SRCNN  |
| :-------- | :-------------- | :----  |
| `PSNR`    | 33.18           | 35.38  |
| `MSE`     | 93.64           | 56.44  |
| `SSIM`    | 0.928           | 0.940  |

### Performance Evaluation Metrics
PSNR: Peak to Signal Noise Ratio
MSE: Mean Squared Error
SSIM: Structural Similarity
