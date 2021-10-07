---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

### 2021
* Semi-analytical Approach for Sky Localization of Gravitational Waves, CBC East Call, Sep.14 2021.
    * 15+5 minutes talk on the localization paper ([arXiv link](https://arxiv.org/abs/2110.01874)).
