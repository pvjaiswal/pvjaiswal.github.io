---
layout: page
permalink: /publications/
title: Publications
description: Papers under review and preprints, followed by published and accepted work, newest first.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2>Under review and preprints</h2>

{% bibliography -f {{ site.scholar.bibliography }} -q @*[status=review]* %}

<h2>Published and accepted</h2>

{% bibliography -f {{ site.scholar.bibliography }} -q @*[status=published]* %}

</div>
