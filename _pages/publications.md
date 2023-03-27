---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

PCL: Peer-Contrastive Learning with Diverse Augmentations for Unsupervised Sentence Embeddings
Qiyu Wu, Chongyang Tao, Tao Shen, Can Xu, Xiubo Geng, Daxin Jiang. EMNLP 2022.

[Knowledge Stimulated Contrastive Prompting for Low-Resource Stance Detection](https://aclanthology.org/2022.findings-emnlp.83/）

**Kai Zheng**, Qingfeng Sun, Yaming Yang, Fei Xu
**EMNLP-2022**

[Multimodal dialogue response generation](https://arxiv.org/abs/2110.08515)

Qingfeng Sun, Yujing Wang, Can Xu, **Kai Zheng**, Yaming Yang, Huang Hu, Fei Xu, Jessica Zhang, Xiubo Geng, Daxin Jiang. **ACL 2022.**

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
