---
<!-- layout: archive -->
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

**Ji Liu**\*, Heshan Liu\*, Mang-Tik Chiu, Yu-Wing Tai, Chi-Keung Tang. High-Resolution Appearance Transfer Network (APT) (\*Equal contributions)
* Project demo [here](https://jayliu0911.github.io/supp_material/index.html)
* Our contribution consists of a new encoder-decoder architecture that successfully enables appearance transfer to a target pose. 
  * We propose novel local descriptors (progressive local perceptual loss + local discriminators at the highest resolution to enhance local details and generation quality.
  * We apply progressive training to our autoencoder architecture to achieve outputs at unprecedented high resolution (1024 x 1024).
* Results: We can transfer in high resolution on Human3.6M, DeepFashion and a self-collected YouTube dataset.
