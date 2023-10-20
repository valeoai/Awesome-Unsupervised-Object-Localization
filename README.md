# Awesome works on *Unsupervised Object Localization*

🌟 We propose here a curated list of recent works that perform *unsupervised object localization*.  

📝 If you found a missing paper (either yours or someone else's), don't hesitate to create a pull request. \
(Last update 16th of Oct. 2023)

##

📚 Many of these works are discussed in our survey paper on methods which leverage *ViTs self-supervised features* and do not use *any manual annotation*. 
>Unsupervised Object Localization in the Era of Self-Supervised ViTs: A Survey 
\
by Oriane Siméoni, Eloi Zablocki, Spyros Gidaris, Gilles Puy and Patrick Pérez \
<a href="https://arxiv.org/abs/2310.12904">[paper]</a>

## Table of Content
* [*Training-free* object localization with ViT self-supervised features](#Training-free-object-localization-with-ViT-self-supervised-features)
  * [Single object-discovery](#Single-object-discovery)
  * [Multi-object discovery](#Multi-object-discovery)
* [*With training* object localization using ViT self-supervised features](#With-training-object-localization-using-ViT-self-supervised-features)
  * [Unsupervised saliency detection](#Unsupervised-saliency-detection)
  * [Class-agnostic multi-object detection/instance segmentation](#Class-agnostic-multi-object-detectioninstance-segmentation)
  * [Improving self-supervised features](#Improving-self-supervised-features)
* [Self-supervised features used for the task](#Self-supervised-features-used-for-the-task)


##
## 🚀 *Training-free* object localization with ❄ ViT self-supervised features ❄
In this section we report methods that solely exploit self-supervised features without requiring a training step. 

### Single object-discovery

**<< LOST >>** \
Localizing Objects with Self-Supervised Transformers and no Labels, BMVC 2021
<a href="https://arxiv.org/abs/2109.14279">[paper]</a> <a href="https://github.com/valeoai/LOST">[code]</a>

**<< TokenCut >>** \
Self-supervised Transformers for Unsupervised Object Discovery using Normalized Cut, CVPR 2022
<a href="https://arxiv.org/abs/2202.11539">[paper]</a> <a href="https://github.com/YangtaoWANG95/TokenCut">[code]</a> \
TokenCut: Segmenting Objects in Images and Videos with Self-supervised Transformer and Normalized Cut
<a href="https://arxiv.org/abs/2209.00383">[paper]</a> <a href="https://github.com/YangtaoWANG95/TokenCut_video">[code]</a>

**<< DSM >>** \
Deep Spectral Methods: A Surprisingly Strong Baseline for Unsupervised Semantic Segmentation and Localization, CVPR 2022
<a href="https://arxiv.org/abs/2205.07839">[paper]</a> <a href="https://github.com/lukemelas/deep-spectral-segmentation">[code]</a>

### Multi-object discovery

**<< MOST >>** \
 MOST: Multiple Object localization with Self-supervised Transformers for object discovery, ICCV 2023 
<a href="https://arxiv.org/abs/2304.05387">[paper]</a> <a href="">[code]</a>

##
## 🏋 *With training* 🏋 object localization using ViT self-supervised features
We now report methods which integrate a training step.

### Unsupervised saliency detection

**<< SelfMask >>** \
Unsupervised Salient Object Detection with Spectral Cluster Voting, CVPRW 2022 
<a href="https://arxiv.org/abs/2203.12614">[paper]</a> <a href="https://github.com/NoelShin/selfmask">[code]</a>

**<< MOVE >>** \
MOVE: Unsupervised Movable Object Segmentation and Detection, NeurIPS 2022
<a href="https://arxiv.org/abs/2210.07920">[paper]</a> <a href="https://github.com/adambielski/move-seg">[code]</a>

**<< FOUND >>** \
Unsupervised Object Localization: Observing the Background to Discover Objects, CVPR 2023
<a href="https://arxiv.org/abs/2212.07834">[paper]</a> <a href="https://github.com/valeoai/FOUND">[code]</a>

**<< UCOS-DA >>** \
Unsupervised camouflaged object segmentation as domain adaptation, ICCVW 2023
<a href="https://arxiv.org/abs/2308.04528">[paper]</a> <a href="https://github.com/Jun-Pu/UCOS-DA">[code]</a>

**<< UOLwRPS >>** \
Unsupervised object localization with representer point selection, ICCV 2023
<a href="https://arxiv.org/abs/2309.04172">[paper]</a> <a href=" https://github.com/yeonghwansong/uolwrps">[code]</a>

**<< SEMPART >>** \
Sempart: Self-supervised Multi-resolution Partitioning of Image Semantics, ICCV 2023
<a href="">[paper]</a>

**<< PaintSeg >>** \
PaintSeg: Training-free Segmentation via Painting, NeurIPS 2023
<a href="https://arxiv.org/abs/2305.19406">[paper]</a> <a href="">[code]</a>

### Class-agnostic multi-object detection/instance segmentation 

**<< FreeSolo >>** \
FreeSOLO: Learning to Segment Objects without Annotations, CVPR 2022
<a href="https://arxiv.org/abs/2202.12181">[paper]</a> <a href="https://github.com/NVlabs/FreeSOLO">[code]</a> 

**<< DeepCut >>** \
Deepcut: Unsupervised segmentation using graph neural networks clustering, arxiv 2022
<a href="https://arxiv.org/abs/2212.05853">[paper]</a>

**<< IMST >>** \
K-means for unsupervised instance segmentation using a self-supervised transformer, arxiv 2022 
<a href="https://papers.ssrn.com/sol3/Delivery.cfm/456a55bb-5b72-49b6-be69-b5f39b85c44c-MECA.pdf?abstractid=4251338&mirid=1">[paper]</a>

**<< MaskDistill >>** \
Discovering Object Masks with Transformers for Unsupervised Semantic Segmentation, arxiv 2022
<a href="https://arxiv.org/abs/2206.06363">[paper]</a> <a href="">[code]</a>

**<< UMOD >>** \
Image segmentation-based unsupervised multiple objects discovery, WACV 2023
<a href="https://arxiv.org/abs/2212.10124">[paper]</a>

**<< CutLer >>** \
Cut and Learn for Unsupervised Image & Video Object Detection and Instance Segmentation, CVPR 2023
<a href="">[paper]</a> <a href="https://github.com/facebookresearch/CutLER">[code]</a> \
VideoCutLER: Surprisingly Simple Unsupervised Video Instance Segmentation, arxiv 2023 <a href="https://arxiv.org/abs/2308.14710">[paper] <a href="https://github.com/facebookresearch/CutLER/blob/main/videocutler/README.md">[code]</a>

**<< Exemplar FreeSolo >>** \
Exemplar-FreeSOLO: Enhancing Unsupervised Instance Segmentation with Exemplars, CVPR 2023
<a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Ishtiak_Exemplar-FreeSOLO_Enhancing_Unsupervised_Instance_Segmentation_With_Exemplars_CVPR_2023_paper.pdf">[paper]</a> 

### Improving self-supervised features

**<< WSCUOD >>** \
Weakly-supervised Contrastive Learning for
Unsupervised Object Discovery, arxiv 2023
<a href="https://arxiv.org/abs/2307.03376">[paper]</a> <a href="https://github.com/npucvr/WSCUOD">[code]</a>

**<< Box-based refinement >>** \
Box-based Refinement for Weakly Supervised and Unsupervised Localization
Tasks, ICCV 2023
<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Gomel_Box-based_Refinement_for_Weakly_Supervised_and_Unsupervised_Localization_Tasks_ICCV_2023_paper.pdf">[paper]</a> <a href="https://github.com/eyalgomel/box-based-refinement">[code]</a>

##
## Self-supervised features used for the task

**<< DINO >>** \
Emerging Properties in Self-Supervised Vision Transformers, ICCV 2021 
<a href="https://arxiv.org/abs/2104.14294">[paper]</a> <a href="https://github.com/facebookresearch/dino">[code]</a>

**<< MOCOv2 >>** \
Improved Baselines with Momentum Contrastive Learning, arxiv 2020
<a href="https://arxiv.org/abs/2003.04297">[paper]</a>

**<< SimSiam >>** \
Exploring Simple Siamese Representation Learning, CVPR 2020
<a href="https://arxiv.org/abs/2011.10566">[paper]</a> <a href="https://github.com/facebookresearch/simsiam">[code]</a>

**<< BYOL >>** \
Bootstrap your own latent: A new approach to self-supervised Learning, NeurIPS 2020
<a href="https://arxiv.org/abs/2006.07733">[paper]</a> <a href="https://github.com/google-deepmind/deepmind-research/tree/master/byol">[code]</a>

**<< SwAV >>** \
Unsupervised Learning of Visual Features by Contrasting Cluster Assignments, NeurIPS 2020
<a href="https://arxiv.org/abs/2006.09882">[paper]</a> <a href="https://github.com/facebookresearch/swav">[code]</a>

**<< DenseCL >>** \
Dense Contrastive Learning for Self-Supervised Visual Pre-Training, CVPR 2021
<a href="https://arxiv.org/abs/2011.09157">[paper]</a> <a href="https://github.com/WXinlong/DenseCL">[code]</a>

**<< MOCOv3 >>** \
An Empirical Study of Training Self-Supervised Vision Transformers, ICCV 2021
<a href="https://arxiv.org/abs/2104.02057">[paper]</a> <a href="https://github.com/facebookresearch/moco-v3">[code]</a>

**<< MAE >>** \
Masked Autoencoders Are Scalable Vision Learners, CVPR 2022
<a href="https://arxiv.org/abs/2111.06377">[paper]</a> <a href="https://github.com/facebookresearch/mae">[code]</a>

**<< Stable Diffusion >>** \
High-resolution image synthesis with latent diffusion models., CVPR 2022
<a href="https://arxiv.org/abs/2112.10752">[paper]</a> <a href="https://github.com/CompVis/latent-diffusion">[code]</a>

**<< DINOv2 >>** \
DINOv2: Learning Robust Visual Features without Supervision, arxiv 2023
 <a href="https://arxiv.org/abs/2304.07193">[paper]</a> <a href="https://github.com/facebookresearch/dinov2">[code]</a> \
Vision Transformers Need Registers, arxiv 2023 <a href="https://arxiv.org/abs/2309.16588">[paper]</a>

--------

If you found our survey useful for your research, please consider citing:
```
@article{simeoni2023survey,
  author    = {Sim{\'e}oni, Oriane and Puy, Gilles and Zablocki, {\'E}loi and P{\'e}rez, Patrick},
  title     = {Unsupervised Object Localization in the Era of Self-Supervised ViTs: A Survey},
  journal={arXiv preprint arXiv:2310.12904},
  year={2023}
}
```
