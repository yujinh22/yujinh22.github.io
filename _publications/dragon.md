---
title: "DRAGON: Drone and Ground Gaussian Splatting for 3D Building Reconstruction"
collection: publications
link: '/publication/dragon'
excerpt: "A method for reconstructing 3D scenes of large buildings by integrating drone and ground-level images through iterative view synthesis in the intermediate levels."
date: 2024-7-22
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10644903'
imageurl: '/images/dragon_figure.jpg' 
# github: https://github.com/yujinh22/
# github: [metadata]
conference: ICCP 2024
citation: '<strong>Y. Ham</strong>, M. Michalkiewicz, G. Balakrishnan (2024). &quot;DRAGON: Drone and Ground Gaussian Splatting for 3D Building Reconstruction.&quot; <i>ICCP 2024</i>.'
---
<div style="text-align:center;">
  <p style="color:gray">ICCP 2024</p>

  <strong><a href="https://yujinh22.github.io/"> Yujin Ham</a><sup>1</sup></strong>, <a href="https://toomanymatts.github.io/">
Mateusz Michalkiewicz</a><sup>1</sup>, <a href="https://www.guhabalakrishnan.com/">Guha Balakrishnan</a><sup>1,*</sup><br>

  <sup>1</sup>Rice University<br>
  <br>
</div>

[<i class="fas fa-fw fa-file-pdf"></i> Paper](https://arxiv.org/pdf/2407.01761){:.btn .btn-dark style="text-decoration: none;"} [<i class="ai ai-arxiv-square ai-fw"></i> Data](https://drive.google.com/drive/folders/14UApt73KQqZYs6S3ymagYX13r7IHy1gw){:.btn .btn-dark style="text-decoration: none;"}
{: style="text-align: center"}

<center><img src = '/images/dragon.png'></center>

## Abstract
<p style="text-align:justify;">
  3D building reconstruction from imaging data is an important task for many applications ranging from urban planning to reconnaissance. Modern Novel View synthesis (NVS) methods like NeRF and Gaussian Splatting offer powerful techniques for developing 3D models from natural 2D imagery in an unsupervised fashion. These algorithms generally require input training views surrounding the scene of interest, which, in the case of large buildings, is typically not available across all camera elevations. In particular, the most readily available camera viewpoints at scale across most buildings are at near-ground (e.g., with mobile phones) and aerial (drones) elevations. However, due to the significant difference in viewpoint between drone and ground image sets, camera registration -- a necessary step for NVS algorithms -- fails. In this work we propose a method, DRAGON, that can take drone and ground building imagery as input and produce a 3D NVS model. The key insight of DRAGON is that intermediate elevation imagery may be extrapolated by an NVS algorithm itself in an iterative procedure with perceptual regularization, thereby bridging the visual feature gap between the two elevations and enabling registration. We compiled a semi-synthetic dataset of 9 large building scenes using Google Earth Studio, and quantitatively and qualitatively demonstrate that DRAGON can generate compelling renderings on this dataset compared to baseline strategies.
</p>

<!-- ## Results -->


## Citation
```bibitex
@inproceedings{ham2024dragon,
  title={Dragon: Drone and ground gaussian splatting for 3d building reconstruction},
  author={Ham, Yujin and Michalkiewicz, Mateusz and Balakrishnan, Guha},
  booktitle={2024 IEEE International Conference on Computational Photography (ICCP)},
  pages={1--12},
  year={2024},
  organization={IEEE}
}
```