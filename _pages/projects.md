---
layout: page
title: publications
permalink: /publications/
description: publications by categories in reversed chronological order.
nav: true
nav_order: 3
---

<!-- pages/projects.md -->

<p>For a full and up-to-date list, see my <a href="https://scholar.google.com/citations?user=2e-5M5MAAAAJ" target="_blank" rel="noopener noreferrer"><i class="ai ai-google-scholar"></i> Google Scholar</a> profile.</p>

<div class="publications">
 {% bibliography --template bib --group_by type,year --group_order ascending,descending %}
</div>