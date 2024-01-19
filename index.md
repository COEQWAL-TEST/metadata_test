---
title: Home
layout: home
nav_order: 1
---

# Welcome to COEQWAL's docs!

This is a *first attempt* at creating a comprehensive documentation site for [COEQWAL](https://coeqwal.berkeley.edu/). The objective is for this to be a point of reference where collaborators and the wider public can find useful information aboout COEQWAL's:

- Modelling experiment runs
- Datasets and data dictionaries
- General assumptions and definitions

The wider aim is to support the transparency and reproducibility of the project. 

#### Thank you to the contributors of COEQWAL-TEST!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>
