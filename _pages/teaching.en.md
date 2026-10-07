---
layout: archive
title: "Teaching"
permalink: /en/teaching/
author: "Zhiang Xie"
author_profile: true
locale: en
---

# Undergraduate Course

## Quantitative Analysis of Marine Geography

Elective course for undergraduate students majoring in Marine Science.

Quantitative Analysis of Marine Geography is a signature elective in marine geology, using quantitative geography as its core toolkit to systematically teach quantitative analysis, spatial modeling, and statistical methods for marine geographic phenomena and processes. Following a method-to-application structure, it covers the foundations of quantitative geography, spatial statistics and inference, identification and classification of marine variables, and an introduction to artificial intelligence methods, and concludes with integrated case studies and hands-on practice on typical marine geology and environmental problems, developing students' scientific thinking and technical skills in solving marine geology and geography problems with quantitative methods.

# Graduate Topics

- Coupling an ice-sheet model with CAS‑ESM
- Quaternary ice-sheet evolution and sea-level change with <a href="{{ '/en/GREB-ISM/' | relative_url }}">GREB-ISM</a>
- Applications of the Wasserstein distance in climate science
- Other topics about climate sciences

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}