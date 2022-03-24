---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/sky3.jpg
#  actions:
#    - label:
#      url:
excerpt: >
#   <br />
#  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.24.0">Latest release v4.24.0</a></small>

feature_row_left:
  - image_path: /assets/images/UMNproud.jpeg
    title: "Welcome!"
    excerpt: "Thank you for visiting my page!! <br /><br /> My name is **Minoh Jeong.** I am currently a PhD student/research assistant in the group of Prof. [Martina Cardone](https://mcardone.umn.edu) at University of Minnesota. Before joining Martina's group, I received my MS degree and was a member in the group of Prof. [Songnam Hong](https://sites.google.com/view/snlab) at Ajou University, South Korea.<br /><br />
    I am widely interested in the fields of ***statistical estimation theory, differential privacy, coding theory, information theory, machine learning*** and ***algorithm***. In particular, I am currently focusing on data permutation (data ranking) estimation problem motivated by privacy concern, and differential privacy.<br /><br />
    On this current research topic, I am particularly interested in:<br />
	&nbsp;&nbsp; * figuring out the optimal noise-adding mechanism satisfying differential privacy constraints in various systems (particularly, in this ranking estimation problem); <br />
  &nbsp;&nbsp; * designing a low complexity decoding algorithm that has a good performance; <br />
  &nbsp;&nbsp; * characterizing the performance and complexity of various decoders. <br />
"
    url: "/AboutMe"
    btn_label: "Read more"
    btn_class: "btn--info"

feature_row:
  - image_path: /assets/images/PlotH_3D.png
    alt: "Research"
    title: "Research"
#    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/Research/"
    btn_class: "btn--info"
    btn_label: "Read more"
  - image_path: /assets/images/tamara-gak-GWbIHT51VT4-unsplash.jpg
    alt: "Publications"
    title: "Publications"
#    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/Publications/"
    btn_class: "btn--info"
    btn_label: "Read more"      
  - image_path: /assets/images/cv_teaser.jpg
    alt: "CV"
    title: "CV"
#    excerpt: "I am PhD student at University of Minnesota"
    url: "/assets/files/CV_Minoh.pdf"
    btn_class: "btn--info"
    btn_label: "Read more"
---

{% include feature_row id="feature_row_left" type="left" %}
{% include feature_row %}
