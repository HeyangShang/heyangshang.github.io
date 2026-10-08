---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

The (α-β) means that the authors are sorted in alphabetical order.

{% bibliography %}

<h2 id="manuscripts" style="font-size: 1.75rem; margin-top: 3rem;">Manuscripts</h2>

{% bibliography --file manuscripts --group_by none %}

</div>
