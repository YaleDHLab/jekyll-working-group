---
layout: default
---

{% for animal in site.data.animals %}
  <div>
    <span>{{ animal.animal_name_in_language }}</span>
    <span>is the name for</span>
    <span>{{ animal.animal_common_name }}</span>
    <span>in</span>
    <span>{{ animal.language }}</span>
  </div>
{% endfor %}