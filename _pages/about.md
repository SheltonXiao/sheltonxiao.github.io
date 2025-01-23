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

I am a Ph.D. candidate in the School of Mechanical Engineering at Tongji University, specializing in Heating, Ventilation and Air Conditioning (HVAC). I am currently a visiting Ph.D. student at the Center for the Built Environment (CBE), UCBerkeley.

My research focuses on energy forecasting, optimal operation and control for HVAC systems in commercial buildings using data science technologies, particularly causal science and causal machine learning to enhance the physical principles underlying these models in the context of building energy data. I am also interested in automating energy management and optimization tasks with large language models, primarily focusing on automating energy efficiency diagnosis using multi-source building data. My experience includes building energy simulation, flexible demand-side control of energy systems considering occupant behavior, and informative and automatic design of air-conditioning systems.

My PhD thesis focuses on enhancing the predictive accuracy of data-driven energy prediction models across various buildings and usage scenarios, thereby increasing the value of using real-world data in building energy modeling. Existing data-driven approaches often struggle with generalizability, particularly when making out-of-distribution predictions, such as intervention predictions and counterfactual inference. These types of predictions are essential for tasks like building benchmarking, optimal control, demand response, and retrofit decisions. This research addresses this challenge by exploring methods to improve generalizability, focusing on energy models built from measured data and considering three key aspects: variables, models, and the data itself.

