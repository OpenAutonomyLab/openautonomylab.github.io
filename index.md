---
title: Open Autonomy Lab
subtitle: We pursue fully autonomous robots
layout: page
show_sidebar: false
hide_footer: false
hero_height: is-large
hero_image: /img/hero-placeholder.svg
hero_link: /research/
hero_link_text: See Our Research

hero_link2: /team/
hero_link_text2: See Our Team
---

# About Us

<!-- TODO: replace with your lab's mission statement -->
Our mission is to advance the state of the art in autonomous robots and systems.

<!-- TODO: replace with your institution / affiliation, or remove this line -->
We are part of [Department of Electrical Engineering and Computer Science](https://www.dgist.ac.kr/en_eecs/index.do) at [DGIST](https://www.dgist.ac.kr/eng/index.do), South Korea.

# Highlights

<!-- TODO: highlighted posts are pulled from _posts with `categories: highlights`.
     Add posts with that category to feature them here, or remove this section. -->
{% assign posts = site.posts | where:"categories","highlights" %}
<div class="columns is-multiline">
    {% for post in posts %}
    <div class="column is-4-desktop is-6-tablet">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div>
