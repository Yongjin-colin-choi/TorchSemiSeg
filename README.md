# Semi-supervised Sementic Segmentation with Cross Pseudo Supervision
<br>

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/semi-supervised-semantic-segmentation-with-3/semi-supervised-semantic-segmentation-on-2)](https://paperswithcode.com/sota/semi-supervised-semantic-segmentation-on-2?p=semi-supervised-semantic-segmentation-with-3)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/semi-supervised-semantic-segmentation-with-3/semi-supervised-semantic-segmentation-on-1)](https://paperswithcode.com/sota/semi-supervised-semantic-segmentation-on-1?p=semi-supervised-semantic-segmentation-with-3)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/semi-supervised-semantic-segmentation-with-3/semi-supervised-semantic-segmentation-on-8)](https://paperswithcode.com/sota/semi-supervised-semantic-segmentation-on-8?p=semi-supervised-semantic-segmentation-with-3)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/semi-supervised-semantic-segmentation-with-3/semi-supervised-semantic-segmentation-on-4)](https://paperswithcode.com/sota/semi-supervised-semantic-segmentation-on-4?p=semi-supervised-semantic-segmentation-with-3)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/semi-supervised-semantic-segmentation-with-3/semi-supervised-semantic-segmentation-on-9)](https://paperswithcode.com/sota/semi-supervised-semantic-segmentation-on-9?p=semi-supervised-semantic-segmentation-with-3)

> [[CVPR 2021] Semi-Supervised Semantic Segmentation with Cross Pseudo Supervision](https://arxiv.org/abs/2106.01226)
>
> by [Xiaokang Chen](https://charlescxk.github.io)<sup>1</sup>, [Yuhui Yuan](https://scholar.google.com/citations?user=PzyvzksAAAAJ&hl=zh-CN)<sup>2</sup>, [Gang Zeng](https://www.cis.pku.edu.cn/info/1177/1378.htm)<sup>1</sup>, [Jingdong Wang](https://jingdongwang2017.github.io/)<sup>2</sup>.
> 
> <sup>1</sup> Key Laboratory of Machine Perception (MOE), Peking University
><sup>2</sup> Microsoft Research Asia.
> 
> [[Poster](https://charlescxk.github.io/papers/CVPR2021_CPS/00446-poster.pdf)] [[Video (YouTube)](https://www.youtube.com/watch?v=5HKitm0O27w)]
>
> ***Simpler Is Better !***

<br>

<img src=ReadmePic/cps.png width="600">

## News
- **[July 9  2021] We have released some SOTA methods (Mean Teacher, CCT, GCT).**  
- **[June 3 2021] Please check our paper in [Arxiv](https://arxiv.org/abs/2106.01226). Data and code have been released.**  


## Installation
Please refer to the [Installation](./docs/installation.md) document.

## Getting Started
Please follow the [Getting Started](./docs/getting_started.md) document.


## CutMix
<img src=ReadmePic/cutmix.png width="300">

- cutout, mixup과 마찬가지로 regularization 기법 중 하나.
- cutout은 patch를 잘라내어 local한 정보 손실을 유발, mixup은 interpolation을 하여 이미지 정보가 왜곡됨.
- 이미지의 local한 부분에만 집중하지않고, 덜 중요한 부분까지 focusing하게 하여 segmentation task에 적합함.

## Loss
<img src=ReadmePic/loss_l.png width="300"> <img src=ReadmePic/loss_r.png width="300"> 
<img src=ReadmePic/loss_cps.png width="300">

#### TODO
- [x] Dataset release
- [x] Code for CPS + CutMix
- [x] Code for Cityscapes dataset
- [x] Other SOTA semi-supervised segmentation methods


## Citation

Please consider citing this project in your publications if it helps your research.

```bibtex
@inproceedings{chen2021-CPS,
  title={Semi-Supervised Semantic Segmentation with Cross Pseudo Supervision},
  author={Chen, Xiaokang and Yuan, Yuhui and Zeng, Gang and Wang, Jingdong},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2021}
}
```
