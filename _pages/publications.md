---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
PCL: Peer-Contrastive Learning with Diverse Augmentations for Unsupervised Sentence Embeddings
Qiyu Wu, Chongyang Tao, Tao Shen, Can Xu, Xiubo Geng, Daxin Jiang. EMNLP 2022.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