I have published several peer-reviewed papers with total <a href='https://scholar.google.com/citations?user=UHHn4yEAAAAJ'>google scholar citations <strong><span id='total_cit'>350+</span></strong></a> <a href='https://scholar.google.com/citations?user=UHHn4yEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 📖 Educations
- *2024.12 - Now*, Visiting Ph.D. student at the [Center for the Built Environment (CBE), UCBerkeley](https://cbe.berkeley.edu/), supervised by Prof. [Stefano Schiavon](https://cbe.berkeley.edu/about-us/people/stefano-schiavon/).
- *2019.09 - Now*, D.Phil. in the School of Mechanical Engineering at Tongji University, supervised by Prof. [Peng Xu](https://a434.tongji.edu.cn/english/GROUP/Team_leader.htm). GPA 4.93/5.0.
- *2015.09 - 2019.06*, B.E. in the School of Mechanical Engineering at Tongji University, majored in Built Environment and Energy Application Engineering. GPA 4.61/5.0.

# 💻 Internship
- *2023.07 - 2023.08*, **Applied Energy Trainee Program**. Research Intern in DC Building Lab (直流建筑实验室) - [Shenzhen Institute of Building Research Co., Ltd.](https://szibr.com/en/), supervised by Dr. Yemao Li, Zhihui Deng, and Dr. Bin Hao. Focus on Demand-side Energy Flexibility Management Optimization Considering Occupant Behavior.

# 📝 Publications 

## Journals:

- **T. Xiao**, P. Xu, 'Exploring automated energy optimization with unstructured building data: A multi-agent based framework leveraging large language models', *Energy and Buildings*, 2024. (**Q1,IF=6.6**)[[Link](https://doi.org/10.1016/j.enbuild.2024.114691)]
- R. He, **T. Xiao**, S. Qiu, J. Gu, M. Wei, P. Xu, 'A rule-based data preprocessing framework for chiller rooms inspired by the analysis of engineering big data', *Energy and Buildings*, 2022. (**Q1,IF=6.7**)[[Link](https://doi.org/10.1016/j.enbuild.2022.112372)]
- H. Guan, **T. Xiao**, W. Luo, J. Gu, R. He, P. Xu, 'Automatic fault diagnosis algorithm for hot water pipes based on infrared thermal images'. *Building and Environment*, 2022. (**Q1,IF=7.4**) [[Link](https://doi.org/10.1016/j.buildenv.2022.109111)]
- H. Wang, P. Xu, H. Sha, J. Gu, **T. Xiao**, Y. Yang, D. Zhang, 'BIM-based automated design for HVAC system of office buildings—An experimental study', *Building Simulation*, 2022. (**Q1,IF=5.5**) [[Link](https://doi.org/10.1007/s12273-021-0883-7)]
- **T. Xiao**, P. Xu, R. Ding, Z. Chen, 'An interpretable method for identifying mislabeled commercial building based on temporal feature extraction and ensemble classifier', *Sustainable Cities and Society*, 2022. (**Q1,IF=11.7**) [[Link](https://doi.org/10.1016/j.scs.2021.103635)]
- **T. Xiao**, P. Xu, R. He, H. Sha, 'Status quo and opportunities for building energy prediction in limited data Context—Overview from a competition', *Applied Energy*, 2022. (**Q1,IF=11.2**) [[Link](https://doi.org/10.1016/j.apenergy.2021.117829)]
- Z. Chen, Y. Chen, **T. Xiao**, H. Wang, P. Hou, 'A novel short-term load forecasting framework based on time-series clustering and early classification algorithm', *Energy and Buildings*, 2021. (**Q1,IF=6.7**) [[Link](https://doi.org/10.1016/j.enbuild.2021.111375)]
- M. Guo, P. Xu, **T. Xiao**, R. He, M. Dai, S.L. Miller, 'Review and comparison of HVAC operation guidelines in different countries during the COVID-19 pandemic', *Building and Environment*, 2021. (**Q1,IF=7.4**) [[Link](https://doi.org/10.1016/j.buildenv.2020.107368)]

## Conferences:

- J. Gu, W. Wang, **T. Xiao**, P. Xu, R. Jin, Z. Xiong, 'Automatic Design for Subway Station HVAC System Control Flow Chart Based on BIM or 2D Drawings', *Asia Conference of International Building Performance Simulation Association 2024* (**ASim 2024**), 2024.
- **T. Xiao**, P. Xu, 'Probing data selection risks in data-driven building energy mod-els: An investigation based on causal analysis', *The 18th Conference of the International Society of Indoor Air Quality & Climate* (**IndoorAir 2024**), 2024. (**Abstract**)(**Oral**)
- **T. Xiao**, P. Xu, S. Qiu, 'How does different collected data influence data-driven chiller model – Analysis of collected data distribution using causal discovery method', *The 18th IBPSA International Conference and Exhibition Building Simulation* (**BS2023**), 2023. (**Oral**)
- **T. Xiao**, P. Xu, H. Sha, 'An indoor temperature shift prediction model during demand response period based on operational data transfer learning (基于运行数据迁移学习的需求响应时段室内温度漂移预测模型)', *The 21st China HVAC Simulation Conference*, 2023. (**Oral**, in Chinese)

## Workshops, Posters and Others:

- P. Xu, **T. Xiao**, H. Sha, 'Deep Fake Synthetic Building —— The potential use of fake data synthesis technology in building area', *The 12th International Symposium on Heating, Ventilation and Air Conditioning* (**ISHVAC 2021**), 2021. (**Abstract**)

## Patents:
- P. Xu, **T. Xiao**, Z. Chen, Z. Chen, M. Guo, H. Sha. An automatic diagram forming method for air-conditioning water system schematic based on topological hierarchical abstraction. CN (Patent) 111797485B. filed June 5, 2020, and issued Apr. 7, 2023.
- P. Xu, **T. Xiao**, J. Gu, H. Li, Z. Chen, M. Dai. An automatic obstacle-based graph line exploration algorithm. CN (Patent) 112241575B. filed Sept. 28, 2020, and issued Nov. 11, 2022.
- P. Xu, R. He, Z. Chen, Y. Chen, **T. Xiao**, Z. Chen. A path optimization algorithm for water systems in air conditioning systems. CN (Patent) 112241564B. filed Jan. 19, 2021, and issued Sept. 13, 2022.

# 🎖 Honors and Awards
- *2022*, Outstanding Doctoral Scholarship, Tongji University.
- *2022*, Outstanding Student, Tongji University.
- *2022*, [Datawhale](https://github.com/datawhalechina) Contributor.
- *2019*, ***Outstanding Graduate, Shanghai***.
- *2017*, Second Prize of National Mathematical Contest in Modeling, China Society of Industrial and Applied Mathematics. First Prize of Shanghai Mathematical Contest in Modeling, Shanghai Municipal Education Commission.
- *2016*, Oustanding Student, Tongji University.
- *2016*, First Prize of Tongji Scholarship of Excellence, Tongji University.
- *2016*, First Prize of 6th “Shangtubei (上图杯)” Advanced Mapping Technology Competition, Shanghai Municipal Education Commission.

# 💬 Presentations and Talks

## Invited Talk:
- *2024*, Exploring automated energy optimization with unstructured building data: A multi-agent based framework leveraging large language models, Digital Futures 2024. @Shanghai,China

## Seminar:
- *2024*, Causal analysis of distribution shift in building energy models, WeLL Seminar Spring Student Spotlight Talk. @Berkeley,CA,USA. [[Picture](https://sheltonxiao.github.io/images/files/WeLL2024.jpg)]

## Conference Presentations:
- *2024*, Probing data selection risks in data-driven building energy mod-els: An investigation based on causal analysis, The 18th Conference of the International Society of Indoor Air Quality & Climate. @Honolulu,HI,USA.
- *2023*, How does different collected data influence data-driven chiller model – Analysis of collected data distribution using causal discovery method, The 18th IBPSA International Conference and Exhibition Building Simulation. @Shanghai,China. [[Picture](https://sheltonxiao.github.io/images/files/BS2023.jpg)]
- *2023*, An indoor temperature shift prediction model during demand response period based on operational data transfer learning, The 21st China HVAC Simulation Conference. @Taiyuan,Shanxi,China. [[Picture](https://sheltonxiao.github.io/images/files/CHVACS2023.jpg)]
- *2021*, Building energy consumption prediction in a limited data context, The 20th China HVAC Simulation Conference. @Xi'an,Shaanxi,China. [[Picture](https://sheltonxiao.github.io/images/files/CHVACS2021.jpg)]
