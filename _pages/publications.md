---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
---
<div class="publications">
  <nav class="publication-index" aria-label="Publication sections">
    <a href="#papers-heading">Papers</a>
    <a href="#other-work-heading">Theses and other work</a>
  </nav>
  <section aria-labelledby="papers-heading">
    <h2 class="publication-section-title" id="papers-heading">Papers</h2>
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[website_section=papers] %}
  </section>
  <section aria-labelledby="other-work-heading">
    <h2 class="publication-section-title" id="other-work-heading">Theses and other work</h2>
    {% bibliography -f {{ site.scholar.bibliography }} --query @*[website_section=other] %}
  </section>
</div>
