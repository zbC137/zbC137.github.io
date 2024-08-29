---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
*Equal Contribution

Journal Papers
=======
[1] X. Shao, **B. Zhang<sup>*</sup>**, H. Zhi, J. G. Romero, B. Fan, Q. Hu, and D. Navarro-Alarcon, "InPTC: Integrated Planning and Tube-Following Control for Prescribed-Time Collision-Free Navigation of Wheeled Mobile Robots," in *IEEE/ASME Transactions on Mechatronics*, 2024(Under Review). doi:[arXiv:2312.11930](https://doi.org/10.48550/arXiv.2312.11930). ([PDF](http://zbC137.github.io/files/papers/TMECH_2024.pdf), [Video](https://vimeo.com/895801720))

[2] **B. Zhang**, X. Shao, H. Zhi, L. Qiu, J. G. Romero, and D. Navarro-Alarcon, "Leader-Follower Formation Control of Perturbed Nonholonomic Agents along Parametric Curves with Directed Communication," in *IEEE Robotics and Automation Letters*, Aug. 2024(Early Access). doi:[10.1109/LRA.2024.3445657](https://doi.org/10.1109/LRA.2024.3445657). ([PDF](http://zbC137.github.io/files/papers/RAL_2024.pdf), [Video](https://vimeo.com/872927697))
[3] 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
