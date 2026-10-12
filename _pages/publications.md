---
layout: page
permalink: /publications/
title: Publications
# description: Also on <a href="https://scholar.google.com/citations?user=ofeDbZQAAAAJ">My Google Scholar</a>.
nav: true
nav_order: 2
---

<style>
  .publications h2.bibliography {
    color: var(--global-text-color-light);
  }
</style>

<style>
  .publications .author > em {
    border-bottom: none !important;
    font-weight: 700;
  }
</style>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
