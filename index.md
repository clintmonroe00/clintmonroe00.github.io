---
layout: default
title: Technical Artifacts
---

<h1>Technical Artifacts</h1>

<p>The current project repository is available <a href="https://github.com/clintmonroe00/capstone-project/tree/develop">here</a>.</p>
<p>See an evaluation of the original project in my <a href="https://youtu.be/sgI5B061QTc">code review</a> or view the files <a href="https://github.com/clintmonroe00/CS-340-Client-Server-Development">here</a>.</p>

<div>
  <!-- Tab Navigation -->
  <ul class="nav nav-tabs mt-3">
    <li class="nav-item">
      <a class="nav-link active" data-toggle="tab" href="#enhancement1">Enhancement One</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" data-toggle="tab" href="#enhancement2">Enhancement Two</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" data-toggle="tab" href="#enhancement3">Enhancement Three</a>
    </li>
  </ul>

  <!-- Tab Content -->
  <div class="tab-content">
    <div id="enhancement1" class="container tab-pane active"><br>
      {% include enhancements/software-design-and-engineering.md %}
    </div>
    <div id="enhancement2" class="container tab-pane fade"><br>
      {% include enhancements/algorithms-and-data-structures.md %}
    </div>
    <div id="enhancement3" class="container tab-pane fade"><br>
      {% include enhancements/databases.md %}
    </div>
  </div>
</div>
