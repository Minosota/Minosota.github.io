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
    excerpt: "Hi, I'm Minoh Jeong, a postdoctoral researcher at the University of Michigan. <br /> My work sits at the intersection of machine learning, statistical signal processing, and information theory. Currently, I explore principled ways to turn messy, multimodal data into useful representations. I'm motivated by questions of robustness, uncertainty, and evaluation, and I enjoy building bridges between theory and practice. 
"
    url: "/AboutMe"
    btn_label: "Read more"
    btn_class: "btn--info"

feature_row:
  - image_path: /assets/images/PlotH_3D.png
    alt: "Publications"
    title: "Publications"
#    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/Publications/"
    btn_class: "btn--info"
    btn_label: "Read more"
  - image_path: /assets/images/Presenstation.png
    alt: "Presentations"
    title: "Presentations"
#    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/Presentations/"
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
