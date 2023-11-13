---
layout: page
permalink: /repositories/
title: Repositories
description: 
nav: true
nav_order: 3
---

<!-- ## GitHub users -->

<!-- {% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div> -->



<!-- {% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
  {% if site.data.repositories.github_users.size > 1 %}
  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.html username=user %}
  </div>

  ---

{% endfor %}
{% endif %} -->
<!-- {% endif %} -->
---
## Data Repositories
Check out some fantastic imaging datasets used for my research and which I contributed to make publicly available!
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/repository/dataset/remind.gif" title="ReMIND dataset" href="https://doi.org/10.7937/3RAG-D070" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/repository/dataset/vsseg_multi.gif" title="VS-MC-RC dataset" href="https://doi.org/10.7937/TCIA.9YTJ-5Q73"  class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/repository/dataset/vsseg.gif" title="VS-Seg dataset" href="https://doi.org/10.7937/HRZH-2N82"  class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
</div>
---

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
