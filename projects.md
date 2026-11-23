---
layout: page
title: Projects
show_sidebar: false
hide_footer: false
---

<style>
.project-list {
  list-style-type: none;
}

.project-list > li::marker {
  content: "[" counter(list-item) "]";
  counter-increment: list;
}

.project-list > li {
  margin-bottom: 14px;
}

.project-title {
  display: block;
  font-size: 16px;
  font-weight: 600;
}

.project-meta {
  display: block;
  font-size: 16px;
}
</style>

<ol class="project-list">
{% for project in site.data.projects %}
<li>
    <span class="project-title">{{ project.title }}</span>
    <span class="project-meta">{{ project.sponsor }}, {{ project.period }}</span>
</li>
{% endfor %}
</ol>
