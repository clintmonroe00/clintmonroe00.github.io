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
    <div class="tab-content">
      <div id="enhancement1" class="container tab-pane active"><br>
        <h3>Software Design and Engineering</h3>
        <p>The repository for this enhancement is available <a href="https://github.com/clintmonroe00/capstone-project/tree/sprint-one">here</a>.</p>
        <h4>Targeted Enhancements:</h4>
        <ul>
          <li><strong>Frameworks:</strong> Transitioning to React for the frontend and FastAPI for the backend will enhance UI responsiveness, modularity, and scalability. React’s component-based structure allows for quicker, cleaner UI updates, while FastAPI’s asynchronous capabilities efficiently handle concurrent requests, reducing response times and boosting performance.</li>
          <li><strong>Rapid Prototyping:</strong> Using FastAPI and React facilitates quick MVP iterations, enabling faster adjustments based on user feedback. React’s reusable components and FastAPI’s automatic OpenAPI documentation streamline development and debugging.</li>
          <li><strong>Enhanced User Experience:</strong> A React-based UI supports a more responsive and interactive experience, with options for advanced data visualization through libraries like D3.js or Plotly. Incorporating interactive map components, modal pop-ups, and custom filters will further engage users.</li>
        </ul>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
      <div id="enhancement2" class="container tab-pane fade"><br>
        <h3>Algorithms and Data Structures</h3>
        <p>Details about Enhancement Two...</p>
      </div>
      <div id="enhancement3" class="container tab-pane fade"><br>
        <h3>Databases</h3>
        <p>Details about Enhancement Three...</p>
      </div>
    </div>
  </div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
