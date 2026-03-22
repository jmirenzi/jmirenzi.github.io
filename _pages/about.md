---
permalink: /
title: "Jack Mirenzi"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year Masters in Robotics student at Carnegie Mellon University, with a BS in Mechanical Engineering from University of Maryland. My primary interest is Human Robot Interactions (HRI) and more specifically how a robot learner can improve even with a non-expert human teacher.

Currently, I am a member of the [HARP Lab](https://harplab.github.io/harplab.deploy/) and advised my Dr. Henny Admoni.

<!-- ### Selected Experience

![Me at CATT Lab](/images/catt-lab.jpg)
*Lieutenant Governor of Maryland, Aruna Miller, visiting the CATT Lab*

I worked at the [CATT Lab](https://www.cattlab.umd.edu/) for two years developing a self-supervised anomaly detector for the Clearpath Husky UGV. -->

<!-- I was a Design Engineer for [Airgility](https://www.airgility.co) three years  -->


## Recent Publications

{% assign pubs = site.publications | reverse %}
{% for post in pubs limit:3 %}
  <div style="margin-bottom: 1em;">
    <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br/>
    {{ post.venue }}, {{ post.date | date: "%Y" }}
    {% if post.paperurl %} · <a href="{{ post.paperurl }}">PDF</a>{% endif %}
  </div>
{% endfor %}

[See all publications →](/publications/)

---

## Recent Projects

{% assign portfolio = site.portfolio | reverse %}
{% for post in portfolio limit:3 %}
  <div style="display:flex; align-items:center; gap:1em; margin-bottom:1em;">
    {% if post.header.teaser %}
      <img src="{{ post.header.teaser }}" alt="{{ post.title }}"
           style="width:80px; height:80px; object-fit:cover; border-radius:4px; flex-shrink:0;">
    {% endif %}
    <div>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br/>
      {{ post.excerpt | strip_html | truncatewords: 20 }}
    </div>
  </div>
{% endfor %}

[See all projects →](/portfolio/)