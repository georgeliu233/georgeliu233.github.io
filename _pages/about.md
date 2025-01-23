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

I am pursuing a Ph.D. in the School of Mechanical and Aerospace Engineering at Nanyang Technological University. My research endeavors are based in the [Automated Driving and Human-Machine System (AutoMan) Lab](https://lvchen.wixsite.com/automan), which is led by Prof. Chen Lyu. 

My research center on the realm of autonomous driving and machine learning. The objective is to develop AI agents for **predictive decisions-making** in autonomous driving techniques. My research interest include deep learning and reinforcement learning for prediction, planning, and decision-making framework modeling. 

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 Our team won the [Champion of 2024 Waymo Open Dataset Occupancy and Flow Prediction Challenge](http://cvpr2024.wad.vision/). Check out more for our [team report](https://storage.googleapis.com/waymo-uploads/files/research/2024%20Technical%20Reports/2024%20WOD%20Occupancy%20Flow%20Challenge%20-%201st%20Place%20-%20DOPP.pdf) and original implementation based on our [HPP paper](https://arxiv.org/abs/2402.02426).
- *2023.08*: &nbsp;🎉🎉 Our GameFormer paper has been selected as Oral Presentation for International Conference on Computer Vision (ICCV)! Code is also available!
- *2023.07*: &nbsp;🎉🎉 Our ITSC special session on [learning-powered prediction and decision-making](https://sites.google.com/view/itsc-lpad) has received 17 paper submissions, all of which were accepted. Congrats and looking forward to seeing you in Spain in September!
- *2023.07*: &nbsp;🎉🎉 Our GameFormer paper has been accepted by International Conference on Computer Vision (ICCV)! We will be releasing the code soon, so stay tuned for updates.
- *2023.07*: &nbsp;🎉🎉 Two of our papers on predictive decision-making/planning have been accepted by the International Conference on Intelligent Transportation Systems (ITSC)!
- *2023.06*: &nbsp;🎉🎉 Our team won the innovation award in the nuPlan Planning Challenge! Check out our [report](https://opendrivelab.com/e2ead/AD23Challenge/Track_4_AID.pdf) and [presentation](https://youtu.be/ZwhXilQKULY?t=1204) on our GameFormer Planner.
- *2023.06*: &nbsp;🎉🎉 Our team secured third place in the Waymo Open Dataset Motion Prediction Challenge! Our [report](https://storage.googleapis.com/waymo-uploads/files/research/2023%20Technical%20Reports/MP_3rd_GRT-R36.pdf) is available on [CVPR 2023
Workshop on Autonomous Driving](https://cvpr2023.wad.vision/).
- *2022.12*: &nbsp;🎉🎉 Our team won the Most Innovative Award and 3rd Place in both Track 1 and Track 2 at NeurIPS Driving SMARTS Competition! Check out our [presentation](https://smarts-project.github.io/assets/docs/aid_driving_smarts.pdf) on predictive decision-making at the [official competition site](https://smarts-project.github.io/archive/2022_nips_driving_smarts/).

# 📝 Publications 

## Recent Highlights

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2025</div><img src='images/hpp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hybrid-Prediction Integrated Planning for Autonomous Driving**

**Haochen Liu**, Zhiyu Huang, Wenhui Huang, Haohan Yang, Xiaoyu Mo, Chen Lv

**IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI), 2025**

[**Paper**](https://ieeexplore.ieee.org/abstract/document/10833731/) \| [**Project**](https://github.com/georgeliu233/HPP) \| [![](https://img.shields.io/github/stars/georgeliu233/HPP?style=social&label=Code Stars)](https://github.com/georgeliu233/HPP)

-  A collborative design and optimization framework for end-to-end autonomous driving system that integrates hybrid prediction forms and motion planning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/betopnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Reasoning Multi-Agent Behavioral Topology for Interactive Autonomous Driving**

**Haochen Liu**, Li Chen, Yu Qiao, Chen Lv, Hongyang Li

**Advances in Neural Information Processing Systems (NeurIPS), 2024**

[**Paper**](https://arxiv.org/abs/2409.18031) \| [**Project**](https://github.com/OpenDriveLab/BeTop) \| [![](https://img.shields.io/github/stars/OpenDriveLab/BeTop?style=social&label=Code Stars)](https://github.com/OpenDriveLab/BeTop) 

-  A synergistic framework for interactive behavior reasoning that enhances multi-agent prediction and planning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV (Oral) 2023</div><img src='images/gameformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GameFormer: Game-theoretic Modeling and Learning of Transformer-based Interactive Prediction and Planning for Autonomous Driving**

Zhiyu Huang\*, **Haochen Liu**\*, Chen Lv

**IEEE/CVF International Conference on Computer Vision (ICCV Oral), 2023**

[**Paper**](https://arxiv.org/abs/2303.05760) \| [**Project**](https://mczhi.github.io/GameFormer/) \| [![](https://img.shields.io/github/stars/MCZhi/GameFormer?style=social&label=Code Stars)](https://github.com/MCZhi/GameFormer) \| **GameFormer Planner** [![](https://img.shields.io/github/stars/MCZhi/GameFormer-Planner?style=social&label=Code Stars)](https://github.com/MCZhi/GameFormer-Planner) 

-  We address the interaction prediction problem by formulating it with hierarchical game theory and implementing it with Transformer networks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ITSC 2023</div><img src='images/opgp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Occupancy Prediction-Guided Neural Planner for Autonomous Driving**

 **Haochen Liu**, Zhiyu Huang, Chen Lv

**IEEE International Conference on Intelligent Transportation Systems (ITSC), 2023**

[**Paper**](https://arxiv.org/abs/2305.03303)\| [**Zhihu**](https://zhuanlan.zhihu.com/p/630045890)\| [**Project**](https://github.com/georgeliu233/OPGP) \| [![](https://img.shields.io/github/stars/georgeliu233/OPGP?style=social&label=Code Stars)](https://github.com/georgeliu233/OPGP) 

-  We propose a learning-based prediction-guided motion planner, that imitative planning trajectory is refined by transformed occupancy predictions in an intergated network.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div><img src='images/strajnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-modal Hierarchical Transformer for Occupancy Flow Field Prediction in Autonomous Driving**

 **Haochen Liu**, Zhiyu Huang, Chen Lv

**IEEE International Conference on Robotics and Automation (ICRA), 2023**

[**Paper**](https://ieeexplore.ieee.org/abstract/document/10160855) \| [**Project**](https://github.com/georgeliu233/STrajNet) \| [![](https://img.shields.io/github/stars/georgeliu233/STrajNet?style=social&label=Code Stars)](https://github.com/georgeliu233/STrajNet) 

-  We develop a multi-modal hierarchial Transformer sturcture for long-term occupancy and flow prediction fusing visual and vector features from perception.
</div>
</div>

## Talks
- *2024.12* **Reasoning Multi-Agent Behavioral Topology for Interactive Autonomous Driving*** in [ADHeart](www.zdjszx.com)
- *2024.06* **Interactive Prediction and Planning for Autonomous Driving: Method and Thoughts** in [ADHeart](www.zdjszx.com), online. [Link](https://www.bilibili.com/opus/943962468011474950?spm_id_from=333.999.0.0)
- *2024.06* **Prediction and Planning: Integration Methodology and Challenges** in CVPR'24 wE2EAD, [OpenDriveLab@Shanghai AI Lab](https://opendrivelab.com/), Shanghai. [Link](https://www.bilibili.com/video/BV11b421J76g/?spm_id_from=333.337.search-card.all.click) 

## Journal
- [Human-Guided Continual Learning for Personalized Decision-Making of Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/10844014) Haohan Yang, Yanxin Zhou, Jingda Wu, **Haochen Liu**, Lie Yang, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025**

- [Safety-aware human-in-the-loop reinforcement learning with shared control for autonomous driving](https://ieeexplore.ieee.org/abstract/document/10596046) Wenhui Huang, **Haochen Liu**, Zhiyu Huang, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2024**

- [Augmenting Reinforcement Learning with Transformer-based Scene Representation Learning for Decision-making of Autonomous Driving](https://arxiv.org/abs/2208.12263), **Haochen Liu**, Zhiyu Huang, Xiaoyu Mo, Chen Lv, **IEEE Transactions on Intelligent Vehicles (T-IV), 2024** [![](https://img.shields.io/github/stars/georgeliu233/Scene-Rep-Transformer?style=social&label=Code Stars)](https://github.com/georgeliu233/Scene-Rep-Transformer)
  
- [Differentiable Integrated Motion Prediction and Planning with Learnable Cost Function for Autonomous Driving](https://arxiv.org/abs/2207.10422), Zhiyu Huang, **Haochen Liu**, Jingda Wu, Chen Lv, **IEEE Transactions on Neural Networks and Learning Systems (T-NNLS), 2023** [![](https://img.shields.io/github/stars/MCZhi/DIPP?style=social&label=Code Stars)](https://github.com/MCZhi/DIPP)

- [Map-Adaptive Multimodal Trajectory Prediction Using Hierarchical Graph Neural Networks](https://dspace.lib.cranfield.ac.uk/bitstream/handle/1826/19830/Map-adaptive_multimodal_trajectory_prediction-2023.pdf?sequence=1), Xiaoyu Mo, Yang Xing, **Haochen Liu**, Chen Lv, **IEEE Robotics and Automation Letters (RA-L), 2023**
  
- [Conditional Predictive Behavior Planning with Inverse Reinforcement Learning for Human-like Autonomous Driving](https://arxiv.org/abs/2212.08787), Zhiyu Huang, **Haochen Liu**, Jingda Wu, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2023**
  
- [Map-Adaptive Multimodal Trajectory Prediction via Intention-Aware Unimodal Trajectory Predictors](https://ieeexplore.ieee.org/abstract/document/10323217/) Xiaoyu Mo, **Haochen Liu**, Zhiyu Huang, Xiuxian Li, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2023**

- [Quantitative identification of driver distraction: A weakly supervised contrastive learning approach](https://ieeexplore.ieee.org/abstract/document/10265761/) Haohan Yang, **Haochen Liu**, Zhongxu Hu, Anh-Tu Nguyen, Thierry-Marie Guerra, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2023**


## Conference
- [Learning Interaction-aware Motion Prediction Model for Decision-making in Autonomous Driving](https://arxiv.org/abs/2302.03939), Zhiyu Huang, **Haochen Liu**, Jingda Wu, Wenhui Huang, Chen Lv, **IEEE International Conference on Intelligent Transportation Systems (ITSC), 2023** ([**Best Paper Award Runner-up**](https://2023.ieee-itsc.org/best-paper-awards/)) [![](https://img.shields.io/github/stars/MCZhi/Predictive-Decision?style=social&label=Code Stars)](https://github.com/MCZhi/Predictive-Decision)

- [Dynamic Edge Caching via Online Meta-RL](https://ieeexplore.ieee.org/abstract/document/10191608/) Yinan Mao, Shiji Zhou, **Haochen Liu**, Zhi Wang, Wenwu Zhu, **International Joint Conference on Neural Networks, 2023**

- [Improved Deep Reinforcement Learning with Expert Demonstrations for Urban Autonomous Driving](https://arxiv.org/abs/2102.09243), **Haochen Liu**, Zhiyu Huang, Jingda Wu, Chen Lv, **IEEE Intelligent Vehicles Symposium (IV), 2022** 

## Preprints
- Coming soon


# 🎖 Honors and Awards
- *2024.06* [1st Place Winner, Waymo Open Dataset Occupancy and Flow Prediction Challenge](http://cvpr2024.wad.vision/), CVPR Workshop on Autonomous Driving
- *2023.06* [Innovation Award, nuPlan Planning Challenge](https://opendrivelab.com/AD23Challenge.html#nuplan_planning), CVPR Workshop on End-to-End Autonomous Driving 
- *2023.06* [3rd Place Winner, Waymo Open Dataset Motion Prediction Challenge](http://cvpr2023.wad.vision/), CVPR Workshop on Autonomous Driving
- *2022.12* [3rd Place Winner, Most Innovative Award, Driving SMARTS Competition](https://smarts-project.github.io/archive/2022_nips_driving_smarts/competition/), NeurIPS Competition Track \| [\[slides\]](https://smarts-project.github.io/assets/docs/aid_driving_smarts.pdf)
- *2022.06* [2nd Place Winner, Waymo Open Dataset Occupancy and Flow Prediction Challenge](http://cvpr2022.wad.vision/), CVPR Workshop on Autonomous Driving

# 📖 Educations
- *2021.08 - Now*, Doctor of Philosophy, Nanyang Technological University, Singapore 
- *2017.09 - 2021.06*, Bachelor of Engineering, Automation, Beihang University, Beijing, China

# 💻 Internships
- *2024-Now*, Research Intern (Remote), [OpenDriveLab](https://opendrivelab.com/), China.
- *2021.06 - 2021.08* VC Intern, [MiraclePlus](https://www.miracleplus.com/), Beijing, China
- *2020.10 - 2021.06*, Algorithm Engineer (DATA-EDU), ByteDance, Beijing, China.
