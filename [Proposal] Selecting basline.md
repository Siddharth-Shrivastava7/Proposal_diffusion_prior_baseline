# [Proposal] Selecting basline
    

:bulb: Using the analysis to select the most suitable work as the baseline (to improve further with)

  
## Analysis 
 
### Comparision between Diffusion model based Segmentation works 

    
| Name | Code availablity | General___Comments  | Dataset used | Published or not |  Performance (in mIoU, of cityscapes or common dataset) | Input modality |
|:----------------------:|:-------------------:|:------------:|:-------------:|:--------------:|:----------------------:|:--------------------:|
|   [SegDiff: Image Segmentation with Diffusion Probabilistic Models](https://arxiv.org/pdf/2112.00390.pdf )   |  Yes   |                       |  **Cityscapes Val**, Vaihingen building, MoNuSeg | No  |   |              RGB image   |
|    [LABEL-EFFICIENT SEMANTIC SEGMENTATION WITH DIFFUSION MODELS](https://openreview.net/pdf?id=SlxSY2UZQT)   |   Yes  |                       |    FFHQ,CelebAMask,LSUN-Bedroom, ADE-Bedroom, LSUN-Cat, LSUN-Horse   | ICLR'22  |           |  RGB image   |
|    [Semantic Diffusion Network for semantic segmentation](https://proceedings.neurips.cc/paper_files/paper/2022/file/396446770f5e8496ca1feb02079d4fb7-Paper-Conference.pdf)    |    No     |                          |     ADE20K-val, Cityscapes-val.  |  NeurIPS'22       |         |    RGB image  |
| [Generative Semantic Segmentation](https://arxiv.org/pdf/2303.11316.pdf) |  Yes   |              |                             |  CVPR'23  |       | image conditioned mask generation problem (i think both rgb and label) | 
| [DDP: Diffusion Model for Dense Visual Prediction](https://arxiv.org/pdf/2303.17559.pdf) |  No   |                           |               |  No  |       | both RGB and label images| 
| [Let us Build Bridges: Understanding and Extending Diffusion Generative Models](https://arxiv.org/pdf/2208.14699.pdf) |  No   |              |                          |  NeurIPS'22 workshop  |       |  | 
| [BerDiff: Conditional Bernoulli Diffusion Model for Medical Image Segmentation](https://arxiv.org/pdf/2304.04429.pdf) |  No   |              |                             |  No  |       | Input image conditioning | 
| [MedSegDiff: Medical Image Segmentation with Diffusion Probabilistic Model](https://openreview.net/pdf?id=Jdw-cm2jG9) |  Yes  |              |                             |  MIDL'23  |       | Input image conditioning | 
| [MedSegDiff-V2: Diffusion based Medical Image Segmentation with Transformer](https://arxiv.org/pdf/2301.11798.pdf) |  No |              |                             |  No  |       |  | 
| [Ambiguous Medical Image Segmentation using Diffusion Models](https://arxiv.org/pdf/2304.04745.pdf) |  Yes |              |                             |  CVPR'23  |       | Input image conditioning | 
| [Diffusion Models for Implicit Image Segmentation Ensembles](https://arxiv.org/pdf/2112.03145.pdf) |  Yes |              |                             | No  |       |    Different input images conditioning |
| [Diffusion models as plug-and-play priors](https://arxiv.org/pdf/2206.09012.pdf) |  Yes  |              |                             | NeurIPS'22   |       |    Image and weak labels as inputs |
| [Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions](https://proceedings.neurips.cc/paper_files/paper/2021/file/67d96d458abdef21792e6d8e590244e7-Paper.pdf) |  Yes  |              |                             | NeurIPS'21   |       |    generating segmentaiton labels from categorical noise as input |
| [Stochastic Segmentation with Conditional Categorical Diffusion Models](https://arxiv.org/pdf/2303.08888.pdf) |  Yes  |              |                             | No   |       |   RGB image conditioning with categorical noise as input |

    
