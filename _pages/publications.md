---
layout: page
permalink: /publications/
title: publikationen
description: Ausgewählte Forschungsbeiträge der letzten fünf Jahre.
years: [2022, 2021, 2020, 2019, 2018]
nav: false
---

<!-- _pages/publications.md -->
Eine vollständige Publikationsliste ist als <a href="{{ site.baseurl }}/assets/pdf/publication_list.pdf" target="_blank">PDF</a> verfügbar.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2> {% bibliography -f publications -q @book[year={{y}}]* && @proceedings[year={{y}}]* && @periodical[year={{y}}]* && @incollection[year={{y}}]* && @article[year={{y}}]* %} {% endfor %}

</div>
