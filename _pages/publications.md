---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

{% include base_path %}

## <u>Measurement of triple boson production in proton collisions with the ATLAS detector at the Large Hadron Collider</u>
(Forthcoming)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
