---
layout: default
title: ePortfolio
---

<div class="container mt-3 mb-3">
  <div class="mt-3">
    <h2>Self-Assessment</h2>
    <p>Completing my coursework in the Computer Science program and developing my ePortfolio have been transformative experiences that highlight my technical expertise and professional growth. Throughout the program, I have honed skills in software design, database management, algorithms, and security, which are integral to my career as a Senior IT Manager. The ePortfolio serves as a tangible showcase of my ability to apply industry-standard tools and techniques, as demonstrated by my capstone project: transitioning an animal shelter management dashboard from a Python-based application to a full-stack architecture using React, FastAPI, and SQLite. This process has underscored my strengths in adapting to emerging technologies and creating scalable, user-centered solutions.</p>
    <p>One of the key takeaways from the program has been the importance of collaboration in a team environment and effective communication with stakeholders. Managing international teams in my current role has equipped me with the ability to translate technical concepts into actionable insights for diverse audiences. This skill was further refined during my capstone, where I implemented agile development practices, breaking the project into structured sprints to ensure clarity and accountability. Additionally, my understanding of data structures and algorithms allowed me to optimize performance through efficient database queries and structured data handling, while my focus on security was evident in implementing user authentication with Firebase and rate limiting via SlowAPI.</p>
    <p>The artifacts in my ePortfolio collectively highlight my capabilities across multiple domains in computer science. The enhanced animal shelter dashboard exemplifies my expertise in software engineering, while the integration of advanced algorithms and data visualization showcases my ability to present complex datasets in an intuitive and actionable manner. My emphasis on database security and optimization, combined with a user-friendly interface, demonstrates a holistic approach to problem-solving that aligns with real-world needs. Together, these artifacts provide a comprehensive view of my technical skills and professional growth, emphasizing my readiness to contribute meaningfully to any computing environment.</p>
    <p>Reflecting on my journey, the capstone experience has not only solidified my technical knowledge but also reaffirmed my professional values of innovation, collaboration, and adaptability. By integrating modern technologies and adhering to best practices, I have demonstrated my ability to deliver robust solutions that meet user and organizational goals. This ePortfolio serves as both a culmination of my academic achievements and a stepping stone toward future opportunities, showcasing my commitment to excellence in the dynamic field of computer science.</p>
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
        <p>The written narrative for this enhancement is available <a href="https://github.com/clintmonroe00/clintmonroe00.github.io/blob/main/Monroe%2C%20Clint%203-2%20Milestone%20Two.docx">here</a>.</p>
        <h4>Targeted Enhancements:</h4>
        <ul>
          <li><strong>Frameworks:</strong> Transitioning to React for the frontend and FastAPI for the backend will enhance UI responsiveness, modularity, and scalability. React’s component-based structure allows for quicker, cleaner UI updates, while FastAPI’s asynchronous capabilities efficiently handle concurrent requests, reducing response times and boosting performance.</li>
          <li><strong>Rapid Prototyping:</strong> Using FastAPI and React facilitates quick MVP iterations, enabling faster adjustments based on user feedback. React’s reusable components and FastAPI’s automatic OpenAPI documentation streamline development and debugging.</li>
          <li><strong>Enhanced User Experience:</strong> A React-based UI supports a more responsive and interactive experience, with options for advanced data visualization through libraries like D3.js or Plotly. Incorporating interactive map components, modal pop-ups, and custom filters will further engage users.</li>
        </ul>
      </div>
      <div id="enhancement2" class="container tab-pane fade"><br>
        <h3>Algorithms and Data Structures</h3>
        <p>The repository for this enhancement is available <a href="https://github.com/clintmonroe00/capstone-project/tree/sprint-two">here</a>.</p>
        <p>The written narrative for this enhancement is available <a href="https://github.com/clintmonroe00/clintmonroe00.github.io/blob/main/Monroe%2C%20Clint%204-2%20Milestone%20Three.docx">here</a>.</p>
        <h4>Targeted Enhancements:</h4>
        <ul>
          <li><strong>Optimized Data Classes and Structures:</strong> Transitioning from dictionaries to data classes with tuples or arrays will optimize memory usage and processing speed, as these structures are generally more performant in Python. Data classes offer type annotations and reduce boilerplate code, promoting better code readability and maintainability.</li>
          <li><strong>Enhanced Algorithm Efficiency:</strong> By moving sorting and filtering operations to the database and retrieving only necessary data, you reduce data transfer and enhance response times. Leveraging database-level operations improves overall algorithmic efficiency, as the database can use indexing and optimized query execution plans.</li>
          <li><strong>Complex Queries and Efficient Filtering:</strong> Data structures such as arrays or lists will simplify handling ordered data, improving performance for tasks that involve sorting or searching, especially for large datasets.</li>
        </ul>
      </div>
      <div id="enhancement3" class="container tab-pane fade"><br>
        <h3>Databases</h3>
        <p>The repository for this enhancement is available <a href="https://github.com/clintmonroe00/capstone-project/tree/sprint-three">here</a>.</p>
        <p>The written narrative for this enhancement is available <a href="https://github.com/clintmonroe00/clintmonroe00.github.io/blob/main/Monroe%2C%20Clint%205-2%20Milestone%20Four.docx">here</a>.</p>
        <h4>Targeted Enhancements:</h4>
        <ul>
          <li><strong>ORM (Object-Relational Mapping):</strong> Implementing an ORM like SQLAlchemy or Tortoise ORM (for asynchronous handling with FastAPI) enables you to work with a unified data model, streamlining database interactions and eliminating vendor-specific SQL differences. This also allows for faster prototyping by eliminating repetitive SQL code, which conforms to DRY (Don't Repeat Yourself) principles.</li>
          <li><strong>Centralized Data Model:</strong> With the ORM, the data model is defined in one location, reducing the potential for inconsistencies. Changes in data models are automatically synchronized with the database, making schema migrations easier.</li>
          <li><strong>Improved Query Efficiency:</strong> Moving complex filtering and sorting to the database level leverages indexing and optimized database operations, reducing memory overhead and minimizing processing time on the server side.</li>
          <li><strong>ORM-Driven Security and Validation:</strong> ORMs often have built-in security features like SQL injection protection and automatic query validation, adding an extra layer of security with minimal additional code.</li>
        </ul>
    </div>
  </div>
</div>

