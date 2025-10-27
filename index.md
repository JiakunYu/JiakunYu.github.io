---
layout: page
title: About Me
cover: true
---

I am currently a Postdoctoral Researcher at Purdue University's Institute for Physical Artificial Intelligence ([IPAI](https://www.purdue.edu/computes/institute-for-physical-artificial-intelligence/)), working with [Prof. Karthik Ramani](https://engineering.purdue.edu/cdesign/wp/current-convergence-design-lab-members/) at the Convergence Design Lab and [Dr. Sooyeon Jeong](https://www.sooyeonjeong.com/) at the HAI Lab.

I completed my PhD in 2024 at the University of Sydney, where my research focused on the [“Computational Design and Fabrication of Customizable Interactive Soft Devices”](https://ses.library.usyd.edu.au/handle/2123/32814), supervised by [A/Prof. Anusha Withana](https://scholar.google.com/citations?user=y17ckyIAAAAJ&hl=en&oi=ao) and [Prof. Judy Kay](https://scholar.google.com/citations?user=4lr4HzgAAAAJ&hl=en&oi=ao). I also hold a Master of Data Science from the University of Sydney and a Bachelor's in Electrical and Computer Systems Engineering from Monash University.

My current research interests lie at the intersection of soft sensors, epidermal sensing technologies, and smart textiles. My goal is to create interfaces that seamlessly integrate with the human body and improve user-centric interactions.

## Recent News
* [12/2024]\: Excited to share that I have accepted a Postdoctoral position at Purdue University. Starting Spring of 2025, I will be working with Prof. Karthik Ramani, Dr. Sooyeon Jeong, and Dr. Liang He!
* [10/2024]\: I presented [IrOnTex](https://programs.sigchi.org/ubicomp-iswc/2024/program/content/174664) at UbiComp 2024!
* [09/2024]\: I was officially awarded a PhD by the University of Sydney!
* [07/2024]\: Our IrOnTex submission to UbiComp/IMWUT was accepted!
* [03/2024]\: I joined Keio University as a Visiting Researcher in Tokyo!
* [01/2024]\: I submitted my Ph.D. thesis to the University of Sydney!
* [01/2024]\: Our Infill Sensor submission to the IEEE Sensor Journal was accepted!

## Recent Research Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

