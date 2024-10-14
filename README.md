<div align="center"><h1> MedDet: Generative Adversarial Distillation for Efficient Cervical Disc Herniation Detection <br>
  <sub><sup><a href="https://ieeebibm.org/BIBM2024/">BIBM 2024 Oral</a></sup></sub> 
</h1>

[Zeyu Zhang](https://steve-zeyu-zhang.github.io)<sup>\*</sup>, [Nengmin Yi](https://www.researchgate.net/scientific-contributions/Nengmin-Yi-2249685869)<sup>\*</sup>, [Shengbo Tan](https://dblp.org/pid/205/0179.html)<sup>\*</sup>, [Ying Cai](https://ieeexplore.ieee.org/author/37087137422)<sup>✉</sup>, [Yi Yang](https://www.researchgate.net/scientific-contributions/Yi-Yang-2208407378), [Lei Xu](https://www.researchgate.net/profile/Lei-Xu-106), [Qingtai Li](https://pubmed.ncbi.nlm.nih.gov/?term=Li+Q&cauthor_id=38902109), [Zhang Yi](https://scholar.google.com.hk/citations?user=kCtQkrkAAAAJ), [Daji Ergu](https://ieeexplore.ieee.org/author/37085795653), [Yang Zhao](https://yangyangkiki.github.io/)

<sup>*</sup>Equal contribution
<sup>✉</sup>Corresponding author: caiying34@yeah.net

[![Website](https://img.shields.io/badge/Website-Demo-fedcba?style=flat-square)](https://steve-zeyu-zhang.github.io/MedDet/) [![arXiv](https://img.shields.io/badge/arXiv-2409.00204-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.00204) [![Papers With Code](https://img.shields.io/badge/Papers%20With%20Code-555555.svg?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgd2lkdGg9IjUxMiIgIGhlaWdodD0iNTEyIiA+PHBhdGggZD0iTTg4IDEyOGg0OHYyNTZIODh6bTE0NCAwaDQ4djI1NmgtNDh6bS03MiAxNmg0OHYyMjRoLTQ4em0xNDQgMGg0OHYyMjRoLTQ4em03Mi0xNmg0OHYyNTZoLTQ4eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PHBhdGggZD0iTTEwNCAxMDRWNTZIMTZ2NDAwaDg4di00OEg2NFYxMDR6bTMwNC00OHY0OGg0MHYzMDRoLTQwdjQ4aDg4VjU2eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PC9zdmc+)]() [![BibTeX](https://img.shields.io/badge/BibTeX-Citation-eeeeee?style=flat-square)](https://steve-zeyu-zhang.github.io/MedDet/static/scholar.html)

</div>

_Cervical disc herniation (CDH) is a prevalent musculoskeletal disorder that significantly impacts health and requires labor-intensive analysis from experts. Despite advancements in automated detection of medical imaging, two significant challenges hinder the real-world application of these methods. First, the computational complexity and resource demands present a significant gap for real-time application. Second, noise in MRI reduces the effectiveness of existing methods by distorting feature extraction. To address these challenges, we propose three key contributions: Firstly, we introduced <b>MedDet</b>, which leverages the multi-teacher single-student knowledge distillation for model compression and efficiency, meanwhile integrating generative adversarial training to enhance performance. Additionally, we customize the second-order nmODE to improve the model's resistance to noise in MRI. Lastly, we conducted comprehensive experiments on the CDH-1848 dataset, achieving up to a <b>5%</b> improvement in mAP compared to previous methods. Our approach also delivers over <b>5</b> times faster inference speed, with approximately <b>67.8%</b> reduction in parameters and <b>36.9%</b> reduction in FLOPs compared to the teacher model. These advancements significantly enhance the performance and efficiency of automated CDH detection, demonstrating promising potential for future application in clinical practice._

<img src="static/images/main.svg" alt="main" style="width:100%;">

## Citation

```
@article{zhang2024meddet,
  title={MedDet: Generative Adversarial Distillation for Efficient Cervical Disc Herniation Detection},
  author={Zhang, Zeyu and Yi, Nengmin and Tan, Shengbo and Cai, Ying and Yang, Yi and Xu, Lei and Li, Qingtai and Yi, Zhang and Ergu, Daji and Zhao, Yang},
  journal={arXiv preprint arXiv:2409.00204},
  year={2024}
}
```
