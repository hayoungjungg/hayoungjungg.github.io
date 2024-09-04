---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---

<p>For most up-to-date list of my publications, please visit my <a href="https://scholar.google.com/citations?user=4-HhtdkAAAAJ&hl=en">Google Scholar profile.</a></p>

<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=preprint]* %}

</div>
