---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed publications and manuscripts currently under review to which I have contributed.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

  <h2>Published / Accepted</h2>
  {% bibliography --query @*[status=published] %}

  <h2>Under Review</h2>
  {% bibliography --query @*[status=underreview] %}

  <h2>In Preparation</h2>
  {% bibliography --query @*[status=inprep] %}

</div>
