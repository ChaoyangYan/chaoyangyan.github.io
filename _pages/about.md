---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# About me

I am currently a third-year doctoral student at Centre for Bioinformatics and Intelligent Medicine ([**BioAIMed Lab**](http://bio.nankai.edu.cn/)), Nankai University, supervised by Prof. [Jian Liu](http://bio.nankai.edu.cn/profiles/liu.html). 

My research lies at the intersection of artificial intelligence and healthcare. I mainly focus on computational pathology and multi-omics data analysis. My objective is to develop advanced AI techniques to enhance in-depth cancer research.

I received my bachelor and master degree in control science and engineering from Nanjing University of Information Science & Technology (NUIST), China. I was supervised by Prof. [Jun Xu](https://faculty.nuist.edu.cn/jxu/zh_CN/index.htm) during my postgraduate period.

I once worked in [Zhejiang Dahua Technology Co., Ltd.](https://www.dahuatech.com/) for one year as an full-time algorithm engineer in 2021.

Now, I have started a new journey (a journey full of glory and dreams) and I believe everything will be fine. If you’re interested in my work or encounter any research problems, please feel free to [contact me](mailto:cyyan@mail.nankai.edu.cn). 


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 One paper was accepted by [ISMB/ECCB 2025](https://www.iscb.org/ismbeccb2025/home) (Acc. Rate: 17.5%)
- *2024.04*: &nbsp;🎉🎉 One paper was accepted by [ISMB 2024](https://www.iscb.org/ismb2024/home) (Acc. Rate: 18.2%)
- *2023.07*: &nbsp;🎉🎉 A presentation was made at Northeastern University, Shenyang, China 
- *2022.09*: &nbsp; A new journey was started in Nankai University, Tianjin, China 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMB/ECCB 2025</div><img src='images/ISMB2025_CUCA_main.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ISMB/ECCB 2025**]
**Predicting fine-grained cell types from histology images through cross-modal learning in spatial transcriptomics**    
**Chaoyang Yan**, Zhihan Ruan, Songkang Chen, Yichen Pan, Xue Han, Yuanyu Li, Jian Liu    
[[Paper: TBD](https://cyyan.cn/)][[Code](https://github.com/lyotvincent/CUCA)]<img src="https://img.shields.io/github/stars/lyotvincent/CUCA?style=social"/>    
A cross-modal unified representation learning framework (CUCA) is proposed for identifying fine-grained cell types from histology images. CUCA is trained on paired morphology-molecule spatial transcriptomics data, enabling it to infer fine-grained cell abundances solely from pathology images.   
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMB 2024</div><img src='images/ISMB2024_PhiHER2_main.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ISMB 2024**]
**PhiHER2: Phenotype-informed weakly supervised model for HER2 status prediction from pathological images**    
**Chaoyang Yan**, Jialiang Sun, Yiming Guan, Jiuxin Feng, Hong Liu, Jian Liu    
[[Paper](https://doi.org/10.1093/bioinformatics/btae236)][[Code](https://github.com/gatsby2016/PhiHER2)]<img src="https://img.shields.io/github/stars/gatsby2016/PhiHER2?style=social"/>    
PhiHER2 is a phenotype-informed multiple instance learning architecture for the prediction of the HER2 molecular status from pathological images of breast cancer. It provides valuable insights into the heterogeneity of morphological patterns associated with molecular biomarkers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Fundamental Research 2022</div><img src='images/FR2024_DeepPathTNBC_main.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Fundamental Research 2022**]
**Deep learning framework for comprehensive molecular and prognostic stratifications of triple-negative breast cancer**    
Shen Zhao\*, **Chaoyang Yan\***, Hong Lv\*, et.al     
[[Paper](https://doi.org/10.1016/j.fmre.2022.06.008)]  
A deep learning-based framework is devised for comprehensive predictions of molecular features, subtypes and prognosis from pathological WSIs. It enables comprehensive stratifications of TNBC patients and provide valuable information for therapeutic decision-making.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MRM 2022</div><img src='images/MRM2024_S2aNet_main.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Magnetic Resonance in Medicine 2022**]
**Scale- and Slice-aware Net (S2aNet) for 3D segmentation of organs and musculoskeletal structures in pelvic MRI**    
**Chaoyang Yan**, Jing-Jing Lu, Kang Chen, Lei Wang, Haoda Lu, Li Yu, Mengyan Sun, Jun Xu     
[[Paper](https://doi.org/10.1002%2Fmrm.28939)][[Code](https://github.com/gatsby2016/Scale-Slice-awareNet)]<img src="https://img.shields.io/github/stars/gatsby2016/Scale-Slice-awareNet?style=social"/>  
S2aNet is the first model to achieve 3D dense segmentation for 54 organs and musculoskeletal structures in female pelvic MR images. It is an efficient, accurate, and automated segmentation model that can be extended to the 3D digital anatomy for personalized body.    
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISBI 2020</div><img src='images/ISBI2020_main.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ISBI 2020**]
**Prior-aware CNN with multi-task learning for colon images analysis**    
**Chaoyang Yan**, Jun Xu, Jiawei Xie, Chengfei Cai, Haoda Lu     
[[Paper](https://doi.org/10.1109/ISBI45749.2020.9098703)][[Code](https://github.com/gatsby2016/Pathological-Multi-Task-on-Prior)]<img src="https://img.shields.io/github/stars/gatsby2016/Pathological-Multi-Task-on-Prior?style=social"/>  
A prior-aware CNN framework with multi-task learning is proposed for automatic gland segmentation and images grading diagnosis simultaneously. It makes pathological image analysis more applicable and interpretable inspired by the clinical pathological diagnostic criteria.    
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CMPB 2020</div><img src='images/CMPB2020_main.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Computer Methods and Programs in Biomedicine 2020**]
**Automated gleason grading on prostate biopsy slides by statistical representations of homology profile**    
**Chaoyang Yan**, Kazuaki Nakane, Xiangxue Wang, et.al       
[[Paper](https://doi.org/10.1016/j.cmpb.2020.105528)]      
SRHP is a novel Statistical Representation of Homology Profile approach for automated Gleason grading on prostate biopsy slides. It captures the topological characteristics and the degree of connectivity between nuclei around the gland. These characteristics of homology profile are interpretable, visually meaningful and highly consistent with the rubric employed by pathologists.     
</div>
</div>

# 🎖 Honors and Awards
- *2020.12* National Scholarship by Ministry of Education of China.

# 📖 Educations
- *2022.09 - now*, Nankai University (NKU), Computer science and technology, doctor's degree.     
- *2018.09 - 2021.06*, Nanjing University of Information Science & Technology (NUIST), Control science and engineering, master's degree.     
- *2014.09 - 2018.06*, NUIST, Measurement and control technology and instrumentation, bachelor's degree.    

# 💻 Open Projects
- [[Augmentation-PyTorch-Transforms](https://github.com/gatsby2016/Augmentation-PyTorch-Transforms)]<img src="https://img.shields.io/github/stars/gatsby2016/Augmentation-PyTorch-Transforms?style=social"/>    
Image data augmentation on-the-fly by adding new class on transforms in PyTorch and torchvision, for Computational Pathology.
- [[FeatsVisDL](https://github.com/gatsby2016/FeatsVisDL)]<img src="https://img.shields.io/github/stars/gatsby2016/FeatsVisDL?style=social"/>
Attention \& Saliency maps and features visualization for deep learning models in pytorch.
- [[Fast-WSI-Prediction](https://github.com/gatsby2016/Fast-WSI-Prediction)]<img src="https://img.shields.io/github/stars/gatsby2016/Fast-WSI-Prediction?style=social"/>
Unofficial implementation for ScanNet (a fast WSI prediction method, [paper](https://ieeexplore.ieee.org/abstract/document/8354169/)) in PyTorch.

# 💬 Personal
- 🏃‍♂ Running: YANGZHOU JIANZHEN HALF MARATHON 2025, Finish Achievement 1h50min (21.0975km). 
- 🏃‍♂ Running: HUZHOU MARATHON 2024, Finish Achievement 1h55min (21.0975km). 
