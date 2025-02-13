---
layout: default
---

<div class="main-content-wrap">
  <div class="main-content">
    <div class="page-header">
      <h1>{{ page.title }}</h1>
      {% if page.description %}
      <p class="page-description">{{ page.description }}</p>
      {% endif %}
    </div>

    {{ content }}
  </div>
</div>