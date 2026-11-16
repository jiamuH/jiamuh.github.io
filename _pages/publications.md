---
layout: page
permalink: /publications/
title: publications
description: Publications by Jiamu Huang, first-author papers first, then co-authored papers, newest first.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

My full publication record is also on [NASA ADS](https://ui.adsabs.harvard.edu/search/q=%3Dauthor%3A%22Huang%2C%20Jiamu%22%20collection%3Aastronomy&sort=date%20desc).

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">First-author papers</h2>

{% bibliography --query @*[selected=true]* --group_by none %}

<h2 class="bibliography">Co-authored papers</h2>

{% bibliography --query @*[selected!=true]* --group_by none %}

</div>
