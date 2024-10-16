---
layout: page
title: About Me
cover: true
---

I completed my PhD (2024) on the topic [“Computational Design and Fabrication of Customizable Interactive Soft Devices”](https://ses.library.usyd.edu.au/handle/2123/32814) at [the University of Sydney](https://www.sydney.edu.au/) under the supervision of [Dr. Anusha Withana](https://scholar.google.com/citations?user=y17ckyIAAAAJ&hl=en&oi=ao) and [Prof. Judy Kay](https://scholar.google.com/citations?user=4lr4HzgAAAAJ&hl=en&oi=ao). My academic background includes a Master's degree from the University of Sydney and a Bachelor's degree from Monash University. In the field of Human-Computer Interaction, my research is centered on Soft Sensors, Epidermal Sensors, and Smart Textiles. I am dedicated to creating interfaces that seamlessly meld with the human body, enhancing user-technology interactions in everyday life.

## Recent News
* Oct 2024: Presented [IrOnTex](https://programs.sigchi.org/ubicomp-iswc/2024/program/content/174664) at UbiComp 2024!
* Jul 2024: I was officially awarded a PhD by the University of Sydney!
* Jul 2024: Our IrOnTex submission to UbiComp/IMWUT was accepted!
* Mar - May 2024: I joined Keio University as a Visiting Researcher in Tokyo!
* Jan 2024: I submitted my Ph.D. thesis to the University of Sydney!
* Jan 2024: Our Infill Sensor submission to IEEE Sensor Journal was accepted!

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

