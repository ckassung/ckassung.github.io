---
layout: post
title: Workflow für BA-Arbeiten
date: 2022-10-29 17:39:00
description: Idealisierter Workflow für das Erstellen einer Abschlußarbeit, der meinem BA-Kolloquium zugrunde gelegt wird.
tags: culture                                                                   
categories: teaching
---

Das nachfolgende Diagramm stellt einen idealtypischen Workflow dar. Es geht
also weniger um die konkrete Abfolge als die jeweiligen Arbeits- und
Schreibprozesse.

{% nomnoml %}
#fill: #ababab; #d4d4d4
[Forschungsperspektive]-->[Themenfindung|
  [Gegenstand]->[Methode]
  [Methode]->[Theorie]
  [Theorie]->[Gegenstand]
]
[Themenfindung]-->[Forschungsfragen|
  - thesenhaft
  - beantwortbar]
[Forschungsfragen]-->[Gliederung]
[Gliederung]-->[<table> Feingliederung|
  Quelle | Gegenstand ||
  Argument | Beobachtung 1. Ordnung ||
  These | Beobachtung 2. Ordnung
]
{% endnomnoml %}
