---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h3>official publications</h3>
{% bibliography --query @*[keywords=official]* %}

<h3 class="student-publications">student publications</h3>
{% bibliography --query @*[keywords=student]* %}

</div>
