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

[**Paper**](https://arxiv.org/abs/2305.03303) \| [**Project**](https://github.com/georgeliu233/OPGP) \| [![](https://img.shields.io/github/stars/georgeliu233/OPGP?style=social&label=Code Stars)](https://github.com/georgeliu233/OPGP) 

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

## Journal
- [Differentiable Integrated Motion Prediction and Planning with Learnable Cost Function for Autonomous Driving](https://arxiv.org/abs/2207.10422), Zhiyu Huang, **Haochen Liu**, Jingda Wu, Chen Lv, **IEEE Transactions on Neural Networks and Learning Systems (T-NNLS), 2023** [![](https://img.shields.io/github/stars/MCZhi/DIPP?style=social&label=Code Stars)](https://github.com/MCZhi/DIPP)

- [Map-Adaptive Multimodal Trajectory Prediction Using Hierarchical Graph Neural Networks](https://dspace.lib.cranfield.ac.uk/bitstream/handle/1826/19830/Map-adaptive_multimodal_trajectory_prediction-2023.pdf?sequence=1), Xiaoyu Mo, Yang Xing, **Haochen Liu**, Chen Lv, **IEEE Robotics and Automation Letters (RA-L), 2023**
  
- [Conditional Predictive Behavior Planning with Inverse Reinforcement Learning for Human-like Autonomous Driving](https://arxiv.org/abs/2212.08787), Zhiyu Huang, **Haochen Liu**, Jingda Wu, Chen Lv, **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2023**


## Conference
- [Learning Interaction-aware Motion Prediction Model for Decision-making in Autonomous Driving](https://arxiv.org/abs/2302.03939), Zhiyu Huang, **Haochen Liu**, Jingda Wu, Wenhui Huang, Chen Lv, **IEEE International Conference on Intelligent Transportation Systems (ITSC), 2023** ([**Best Paper/Best Student Paper award nominee**](https://2023.ieee-itsc.org/best-paper-awards/)) [![](https://img.shields.io/github/stars/MCZhi/Predictive-Decision?style=social&label=Code Stars)](https://github.com/MCZhi/Predictive-Decision)

- [Improved Deep Reinforcement Learning with Expert Demonstrations for Urban Autonomous Driving](https://arxiv.org/abs/2102.09243), **Haochen Liu**, Zhiyu Huang, Jingda Wu, Chen Lv, **IEEE Intelligent Vehicles Symposium (IV), 2022** 

## Preprints
- [Augmenting Reinforcement Learning with Transformer-based Scene Representation Learning for Decision-making of Autonomous Driving](https://arxiv.org/abs/2208.12263), **Haochen Liu**, Zhiyu Huang, Xiaoyu Mo, Chen Lv, **arXiv, 2022**

# 🎖 Honors and Awards
- *2023.06* [Innovation Award, nuPlan Planning Challenge](https://opendrivelab.com/AD23Challenge.html#nuplan_planning), CVPR Workshop on End-to-End Autonomous Driving 
- *2023.06* [3rd Place Winner, Waymo Open Dataset Motion Prediction Challenge](http://cvpr2023.wad.vision/), CVPR Workshop on Autonomous Driving
- *2022.12* [3rd Place Winner, Most Innovative Award, Driving SMARTS Competition](https://smarts-project.github.io/archive/2022_nips_driving_smarts/competition/), NeurIPS Competition Track \| [\[slides\]](https://smarts-project.github.io/assets/docs/aid_driving_smarts.pdf)
- *2022.06* [2nd Place Winner, Waymo Open Dataset Occupancy and Flow Prediction Challenge](http://cvpr2022.wad.vision/), CVPR Workshop on Autonomous Driving

# 📖 Educations
- *2021.08 - Now*, Doctor of Philosophy, Nanyang Technological University, Singapore 
- *2017.09 - 2021.06*, Bachelor of Engineering, Automation, Beihang University, Beijing, China

# 💻 Internships
- *2020.10 - 2021.06*, Algorithm Engineer (DATA-EDU), ByteDance, Beijing, China.
