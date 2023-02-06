---
layout: page
permalink: /repositories/
title: Projects
description: 
nav: true
nav_order: 1
---

## GitHub Profile

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}

---

## Selected Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

---

## Working Progress

🧑‍💻 60exps: A photographic style dataset for computational photography applications.

🧑‍💻 A multiclass graph neural network-based framework for predicting post engagement in social media.

🧑‍💻 Development of a Deep Learning method for Dataset Distillation

🧑‍💻 Select and Enhance: Mask-Based Image Enhancement via Tree Search Theory

🧑‍💻 Implementation of a Conditional Variational AutoEncoder for Image Enhancement
