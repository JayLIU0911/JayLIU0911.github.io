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

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

High-Resolution Pose Transfer via Progressive Training and Pose Disentangling
======
**Ji Liu**\*, Heshan Liu\*, Yu-Wing Tai, Chi-Keung Tang. High-Resolution Pose Transfer via Progressive Training and Pose Disentangling. Submitted to *CVPR'19*. (\*Equal contributions)
* Project demo: *To be uploaded soon*
* Novelty:
  * To disentangle structure and appearance inherent in a given reference image, we propose a new encoder-decoder architecture that successfully enables seamless human pose transfer
  * We propose novel local descriptors to enhance the generation quality and local details
  * We apply progressive training to our autoencoder architecture to achieve outputs of unprecedented high resolution (1024 x 1024)
