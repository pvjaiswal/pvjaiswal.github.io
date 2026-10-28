---
layout: page
permalink: /publications/
title: publications
description: Papers under review and preprints, followed by published and accepted work, newest first.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

## Under review and preprints

{% bibliography -f {{ site.scholar.bibliography }} -q @*[status=review]* %}

## Published and accepted

{% bibliography -f {{ site.scholar.bibliography }} -q @*[status=published]* %}

</div>
