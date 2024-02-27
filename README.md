# Single-Image-Deblur
including DeepRFT and AdaRevD developed by DeepMed Lab.
- [News](#news)
- [Model zoo](#model-zoo)
- [Citation](#citation)

## News
2024/02/27 The paper of AdaRevD (AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring) is accepted by [CVPR 2024]().
2022/11/19 The paper of DeepRFT (Intriguing findings of frequency selection for image deblurring) is accepted by [AAAI 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25281).

## Model zoo

| Model | Paper | Pytorch code |
| - | - | - | 
| DeepRFT-v1 | Deep Residual Fourier Transformation for Single Image Deblurring [[Arxiv]](https://arxiv.org/abs/2111.11745) | [DeepRFT-v1](https://github.com/INVOKERer/DeepRFT) |
| DeepRFT-v2 | Intriguing findings of frequency selection for image deblurring [[AAAI 2023]](https://ojs.aaai.org/index.php/AAAI/article/view/25281) | [DeepRFT-v2](https://github.com/INVOKERer/DeepRFT/tree/AAAI2023) |
| AdaRevD | AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring [[CVPR 2024]]() | [AdaRevD](https://github.com/INVOKERer/AdaRevD) |

## Citation
```
@inproceedings{xint2023freqsel, 
    title = {Intriguing Findings of Frequency Selection for Image Deblurring},
    author = {Xintian Mao, Yiming Liu, Fengze Liu, Qingli Li, Wei Shen and Yan Wang}, 
    booktitle = {Proceedings of the 37th AAAI Conference on Artificial Intelligence}, 
    year = {2023}
    }
@inproceedings{,
    title={Deep Residual Fourier Transformation for Single Image Deblurring},
    author={Xintian Mao, Yiming Liu, Wei Shen, Qingli Li, Yan Wang},
    booktitle={arXiv:2111.11745},
    year={2021}
}
