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

* [Heuristic-based Incremental Probabilistic Roadmap for Efficient UAV Exploration in Dynamic Environments](https://arxiv.org/abs/2309.09121) \
   **Zhefan Xu\***, Christopher Suzuki\*, Xiaoyang Zhan, Kenji Shimada \
   *Submitted to IEEE International Conference on Robotics and Automation (**ICRA**)*, 2024.
* [Quadcopter Trajectory Time Minimization and Robust Collision Avoidance via Optimal Time Allocation](https://arxiv.org/abs/2309.08544) \
   **Zhefan Xu**, Kenji Shimada \
   *Submitted to IEEE International Conference on Robotics and Automation (**ICRA**)*, 2024.
* [Onboard dynamic-object detection and tracking for autonomous robot navigation with RGB-D camera](https://arxiv.org/abs/2303.00132) \
   **Zhefan Xu\***, Xiaoyang Zhan\**, Yumeng Xiu, Christopher Suzuki, Kenji Shimada \
   *Submitted to IEEE IEEE Robotics and Automation Letters (**RAL**)*, 2023.