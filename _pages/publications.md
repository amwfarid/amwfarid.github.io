---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- A. Farid, T. Matsumaru, "Pre-Robotic Navigation Identification of Pedestrian Crossings & Their Orientations", 12th Conference on Field & Service Robotics, 2019.

- A. Farid, A. Elaraby, R. Saito, "A Mission Concept for Road-side Waste Detection & Action Planning Using Networked Mobile Robots", Workshop on The Advances and Challenges on the Development, Testing and Assessment of Internet of Robotic Things (IoRT): Experiences from Engineering and Human Science Research, 2019 IEEE International Conference of Robotics on Robotics and Automation, 2019.

- A. Farid, T. Matsumaru, "Path Planning in Outdoor Pedestrian Settings Using 2D Digital Maps", Journal of Robotics & Mechatronics, FujiTechnology Press, Accepted and scheduled for Vol.31 No.3, June 2019.

- A. Farid, T. Matsumaru, "Path Planning of Sidewalks & Street Crossings in Pedestrian Environments Using 2D Map Visual Inference", ROMANSY 22 Robot Design, Dynamics and Control, pp.247-255, 2018.

- A. Farid, A. Elaraby, A. Sherif, F. Fouda, F., "MENA Renewable Energy Source Mapping Via Nano-Satellite Mission", University Space Engineering Consortium (UNISEC) 3rd Mission Idea Contest, 2014.

- A. Farid, A. Samy, A. Shalaby, A. Tarek, M. Ayyad, M. Assem, S. Amin, "Utilizing Low-Cost Linux Micro-Computer & Android Phone Solutions on Cube-Satellites", 5th Nano-Satellite Symposium, 2013.

- A. Farid, A. Samy, A. Shalaby, A. Tarek, M. Ayyad, M. Assem, S. Amin, "2nd Iteration Cairo University Cube-Satellite", 5th Nano-Satellite Symposium, 2013.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}