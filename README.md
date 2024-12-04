# <p align=center>Awesome Medical Image Registration</p>
[![Static Badge](https://img.shields.io/badge/MICCAI-SIG_BIR-%2337677e?style=flat&labelColor=%23ececec&link=https%3A%2F%2Fmiccai.org%2Findex.php%2Fspecial-interest-groups%2Fbir%2F)](https://miccai.org/index.php/special-interest-groups/bir/) ![Static Badge](https://img.shields.io/badge/MICCAI-Learn2Reg-%23214f5f?labelColor=%23ececec&link=https%3A%2F%2Flearn2reg.grand-challenge.org%2F)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

<p align=center>A curation of medical image registration papers and source codes. This repository is actively maintained by MICCAI SIG-BIR.</p>

## *Description*
The importance of image registration in medical imaging is underrepresented at MICCAI, largely due to the complexity of applying deep learning to its ill-posed nature without real ground truth. In response, the ***MICCAI Special Interest Group in Biomedical Image Registration ([MICCAI SIG-BIR](https://miccai.org/index.php/special-interest-groups/bir/))*** is launching several initiatives aimed at uniting the fragmented image registration community and promoting research in the field. One such initiative is the creation of an ***Awesome Medical Image Registration*** GitHub page that will curate well-documented, out-of-the-box code applicable to at least two *Learn2Reg* tasks. This repository is designed to serve that purpose.

## *Learn2Reg Tasks*
Learn2Reg is a public computational challenge organized by MICCAI SIG-BIR, featuring 12 datasets with labels and multiple active leaderboards. You can explore more at **learn2reg.grand-challenge.org**
<p align=center><img src="https://github.com/sigbir/awesome-medical-image-registration/blob/main/figs/L2R_tasks_.jpg" width="800"/></p>

## *Paper & Code Collection*

```
Syntax:
*  **Publication Title**, First Author et al.
    *  :newspaper: [Journal/Conference Name] 
    *  :computer:  [*Learn2Reg Tasks*] 
    *  :link: [Paper Link][GitHub Link]
```
*  **ConvexAdam: Self-Configuring Dual-Optimisation-Based 3D Multitask Medical Image Registration**, Siebert et al.
    *  :newspaper: [IEEE TMI 2024]
    *  :computer: [*Abdomen MR-CT*, *Abdomen CT-CT*, *OASIS*]
    *  :link: [[Paper](https://ieeexplore.ieee.org/document/10681158)][[GitHub](https://github.com/multimodallearning/convexAdam)]
*  **Fourier-Net+: Leveraging Band-Limited Representation for Efficient 3D Medical Image Registration**, Xi et al.
    *  :newspaper: [AAAI 2023, arXiv 2024] 
    *  :computer: [*OncoReg*, *NLST*, *ThoraxCBCT*]
    *  :link: [[Paper (AAAI)](https://doi.org/10.1609/aaai.v37i1.25182)][Paper (arXiv)](https://arxiv.org/abs/2307.02997)][[GitHub](https://github.com/xi-jia/Fourier-Net)]
*  **Vector Field Attention for Deformable Image Registration**, Liu et al.
    *  :newspaper: [arXiv preprint 2024]
    *  :computer: [*NLST*, *OASIS*, *LUMIR*]
    *  :link: [[Paper](https://arxiv.org/abs/2407.10209)][[GitHub](https://github.com/yihao6/vfa/)]
*  **Learning Physics-Inspired Regularization for Medical Image Registration with Hypernetworks**, Reithmeir et al.
    *  :newspaper: [SPIE MI 2024]
    *  :computer: [*Lung CT*, *NLST*]
    *  :link: [[Paper](https://arxiv.org/pdf/2311.08239)][[GitHub](https://github.com/annareithmeir/elastic-regularization-hypermorph)]
*  **TransMorph: Transformer for unsupervised medical image registration**, Chen et al.
    *  :newspaper: [MedIA 2022]
    *  :computer: [*OASIS*, *LUMIR*] 
    *  :link: [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841522002432)][[GitHub](https://github.com/junyuchen245/TransMorph_Transformer_for_Medical_Image_Registration)]
*  **U-Net vs Transformer: Is U-Net Outdated in Medical Image Registration?**, Xi et al.
    *  :newspaper: [MICCAI-MLMI 2022] 
    *  :computer: [*NLST*, *OASIS*] 
    *  :link: [[Paper](https://arxiv.org/abs/2208.04939)][[GitHub](https://github.com/xi-jia/LKU-Net)]
*  **Unsupervised Multi-Modal Medical Image Registration via Discriminator-Free Image-to-Image Translation**, Chen et al.
    *  :newspaper: [IJCAI 2022] 
    *  :computer: [*Abdomen MR-CT*, *Lung CT*] 
    *  :link: [[Paper](https://www.ijcai.org/proceedings/2022/0117.pdf)][[GitHub](https://github.com/heyblackC/DFMIR)]
*  **Learning a deformable registration pyramid**, Gunnarsson et al.
    *  :newspaper: [MICCAI Learn2Reg 2021] 
    *  :computer: [*Abdomen MR-CT*, *OASIS*, *Lung CT*] 
    *  :link: [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-71827-5_10)][[GitHub](https://github.com/ngunnar/learning-a-deformable-registration-pyramid)]
*  **Attention-based Deep Learning Registration (ADLReg)**, Pan et al.
    *  :newspaper: [-, 2021]
    *  :computer: [*Abdomen MR-CT*, *Abdomen CT-CT*, *OASIS*]
    *  :link: [[GitHub](https://github.com/WinterPan2017/ADLReg)]
*  **MONAI Tutorials**, MONAI NVIDIA.
    *  :newspaper: [-, 2021] 
    *  :computer: [*NLST*, *OASIS*] 
    *  :link: [[GitHub](https://github.com/Project-MONAI/tutorials/tree/main/3d_registration)]
*  **Deep learning based registration using spatial gradients and noisy segmentation labels**, Estienne et al.
    *  :newspaper: [MICCAI Learn2Reg, 2020] 
    *  :computer: [*Hippocampus MR*, *Abdomen CT-CT*] 
    *  :link: [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-71827-5_11)][[GitHub-Hippocampus](https://github.com/TheoEst/hippocampus_registration)][[GitHub-Abdomen-CT-CT](https://github.com/TheoEst/abdominal_registration)]
*  **SimpleElastix for abdomen CT-CT registration**, Fourcade
    *  :newspaper: [-, 2020]
    *  :computer: [*Abdomen CT-CT*]
    *  :link: [[Paper](https://ieeexplore.ieee.org/document/5338015)][[GitHub](https://github.com/fconstance/Learn2Reg_Task2_SimpleElastix)]
*  **Large Deformation Diffeomorphic Image Registration with Laplacian Pyramid Networks**, Mok et al.
    *  :newspaper: [MICCAI, 2020]
    *  :computer: [*OASIS*]
    *  :link: [[Paper](https://arxiv.org/abs/2006.16148)][[GitHub](https://github.com/cwmok/LapIRN)]
*  **SITReg: Multi-resolution architecture for symmetric, inverse consistent, and topology preserving image registration**, Joel Honkamaa and Pekka Marttinen.
    *  :newspaper: [MELBA 2024, 1st place in the L2R LUMIR challenge]
    *  :computer: [*LUMIR*, *OASIS*, *NLST*]
    *  :link: [[Paper](https://doi.org/10.59275/j.melba.2024-276b)][[GitHub](https://github.com/honkamj/SITReg)]
##
<p align="center"> <a href="https://miccai.org/index.php/special-interest-groups/bir/" target="_blank"><img src="https://github.com/sigbir/awesome-medical-image-registration/blob/main/figs/sigbir_logo.jpg" width="180"/></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.google.com/search?q=Learn2Reg+Grand+Challenge&sca_esv=7742ccf3e574a415&sca_upv=1&ei=uUbyZrW8IbCXwbkP4p3KmQI&ved=0ahUKEwj1_LK95dqIAxWwSzABHeKOMiMQ4dUDCA8&uact=5&oq=Learn2Reg+Grand+Challenge&gs_lp=Egxnd3Mtd2l6LXNlcnAiGUxlYXJuMlJlZyBHcmFuZCBDaGFsbGVuZ2UyBRAhGKABMgUQIRigATIFECEYoAEyBRAhGKABMgUQIRirAjIFECEYqwJIjRxQ3wRYvRpwAXgBkAEAmAFvoAGnDKoBBDEyLjS4AQPIAQD4AQGYAhGgAtkMwgIKEAAYsAMY1gQYR8ICCxAAGIAEGJECGIoFwgIFEAAYgATCAgQQABgewgIIEAAYgAQYogTCAggQABiiBBiJBZgDAIgGAZAGCJIHBDcuMTCgB5FD&sclient=gws-wiz-serp" target="_blank"><img src="https://github.com/sigbir/awesome-medical-image-registration/blob/main/figs/l2r_logo_21.png" width="90"/></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://miccai.org/" target="_blank"><img src="https://github.com/sigbir/awesome-medical-image-registration/blob/main/figs/miccai_logo2.jpg" width="100"/></a></p>
