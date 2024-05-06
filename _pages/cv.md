---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Economics, Department of Economics, University of California, Riverside, 2019-Present
* M.A. in Applied Statistics, Wang Yanan Institute for Studies in Economics, Xiamen University, 2019
* B.A. in Mathematic Finance, Wang Yanan Institute for Studies in Economics, Xiamen University, 2015
* B.S. in Chemistry, College of Chemistry and Chemical Engineerings, Xiamen University, 2015

Work experiences
======
* Summer 2023: Applied Scientist Intern, Snap Inc.
  * Conduct a causal inference research on double machine learning technique in the context of continuous - uous tretament effect. In this study, we evaluate two methods, entropy balancing for continuous treatment and double/debiased machine learning for continuous treatment, utilizing both synthetic and semi-synthetic data derived from Snapchat user data. These methods address continuous treat- ment scenarios involving dose-response curve and marginal effect estimation. Our results highlight the superiority of machine learning, especially tree-based methods like XgBoost and BooST, over the bal- ancing approach and DNN. Remarkably, BooST surpasses XgBoost in performance, raising questions about overcoming scalability limitations.
  * Submitted and presented at CODE@MIT 2023.

* Fall 2017 - Summer 2019: Master Thesis, Xiamen University
  * Title:Network of Shareholders and Stock Price Synchronicity:Empirical Evidence from A-share Market
  * Main work: Build up a social network model of top ten shareholders to construct three network topol- ogy variables to measure centrality, validity and length of shareholder networks. By using spatial panel data models and network model, this paper firmly demonstrates the networks of shareholders in A-share could significantly increase the stock price synchronicity.

* Fall 2016 - Summer 2017: Research Assistant, Xiamen University
  * Project: Estimating and Testing Threshold Models with Time-Varying Thresholds: Theory and Appli- cation funded by National Science Foundation of China(71571152)
  * Main work: Develop the research idea of network model to simulate the dynamic changes of share- holder networks and to estimate its effects on crash risk of stock market, build up database of the whole 2 project which is partly obtained with crawlers of Rcurl-Package and Rvest-Package from Website and participate in empirical analysis and part of paper writing.

Skills
======
* R
* Pythn
* SQL
* Eviews
* Stata
* Google Cloud Platform

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
