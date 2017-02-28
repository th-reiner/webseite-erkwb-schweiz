---
layout: page
title: Gemeinden
subtitle: ERKWB in der Schweiz
---

{% for item in site.data.gemeinden %}

## [ERKWB {{ item.city }}](http://{{ item.url }})

![Lokal der ERKWB {{ item.city }}]({{ item.image }})

{{ item.house }}<br />
{{ item.adress }}<br />
{{ item.zip }} {{ item.city }}

Gottesdienst: {{ item.service }}

{% endfor %}

Gemeinden der [Evangelisch-reformierten Kirche in Österreich](http:www.reformiert.at).
