---
layout: page
title: Archiv
permalink: /archive/
---

Willkommen im Archiv!

Hier findest du alle Versionen des Spiels, die es jemals gegeben hat!

## Vollversionen
{% if site.data.versions.size > 0 %}
{% for version in site.data.versions %}
- [{{version.name}}]({{version.download}}) \| {{version.date | date: "%-d %B %Y"}}
{% endfor %}
{% else %}
- nichts vorhanden.
{% endif %}

## Testversionen
{% if site.data.testversions.size > 0 %}
{% for version in site.data.testversions %}
- [{{version.name}}]({{version.download}}) \| {{version.date | date: "%-d %B %Y"}}
{% endfor %}
{% else %}
- nichts vorhanden.
{% endif %}
