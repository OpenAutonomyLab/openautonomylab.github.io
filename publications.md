---
layout: page
title: Publications
show_sidebar: false
hide_footer: false
---

<style>
.csl-block {
    font-size: 16px;
}
.csl-title, .csl-author, .csl-event, .csl-editor, .csl-venue {
    display: block;
    position: relative;
    font-size: 16px;
}

.csl-title b {
    font-weight: 600;
}

.csl-content {
    display: inline-block;
    vertical-align: top;
    padding-left: 20px;
}

.bibliography {
  list-style-type: none;
}

.bibliography > li::marker {
  content: "[" counter(list-item) "]";
  counter-increment: list;
}

.pub-award-badge {
  display: block;
  width: fit-content;
  margin: 6px 0 8px;
  padding: 3px 10px;
  font-size: 13px;
  font-weight: 600;
  color: #7a5b00;
  background: #fff4d6;
  border: 1px solid #f0d585;
  border-radius: 999px;
}

</style>

# Under Review
{% bibliography --query @misc %}

# 2025
{% bibliography --query @*[year=2025] %}

# 2024
{% bibliography --query @*[year=2024] %}

# 2023
{% bibliography --query @*[year=2023] %}

# 2021
{% bibliography --query @*[year=2021] %}
