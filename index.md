# Technical Artifacts

<div class="container mt-3">
  <h2>Technical Artifacts</h2>
  <ul class="nav nav-tabs">
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
      <h3>Enhancement One: Software Design and Engineering</h3>
      [Repository](https://github.com/clintmonroe00/capstone-project/tree/sprint-one)
        - Frameworks: Transitioning to React for the frontend and FastAPI for the backend will enhance UI responsiveness, modularity, and scalability. React’s component-based structure allows for quicker, c[...]
        - Rapid Prototyping: Using FastAPI and React facilitates quick MVP iterations, enabling faster adjustments based on user feedback. React’s reusable components and FastAPI’s automatic OpenAPI docum[...]
        - Enhanced User Experience: A React-based UI supports a more responsive and interactive experience, with options for advanced data visualization through libraries like D3.js or Plotly. Incorporating i[...]
      <iframe src="pdfs/Software Design and Engineering.pdf" width="100%" height="400px"></iframe>
    </div>
    <div id="enhancement2" class="container tab-pane fade"><br>
      <h3>Enhancement Two: Algorithms and Data Structures</h3>
      [Repository](https://github.com/clintmonroe00/capstone-project/tree/sprint-two)
        - Optimized Data Structures: Switching from dictionaries to data classes with tuples or arrays will optimize memory usage and speed up processing. Data classes provide type annotations and reduce boil[...]
        - Enhanced Algorithm Efficiency: Moving sorting and filtering operations to the database and retrieving only essential data minimizes data transfer and enhances response times, as the database leverag[...]
      <iframe src="pdfs/Algorithms and Data Structures.pdf" width="100%" height="400px"></iframe>
    </div>
    <div id="enhancement3" class="container tab-pane fade"><br>
      <h3>Enhancement Three: Databases</h3>
      [Repository](https://github.com/clintmonroe00/capstone-project/tree/sprint-three)
        - ORM (Object-Relational Mapping): Implementing an ORM like SQLAlchemy or Tortoise ORM (for asynchronous handling with FastAPI) standardizes database interactions, reducing vendor-specific SQL differe[...]
        - Improved Query Efficiency: Performing complex filtering and sorting at the database level takes advantage of indexing and database optimizations, reducing memory and processing overhead on the serve[...]
        - ORM-Driven Security and Validation: ORMs often include built-in protections, like SQL injection safeguards and query validation, adding security with minimal extra code.
      <iframe src="pdfs/Databases.pdf" width="100%" height="400px"></iframe>
    </div>
  </div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
