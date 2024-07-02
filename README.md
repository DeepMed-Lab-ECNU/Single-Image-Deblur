# Single-Image-Deblur
Including DeepRFT and AdaRevD developed by DeepMed Lab.
- [News](#news)
- [Model Zoo](#model-zoo)
- [Citation](#citation)

## News
2024/02/27 The paper of AdaRevD (AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring) is accepted by [CVPR 2024]().

2022/11/19 The paper of DeepRFT (Intriguing findings of frequency selection for image deblurring) is accepted by [AAAI 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25281).

## Model Zoo

| Model | Paper | Pytorch Code |
| - | - | - | 
| DeepRFT-v1 | Deep Residual Fourier Transformation for Single Image Deblurring [[arXiv]](https://arxiv.org/abs/2111.11745)                          | [DeepRFT-v1](https://github.com/INVOKERer/DeepRFT) |
| DeepRFT-v2 | Intriguing Findings of Frequency Selection for Image Deblurring [[AAAI 2023]](https://ojs.aaai.org/index.php/AAAI/article/view/25281) | [DeepRFT-v2](https://github.com/INVOKERer/DeepRFT/tree/AAAI2023) |
| AdaRevD    | AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring [[CVPR 2024]](https://github.com/INVOKERer/AdaRevD/blob/master/AdaRevD.pdf)                             | [AdaRevD](https://github.com/INVOKERer/AdaRevD) |

## Citation
```
@inproceedings{xintm2024AdaRevD, 
    title = {AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring},
    author = {Xintian Mao, Qingli Li and Yan Wang}, 
    booktitle = {Proc. CVPR}, 
    year = {2024}
    }
@inproceedings{xintm2023DeepRFTv2, 
    title = {Intriguing Findings of Frequency Selection for Image Deblurring},
    author = {Xintian Mao, Yiming Liu, Fengze Liu, Qingli Li, Wei Shen and Yan Wang}, 
    booktitle = {Proc. AAAI}, 
    year = {2023}
    }
@inproceedings{xintm2021DeepRFTv1,
    title={Deep Residual Fourier Transformation for Single Image Deblurring},
    author={Xintian Mao, Yiming Liu, Wei Shen, Qingli Li, Yan Wang},
    booktitle={arXiv:2111.11745},
    year={2021}
    }
