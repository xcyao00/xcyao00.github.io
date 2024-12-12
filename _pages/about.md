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

🧑‍🎓 About Me
======
Hello! I'm Xincheng Yao (姚欣成), a Ph.D. candidate at [<u>Shanghai Jiao Tong University (SJTU)</u>](https://www.sjtu.edu.cn), where I'm working under the guidance of [<u>Prof. Chongyang Zhang</u>](https://faculty.sjtu.edu.cn/zhangchongyang/zh_CN/index.htm). 

I have received the B.S. degree in information
engineering from Shanghai Jiao Tong
University, China, in 2021. And I'm currently working
toward the Ph.D. degree in information and communication
engineering.

My academic interests are about **Deep Learning**, **Computer Vision** and **Anomaly Detection**, with a specific focus on **Image and Multi-modal Anomaly Detection**. Recently, my research has mainly been centered on how to design more general anomaly detection models, including **Multi-class Anomaly Detection**, **Zero/Few-shot Anomaly Detection**, **Class-Agnostic/Generalizable Anomaly Detection**, and also the application of large vision language models in anomaly detection tasks. In the anomaly detetion field, I have published
multiple papers at the top CV and AI conferences, including CVPR, NeurIPS, ICCV, ECCV, and AAAI.

If you find my research intriguing, please don't hesitate to contact with me by my email **i-dover@sjtu.edu.cn**. I welcome any inquries or discussions regarding my work! 😊

🔥 News
======
* 2024.09: 👏👏👏 Our paper [ResAD: A Simple Framework for Class-Generalizable Anomaly Detection](https://arxiv.org/abs/2410.20047), which can address **Class-Generalizable Anomaly Detection**, is accpected by NuerIPS 2024 as a **spotlight** paper.
   
* 2024.07: 👏👏👏 Our paper [Hierarchical Gaussian Mixture Normalizing Flow Modeling for Unified Anomaly Detection](https://arxiv.org/abs/2403.13349), which can address **Multi-Class Anomaly Detection**, is accpected by ECCV 2024.

* 2023.07: 👏👏👏 Our paper [Focus the Discrepancy: Intra- and Inter-Correlation Learning for Image Anomaly Detection](https://arxiv.org/abs/2308.02983), which proposed a novel **Multi-View Anomaly Detection Framework**, is accpected by ICCV 2023.

* 2023.06: 👏👏👏 Our paper [CKT: Cross-Image Knowledge Transfer for Texture Anomaly Detection](https://arxiv.org/abs/2207.01463), which can achive effective **Knowledge Transfer among Normal Images**, is accpected by ICIP 2023.

* 2023.03: 👏👏👏 Our paper [Explicit Boundary Guided Semi-Push-Pull Contrastive Learning for Supervised Anomaly Detection](https://arxiv.org/abs/2207.01463), which can address **Few-Shot Supervised Anomaly Detection**, is accpected by CVPR 2023.

* 2022.12: 👏👏👏 Our paper [One-for-All: Proposal Masked Cross-Class Anomaly Detection](https://ojs.aaai.org/index.php/AAAI/article/view/25604), which can address **Multi-Class and Cross-Class Anomaly Detection**, is accpected by AAAI 2023.

📃 Publications
======
#### [<u>First-Authored Peer-Reviewed Publications</u>](#publications1)
#### [<u>Other Peer-Reviewed Publications</u>](#publications2)


<a id="publications1"></a>
### First-Authored Peer-Reviewed Publications
  1. ResAD: A Simple Framework for Class-Generalizable Anomaly Detection [[Paper]](https://arxiv.org/abs/2410.20047) [[Code]](https://github.com/xcyao00/ResAD)
   
      **Xincheng Yao**, Zixin Chen, Chao Gao, Guangtao Zhai, Chongyang Zhang*, The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024.

  2. Hierarchical Gaussian Mixture Normalizing Flow Modeling for Unified Anomaly Detection [[Paper]](https://arxiv.org/abs/2403.13349) [[Code]](https://github.com/xcyao00/HGAD)
   
      **Xincheng Yao**, Ruoqi Li, Zefeng Qian, Lu Wang, Chongyang Zhang*, The 18th European Conference on Computer Vision (ECCV), 2024.

  3. Focus the Discrepancy: Intra- and Inter-Correlation Learning for Image Anomaly Detection [[Paper]](https://arxiv.org/abs/2308.02983) [[Code]](https://github.com/xcyao00/FOD)
   
      **Xincheng Yao**, Ruoqi Li, Zefeng Qian, Yan Luo, Chongyang Zhang*, The International Conference on Computer Vision (ICCV), 2023.

  4. Explicit Boundary Guided Semi-Push-Pull Contrastive Learning for Supervised Anomaly Detection [[Paper]](https://arxiv.org/abs/2207.01463) [[Code]](https://github.com/xcyao00/BGAD)

      **Xincheng Yao**, Ruoqi Li, Jing Zhang, Jun Sun, Chongyang Zhang*, The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023.

  5. One-for-All: Proposal Masked Cross-Class Anomaly Detection [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25604) [[Code]](https://github.com/xcyao00/PMAD)

      **Xincheng Yao**, Chongyang Zhang*, Ruoqi Li, Jun Sun, Zhenyu Liu, The 37th Annual AAAI Conference on Artificial Intelligence (AAAI), 2023.
   
   6. Multi-Scale Feature Distillation for Anomaly Detection [[Paper]](https://ieeexplore.ieee.org/abstract/document/9665143)

      **Xincheng Yao**, Ruoqi Li, Chongyang Zhang*, Kefeng Huang, Kaiyu Sun, The 27th International Conference on Mechatronics and Machine Vision in Practice (M2VIP), 2021.

<a id="publications2"></a>
### Other Peer-Reviewed Publications
  1. CKT: Cross-Image Knowledge Transfer for Texture Anomaly Detection [[Paper]](https://ieeexplore.ieee.org/abstract/document/10222386)
   
      Zixin Chen, **Xincheng Yao**, Zhenyu Liu, Baozhu Zhang, Chongyang Zhang*, The 2023 IEEE International Conference on Image Processing (ICIP), 2023.

  2. Enhanced Anomaly Detection Using Spatial-Alignment and Multi-scale Fusion [[Paper]](https://link.springer.com/chapter/10.1007/978-981-97-8493-6_21) [[Code]](https://github.com/JiaoKM/GPD_dataset)
   
      Keming Jiao, **Xincheng Yao**, Lu Wang, Baozhu Zhang, Zhenyu Liu, Chongyang Zhang*, The Chinese Conference on Parttern Recognition and Computer Vision (PRCV), 2024.


🥇 Selected Awards
======
* National Scholarship for Postgraduates (**the highest scholarship for Ph.D.**), 2023.09.

* First-class Scholarship for Postgraduates, SJTU, 2022.09, 2023.09, 2024.09.
   
* National Encouragement Scholarship, 2018.09, 2019.09, 2020.09.


📝 Academic Service
======
* Conference Reviewer, CVPR, ECCV, ACM MM, etc.

* Journal Reviewer, Engineering Applications of Artificial Intelligence, IEEE Trans. Neural Networks Learn. Syst., IEEE Trans. Circuits Syst. Video Technol., etc.


🎓 Eduacations
======
* **2021.09 - present, Shanghai Jiao Tong University**

   School of Electronic Information and Electrical Engineering

   **Ph.D. Candidate** in Information and Communication Engineering   &emsp;&emsp;&emsp;  **Advisor**: [<u>Chongyang Zhang</u>](https://faculty.sjtu.edu.cn/zhangchongyang/zh_CN/index.htm)

* **2017.09 - 2021.06, Shanghai Jiao Tong University**

   School of Electronic Information and Electrical Engineering

   **B.S.** in Information Engineering


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=QltdrDBXR7cYztdXsLCBfSeruYl8EMVZ7i3zpSoGzP4&co=2d78ad&cmo=3acc3a&cmn=ff5353&ct=ffffff'></script>
