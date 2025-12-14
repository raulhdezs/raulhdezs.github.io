---
layout: page
permalink: /publications/
title: Publications
description: Scientific communications ordered from oldest to newest.
nav: true
nav_order: 3
---

<h2>Journal Articles</h2>
{% bibliography %}

<h2>Conference Contributions</h2>
{% bibliography --file conferences.bib %}

<h2>Seminars & Workshops</h2>
{% bibliography --file seminars.bib %}
