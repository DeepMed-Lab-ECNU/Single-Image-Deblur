# Single-Image-Deblur
Including DeepRFT, LoFormer and AdaRevD developed by DeepMed Lab.
- [News](#news)
- [Model Zoo](#model-zoo)
- [Citation](#citation)

## News
2024/07/16 The paper of LoFormer (LoFormer: Local Frequency Transformer for Image Deblurring) is accepted by [ACM MM 2024](https://arxiv.org/abs/2407.16993).

2024/02/27 The paper of AdaRevD (AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring) is accepted by [CVPR 2024](https://openaccess.thecvf.com/content/CVPR2024/html/Mao_AdaRevD_Adaptive_Patch_Exiting_Reversible_Decoder_Pushes_the_Limit_of_CVPR_2024_paper.html).

2022/11/19 The paper of DeepRFT (Intriguing findings of frequency selection for image deblurring) is accepted by [AAAI 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25281).

## Model Zoo

| Model | Paper | Pytorch Code |
| - | - | - | 
| DeepRFT-v1 | Deep Residual Fourier Transformation for Single Image Deblurring [[arXiv]](https://arxiv.org/abs/2111.11745v1)                          | [DeepRFT-v0](https://github.com/INVOKERer/DeepRFT) |
| DeepRFT-v2 | Intriguing Findings of Frequency Selection for Image Deblurring [[AAAI 2023]](https://ojs.aaai.org/index.php/AAAI/article/view/25281) | [DeepRFT-v1](https://github.com/INVOKERer/DeepRFT/tree/AAAI2023) |
| AdaRevD    | AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring [[CVPR 2024]](https://arxiv.org/abs/2406.09135)  | [AdaRevD](https://github.com/INVOKERer/AdaRevD) |
| LoFormer   | LoFormer: Local Frequency Transformer for Image Deblurring [[ACM MM 2024]](https://arxiv.org/abs/2407.16993)                             | [LoFormer](https://github.com/INVOKERer/LoFormer) |

## Citation
```
@inproceedings{xintm2024LoFormer, 
    title = {LoFormer: Local Frequency Transformer for Image Deblurring},
    author = {Xintian Mao, JIansheng Wang, Xingran Xie, Qingli Li and Yan Wang}, 
    booktitle = {Proc. ACM MM}, 
    year = {2024}
    }
@inproceedings{xintm2024AdaRevD, 
    title = {AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring},
    author = {Xintian Mao, Qingli Li and Yan Wang}, 
    booktitle = {Proc. CVPR}, 
    year = {2024}
    }
@inproceedings{xintm2023DeepRFTv1, 
    title = {Intriguing Findings of Frequency Selection for Image Deblurring},
    author = {Xintian Mao, Yiming Liu, Fengze Liu, Qingli Li, Wei Shen and Yan Wang}, 
    booktitle = {Proc. AAAI}, 
    year = {2023}
    }
@inproceedings{xintm2021DeepRFTv0,
    title={Deep Residual Fourier Transformation for Single Image Deblurring},
    author={Xintian Mao, Yiming Liu, Wei Shen, Qingli Li, Yan Wang},
    booktitle={arXiv:2111.11745},
    year={2021}
    }
