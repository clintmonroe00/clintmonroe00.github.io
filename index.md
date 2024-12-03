<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Technical Artifacts</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
  
<div class="container mt-3">
  <div>
    <h2>Technical Artifacts</h2>
    <p>The current project repository is available <a href="https://github.com/clintmonroe00/capstone-project/tree/develop">here</a>.</p>
    <p>See an evaluation of the original project in my <a href="https://youtu.be/sgI5B061QTc">code review</a> below or view the files <a href="https://github.com/clintmonroe00/CS-340-Client-Server-Development">here</a>.</p>
    {% include youtube.html id="sgI5B061QTc" %}
  </div>
  <div class="mt-3">
    <h2>Narratives</h2>
    <ul class="nav nav-tabs mt-3">
      {% for enhancement in site.data.enhancements %}
        <li class="nav-item">
          <a class="nav-link{% if forloop.first %} active{% endif %}" data-toggle="tab" href="#{{ enhancement.id }}">{{ enhancement.title }}</a>
        </li> {% endfor %}
    </ul>
    <div class="tab-content">
      {% for enhancement in site.data.enhancements %}
        {% include enhancement.html enhancement=enhancement %}
      {% endfor %}
    </div>
  </div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
