---
layout: page
permalink: /publications/
title: publications
description: Publications listed by year.
nav: true
nav_order: 2
---

<style>
  .publications .abbr figure {
    display: none;
  }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
