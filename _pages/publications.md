---
layout: page
permalink: /publications/
title: publications
nav_icon: fa-solid fa-book-open
description: Papers and patents in reverse chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Papers

<div class="publications">

{% bibliography --query @article,@inproceedings %}

</div>

## Patents

<div class="publications">

{% bibliography --query @misc %}

</div>
