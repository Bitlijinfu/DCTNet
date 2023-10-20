# DCTNet: A Heterogeneous Dual-Branch Multi-Cascade Network for Infrared and Visible Image Fusion (IEEE TIM2023)
This is the official repository for the paper of "[DCTNet: A Heterogeneous Dual-Branch Multi-Cascade Network for Infrared and Visible Image Fusion](https://ieeexplore.ieee.org/document/10288277)"
<br><font color="#FF0000" size=7>The code is opening soon.</font>
## Abstract
Deep learning has become a popular technique for infrared and visible image fusion due to its powerful feature representation abilities. Existing methods often employ the CNN, Transformer, or mixed CNN-Transformer to treat different modalities indiscriminately. However, we observe that these homogeneous fusion networks (i.e., same network for cross-modal) struggle to handle the specific characteristics of each modality, leading to fused images being contaminated with interference or lacking modality-specific information. To alleviate this issue, we propose a heterogeneous Dual-branch multi-cascade fusion network based on CNN and Transformer, named DCTNet, aims independently to maintain the focus of respective modalities, such as radiation intensity of infrared images and texture details of visible images. In DCTNet, the CNN branch is specifically designed to exploit local features in visible images by utillizing stacked residual dense CNNs, while the Transformer branch is tailored to model the long-range dependencies, capturing the overall temperature distribution and thermal patterns of a scene in infrared images by cascading residual Transformers. In addition, we introduce an Adaptive Fusion Interaction Module (AFIM) that leverages attention mechanisms to adaptively high-light informative regions in the fused feature maps. The module assigns weights to these regions based on their contributions and dynamically merges features from the dual-branch at multiple levels. Experimental results on three public datasets demonstrate that the proposed method outperforms state-of-the-art methods in terms of quantitative and qualitative evaluations. Moreover, we showcase the promising performance of DCTNet in downstream object detection and semantic segmentation applications on a widely-accepted benchmark.
## Citation
If this work is helpful to you, please cite it as:
```
@ARTICLE{DCTNet_TIM2023,
  author={Li, Jinfu and Liu, Lei and Song, Hong and Huang, Yuqi and Jiang, Junjun and Yang, Jian},
  journal={IEEE Transactions on Instrumentation and Measurement}, 
  title={DCTNet: A Heterogeneous Dual-Branch Multi-Cascade Network for Infrared and Visible Image Fusion}, 
  year={2023},
  pages={1-1},
  doi={10.1109/TIM.2023.3325520}}
```
If you have any questions, feel free to contact me (jinfuli2021@gmail.com).
