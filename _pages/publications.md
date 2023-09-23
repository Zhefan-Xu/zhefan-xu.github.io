---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=b_PtNQoAAAAJ&hl=en)
* [Heuristic-based Incremental Probabilistic Roadmap for Efficient UAV Exploration in Dynamic Environments](https://arxiv.org/abs/2309.09121) \
   **Zhefan Xu\***, Christopher Suzuki\*, Xiaoyang Zhan, Kenji Shimada \
   *Submitted to IEEE International Conference on Robotics and Automation (**ICRA**)*, 2024.
* [Quadcopter Trajectory Time Minimization and Robust Collision Avoidance via Optimal Time Allocation](https://arxiv.org/abs/2309.08544) \
   **Zhefan Xu**, Kenji Shimada \
   *Submitted to IEEE International Conference on Robotics and Automation (**ICRA**)*, 2024.
* [Low computational-cost detection and tracking of dynamic obstacles for mobile robots with RGB-D cameras](https://arxiv.org/abs/2303.00132) \
   **Zhefan Xu\***, Xiaoyang Zhan\*, Yumeng Xiu, Christopher Suzuki, Kenji Shimada \
   *Submitted to IEEE Robotics and Automation Letters (**RA-L**)*, 2023.
* [A vision-based autonomous UAV inspection framework for unknown tunnel construction sites with dynamic obstacles](https://ieeexplore.ieee.org/document/10167713) \
   **Zhefan Xu**, Baihan Chen, Xiaoyang Zhan, Yumeng Xiu, Christopher Suzuki, Kenji Shimada \
   *IEEE Robotics and Automation Letters (**RA-L**)*, 2023.
* [A real-time dynamic obstacle tracking and mapping system for UAV navigation and collision avoidance with an RGB-D camera](https://ieeexplore.ieee.org/abstract/document/10161194) \
   **Zhefan Xu\***, Xiaoyang Zhan\*, Baihan Chen, Yumeng Xiu, Chenhao Yang, Kenji Shimada \
   *IEEE International Conference on Robotics and Automation (**ICRA**)*, 2023.
* [Vision-aided UAV navigation and dynamic obstacle avoidance using gradient-based B-spline trajectory optimization](https://ieeexplore.ieee.org/abstract/document/10160638) \
   **Zhefan Xu**, Yumeng Xiu, Xiaoyang Zhan, Baihan Chen, Kenji Shimada \
   *IEEE International Conference on Robotics and Automation (**ICRA**)*, 2023.
* [DPMPC-Planner: A real-time UAV trajectory planning framework for complex static environments with dynamic obstacles](https://ieeexplore.ieee.org/abstract/document/9811886) \
   **Zhefan Xu**, Di Deng, Yiping Dong, Kenji Shimada\\
   *IEEE International Conference on Robotics and Automation (**ICRA**)*, 2022.
* [Autonomous UAV exploration of dynamic environments via incremental sampling and probabilistic roadmap](https://ieeexplore.ieee.org/abstract/document/9362184) \
   **Zhefan Xu**, Di Deng, Kenji Shimada \
   *IEEE Robotics and Automation Letters (**RA-L**)*, 2021.
* [Frontier-based automatic-differentiable information gain measure for robotic exploration of unknown 3D environments](https://arxiv.org/abs/2011.05288) \
   Di Deng, **Zhefan Xu**, Wenbo Zhao, Kenji Shimada \
   *Preprint arXiv:2011.05288*, 2020.
* [Coordinated aerial-ground robot exploration via monte-carlo view quality rendering](https://arxiv.org/abs/2011.05275) \
   Di Deng, **Zhefan Xu**, Wenbo Zhao, Kenji Shimada \
   *Preprint arXiv:2011.05275*, 2020.