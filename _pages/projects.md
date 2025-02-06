---
layout: page
title: publications
permalink: /publications/
description: publications by categories in reversed chronological order.
nav: true
nav_order: 3
---

<!-- pages/projects.md -->
<!-- Bibsearch Feature -->

<div class="publications">
 {% bibliography --template bib --group_by type,year --group_order ascending,descending %}
</div>