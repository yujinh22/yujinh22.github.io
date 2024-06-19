---
title: "DRAGON: Drone and Ground Gaussian Splatting for 3D Building Reconstruction"
collection: publications
permalink: /publication/dragon
excerpt: 'Description'
date: 2024-07-22
Conference: ICCP 2024
imageurl: '/images/profile.png' 
paperurl: '/files/paper1.pdf'
github: https://github.com/yujinh22/dragon/
citation: '<strong>Y. Ham</strong>, M. Michalkiewicz, G. Balakrishnan (2024). &quot;DRAGON: Drone and Ground Gaussian Splatting for 3D Building Reconstruction&quot; <i>arXiv preprint</i> arXiv:2311.18064.'
---
<div style="text-align:center;">
  <p style="color:gray">ICCP 2024</p>

  <strong><a href="https://yujinh22.github.io/"> Yujin Ham</a><sup>1</sup></strong>, <a href="https://yujinh22.github.io/">
Mateusz Michalkiewicz</a><sup>1</sup>, <a href="https://www.guhabalakrishnan.com/">Guha Balakrishnan</a><sup>1,*</sup><br>

  <sup>1</sup>Rice University<br>
  <sup>*</sup>Corresponding author: guha@rice.edu<br>
  <br>
</div>

[<i class="ai ai-arxiv-square ai-fw"></i> arXiv](https://arxiv.org/abs/2311.18064){:.btn .btn-dark style="text-decoration: none;"} [<i class="fas fa-fw fa-file-pdf"></i> Paper](/../../files/gelda.pdf){:.btn .btn-dark style="text-decoration: none;"} [<i class="fab fa-fw fa-github"></i> Code](https://github.com/krishk97/gelda/){:.btn .btn-dark style="text-decoration: none;"} 
{: style="text-align: center"}

<center><img src = '/images/publications/gelda/pipeline_gelda.png'></center>

## Abstract
<p style="text-align:justify;">
  Bias analysis is a crucial step in the process of creating fair datasets for training and evaluating computer vision models. The bottleneck in dataset analysis is annotation, which typically requires: (1) specifying a list of attributes relevant to the dataset domain, and (2) classifying each image-attribute pair. While the second step has made rapid progress in automation, the first has remained human-centered, requiring an experimenter to compile lists of in-domain attributes. However, an experimenter may have limited foresight leading to annotation "blind spots," which in turn can lead to flawed downstream dataset analyses. To combat this, we propose GELDA, a nearly automatic framework that leverages large generative language models (LLMs) to propose and label various attributes for a domain. GELDA takes a user-defined domain caption (e.g., "a photo of a bird," "a photo of a living room") and uses an LLM to hierarchically generate attributes. In addition, GELDA uses the LLM to decide which of a set of vision-language models (VLMs) to use to classify each attribute in images. Results on real datasets show that GELDA can generate accurate and diverse visual attribute suggestions, and uncover biases such as confounding between class labels and background features. Results on synthetic datasets demonstrate that GELDA can be used to evaluate the biases of text-to-image diffusion models and generative adversarial networks. Overall, we show that while GELDA is not accurate enough to replace human annotators, it can serve as a complementary tool to help humans analyze datasets in a cheap, low-effort, and flexible manner.
</p>

## Citation
```bibitex
@article{kabra2023gelda,  
  title={GELDA: A generative language annotation framework to reveal visual biases in datasets}, 
  author={Kabra, Krish and Lewis, Kathleen M and Balakrishnan, Guha},
  journal={arXiv preprint arXiv:2311.18064}, 
  year={2023}
}
```

This paper is about the number 2. The number 3 is left for future work.

[Download paper here](http://academicpages.github.io/files/paper2.pdf)

Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2).