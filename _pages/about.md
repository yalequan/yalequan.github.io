---
permalink: /
excerpt: "Yale Quan develops methods for educational and psychological measurement, using statistical and machine learning tools."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home">

<h1 class="home-lead">I develop methods for educational and psychological measurement.</h1>
<p class="home-lead__second">My work uses statistical and machine learning tools to help tests and surveys measure fairly and accurately, even when data are limited.</p>

<hr class="home-rule">

<h2>Research areas</h2>

<div class="home-cards">
  <a class="home-card" href="{{ site.baseurl }}/research/">
    <h3>Integrating Machine Learning and Psychometrics</h3>
    <p>Bringing neural networks, graph-based methods, and other machine learning tools into psychometric modeling, from detecting item bias to estimating parameters and scoring.</p>
    <span class="home-card__more">Read more &rarr;</span>
  </a>
  <a class="home-card" href="{{ site.baseurl }}/research/">
    <h3>Diagnostic Classification Models</h3>
    <p>Methodological frameworks that make diagnostic models practical, from design and specification to model fit, so they give reliable, actionable feedback.</p>
    <span class="home-card__more">Read more &rarr;</span>
  </a>
  <a class="home-card" href="{{ site.baseurl }}/research/">
    <h3>Measurement in Complex Data</h3>
    <p>Methods for settings that challenge standard models: small samples, many groups, sparse responses, and missing data.</p>
    <span class="home-card__more">Read more &rarr;</span>
  </a>
</div>

<p class="home-applied">I also partner with K–12 schools and community organizations to study student belonging and chronic absenteeism.</p>

<h2>Featured publications</h2>

<ul class="home-pubs">
  <li>
    <div class="home-pubs__title">Transitive DIF clustering: A graph-theoretic approach to identifying many-group partial measurement invariance</div>
    <div class="home-pubs__meta"><b>Quan, Y.</b>, &amp; Wang, C. (2026). <em>Psychological Methods</em>.</div>
    <div class="home-pubs__links"><a class="home-tag" href="https://doi.org/10.1037/met0000873">DOI</a></div>
  </li>
  <li>
    <div class="home-pubs__title">Using multi-label classification neural networks to detect intersectional DIF with small sample sizes</div>
    <div class="home-pubs__meta"><b>Quan, Y.</b>, &amp; Wang, C. (2026). <em>British Journal of Mathematical and Statistical Psychology</em>.</div>
    <div class="home-pubs__links"><a class="home-tag" href="https://doi.org/10.1111/bmsp.70041">DOI</a></div>
  </li>
  <li>
    <div class="home-pubs__title">Review of cognitive diagnostic models (CDMs): Recent methodological advancements for addressing practical challenges</div>
    <div class="home-pubs__meta">Wang, C., <b>Quan, Y.</b>, &amp; Arthur, D. (2026). <em>British Journal of Mathematical and Statistical Psychology</em>.</div>
    <div class="home-pubs__links"><a class="home-tag" href="https://doi.org/10.1111/bmsp.70066">DOI</a></div>
  </li>
</ul>

<a class="home-all" href="{{ site.baseurl }}/publications_and_presentations/">All publications and presentations &rarr;</a>

<h2>News</h2>

<ul class="home-news">
{% for item in site.data.news limit: 5 %}
  <li><span class="home-news__date">{{ item.date }}</span><span class="home-news__text">{{ item.text | markdownify | remove: '<p>' | remove: '</p>' | strip }}</span></li>
{% endfor %}
</ul>

</div>
