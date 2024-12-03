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
    <h2>Self-Assessment</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
  </div>
  <div class="mt-3">
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
        <p>The primary artifact for my ePortfolio is an interactive animal shelter management dashboard, a web application developed to support a fictional client’s need for organizing and analyzing rescue animal data. This dashboard was initially created in a previous course as a Python-based application using the Dash framework. For my capstone project, I enhanced the application by transitioning its architecture to React for the frontend and FastAPI for the backend, implemented with SQLite as the database. These upgrades significantly improve performance, scalability, and the user experience. The enhancements I’ve made this week include setting up a React and FastAPI environment, configuring CORS, implementing Axios for API requests, establishing database communication, and setting up basic CRUD operations. Together, these components provide a functional MVP that allows users to add and view animal records.</p>
        <p>I selected this dashboard for my ePortfolio because it represents a comprehensive application of my skills in software design, algorithms, and database management. It demonstrates my ability to apply industry-standard technologies and best practices, such as asynchronous processing, component-based architecture, and ORM-based data management. These improvements showcase my capability in designing a solution that not only meets user needs but also aligns with software engineering principles. By moving sorting and filtering operations to the database layer, optimizing data structures with ORM models, and implementing asynchronous API requests, I’m showcasing my ability to create efficient and maintainable applications.</p>
        <p>The enhancements align closely with the course outcomes I aimed to achieve in Module One. I demonstrated effective software design and the application of tools and techniques, building an MVP that emphasizes algorithmic efficiency and data handling. I plan to further align with security-focused outcomes by implementing measures to mitigate vulnerabilities in FastAPI. Additionally, the structured communication between React and FastAPI highlights my progress in achieving a collaborative environment, setting up the application for scalability and teamwork.</p>
        <p>Throughout the enhancement process, I learned a great deal about handling frontend-backend communication in a full-stack environment, particularly with asynchronous requests in FastAPI. The initial setup of React and FastAPI presented challenges, especially in configuring CORS and ensuring seamless data transfer through Axios. However, overcoming these issues improved my understanding of real-world integration challenges, especially in aligning frontend and backend components in a scalable and responsive way. This experience has prepared me to tackle additional optimizations and security configurations in future sprints, with a focus on delivering a final product that is robust, secure, and user-friendly.</p>
        <p>I would like to note that due to the interconnected nature of building a full-stack application, I’ve found it challenging to focus exclusively on Software Design and Engineering without addressing Algorithms, Data Structures, and Database considerations simultaneously. Recognizing this overlap, I have structured the work into four distinct sprints, covering weeks three through six, to ensure a balanced approach across all areas of development. Since the project requires milestones in the initial three weeks, I’ve allocated the final sprint for backlog tasks and polish to refine the application. Each sprint has defined goals, tasks, and milestones, aligning with both user and developer stories that I crafted to guide development. The plan for each sprint is as follows:</p>
        <ul>
          <li><strong>Sprint 1: Project Initialization & Environment Setup -</strong> This sprint focuses on setting up the project plan and environment, with basic configurations in React, FastAPI, and SQLAlchemy.</li>
          <li><strong>Sprint 2: Core Feature Development -</strong> Emphasizes frontend interactivity and backend efficiency through asynchronous API endpoints and interactive data features.</li>
          <li><strong>Sprint 3: Data Optimization & Security -</strong> Optimizes data structures and queries within SQLAlchemy to enhance performance and security.</li>
          <li><strong>Sprint 4: Backlog & Polish -</strong> Reserved for completing remaining items, enhancing the UI/UX, and final testing to ensure a seamless, reliable user experience.</li>
        </ul>
      </div>
      <div id="enhancement2" class="container tab-pane fade"><br>
        <h3>Algorithms and Data Structures</h3>
        <p>The repository for this enhancement is available <a href="https://github.com/clintmonroe00/capstone-project/tree/sprint-two">here</a>.</p>
        <h4>Targeted Enhancements:</h4>
        <ul>
          <li><strong>Optimized Data Classes and Structures:</strong> Transitioning from dictionaries to data classes with tuples or arrays will optimize memory usage and processing speed, as these structures are generally more performant in Python. Data classes offer type annotations and reduce boilerplate code, promoting better code readability and maintainability.</li>
          <li><strong>Enhanced Algorithm Efficiency:</strong> By moving sorting and filtering operations to the database and retrieving only necessary data, you reduce data transfer and enhance response times. Leveraging database-level operations improves overall algorithmic efficiency, as the database can use indexing and optimized query execution plans.</li>
          <li><strong>Complex Queries and Efficient Filtering:</strong> Data structures such as arrays or lists will simplify handling ordered data, improving performance for tasks that involve sorting or searching, especially for large datasets.</li>
        </ul>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
      <div id="enhancement3" class="container tab-pane fade"><br>
        <h3>Databases</h3>
        <p>The repository for this enhancement is available <a href="https://github.com/clintmonroe00/capstone-project/tree/sprint-three">here</a>.</p>
        <h4>Targeted Enhancements:</h4>
        <ul>
          <li><strong>ORM (Object-Relational Mapping):</strong> Implementing an ORM like SQLAlchemy or Tortoise ORM (for asynchronous handling with FastAPI) enables you to work with a unified data model, streamlining database interactions and eliminating vendor-specific SQL differences. This also allows for faster prototyping by eliminating repetitive SQL code, which conforms to DRY (Don't Repeat Yourself) principles.</li>
          <li><strong>Centralized Data Model:</strong> With the ORM, the data model is defined in one location, reducing the potential for inconsistencies. Changes in data models are automatically synchronized with the database, making schema migrations easier.</li>
          <li><strong>Improved Query Efficiency:</strong> Moving complex filtering and sorting to the database level leverages indexing and optimized database operations, reducing memory overhead and minimizing processing time on the server side.</li>
          <li><strong>ORM-Driven Security and Validation:</strong> ORMs often have built-in security features like SQL injection protection and automatic query validation, adding an extra layer of security with minimal additional code.</li>
        </ul>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>
  </div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
