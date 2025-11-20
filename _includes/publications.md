{% for link in site.data.papers.papers %}

<div class="pub-card">

  <div class="pub-image-wrapper">
    {% if link.badge %}
      <div class="pub-badge">{{ link.badge }}</div>
    {% endif %}
    {% if link.image %}
      <img src="{{ link.image | relative_url }}" alt="teaser of {{ link.title }}">
    {% endif %}
  </div>

  <div class="pub-content">
    <papertitle>
      {% if link.doc-url %}
        <a href="{{ link.doc-url }}">{{ link.title }}</a>
      {% else %}
        {{ link.title }}
      {% endif %}
    </papertitle><br/>

    {{ link.authors }}<br/>

    {% if link.booktitle %}
      <em>{{ link.booktitle }}</em>, {{ link.year }}.
    {% elsif link.conference %}
      <em>{{ link.conference }}</em>, {{ link.year }}.
    {% endif %}<br/>

    {% if link.pdf %}<a class="biblink" href="{{ link.pdf }}">PDF</a>{% endif %}
    {% if link.supp %}<a class="biblink" href="{{ link.supp }}">Supp</a>{% endif %}
    {% if link.supp2 %}<a class="biblink" href="{{ link.supp2 }}">Supp2</a>{% endif %}
    {% if link.video %}<a class="biblink" href="{{ link.video }}">Video</a>{% endif %}
    {% if link.page %}<a class="biblink" href="{{ link.page }}">Page</a>{% endif %}
    {% if link.data %}<a class="biblink" href="{{ link.data }}">Dataset</a>{% endif %}
    {% if link.bibtex %}<a class="biblink" href="{{ link.bibtex }}">BibTeX</a>{% endif %}
  </div>

</div>

{% endfor %}
