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

# Mobile Robot

<ol class="project-list">
{% assign mobile_robot_projects = site.data.projects | where: "category", "Mobile Robot" %}
{% for project in mobile_robot_projects %}
<li>
    <span class="project-title">{{ project.title }}</span>
    <span class="project-meta">{{ project.sponsor }}, {{ project.period }}</span>
</li>
{% endfor %}
</ol>

# Humanoids

<ol class="project-list">
{% assign humanoid_projects = site.data.projects | where: "category", "Humanoids" %}
{% for project in humanoid_projects %}
<li>
    <span class="project-title">{{ project.title }}</span>
    <span class="project-meta">{{ project.sponsor }}, {{ project.period }}</span>
</li>
{% endfor %}
</ol>
