---
layout: archive
title: "Publicações"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Acesse o meu currículo acadêmico aqui <a href="{{http://lattes.cnpq.br/5078353564305934}}"></a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
