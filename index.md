---
layout: page
title: About Me
cover: true
---

I am a PhD candidate at AID-LAB, [the University of Sydney](https://www.sydney.edu.au/), under the supervision of Dr. [Anusha Withana](https://scholar.google.com/citations?user=y17ckyIAAAAJ&hl=en&oi=ao) and Prof. [Judy Kay](https://scholar.google.com/citations?user=4lr4HzgAAAAJ&hl=en&oi=ao). My academic background includes a Master's degree from the University of Sydney and a Bachelor's degree from Monash University. In the field of Human-Computer Interaction, my research is centered on Soft Sensors, Epidermal Sensors, and Smart Textiles. I am dedicated to creating interfaces that seamlessly meld with the human body, enhancing user-technology interactions in everyday life.

## Recent News
* I will join Keio University as a Visiting Researcher from March to May 2024. (Tokyo)
* I submitted my Ph.D. thesis in January 2024. (Sydney)

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

