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

</style>

<!-- TODO: entries come from _bibliography/references.bib (BibTeX), grouped by year.
     Add a `# YYYY` heading + bibliography query for each year you want to publish. -->

# 2026
{% bibliography --query @*[year=2026] %}
