---
layout: page
title:  Research
cover:  false
menu:   true
order:  1
---

> To explain all nature is too difficult a task for any one man or even for any one age. 
> It's much better to do a little with certainty, and leave the rest for others that come after you, 
> than to explain all things by conjecture without making sure of anything.
>
> --- Sir Isaac Newton

<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>
