# Technical Artifacts

See the original project in my [CODE REVIEW](https://youtu.be/sgI5B061QTc) or view the files [HERE](https://github.com/clintmonroe00/CS-340-Client-Server-Development).

Check out the current repo [HERE](https://github.com/clintmonroe00/capstone-project/tree/develop)!

# Narratives

- Enhancement One: Software Design and Engineering
- Enhancement Two: Algorithms and Data Structure
- Enhancement Three: Databases

# Targeted enhancements for capstone project:

### Software Design and Engineering
- Frameworks: Transitioning to React for the frontend and FastAPI for the backend will enhance UI responsiveness, modularity, and scalability. React’s component-based structure allows for quicker, cleaner UI updates, while FastAPI’s asynchronous capabilities efficiently handle concurrent requests, reducing response times and boosting performance.
- Rapid Prototyping: Using FastAPI and React facilitates quick MVP iterations, enabling faster adjustments based on user feedback. React’s reusable components and FastAPI’s automatic OpenAPI documentation streamline development and debugging.
- Enhanced User Experience: A React-based UI supports a more responsive and interactive experience, with options for advanced data visualization through libraries like D3.js or Plotly. Incorporating interactive map components, modal pop-ups, and custom filters will further engage users.

### Algorithms and Data Structures
- Optimized Data Structures: Switching from dictionaries to data classes with tuples or arrays will optimize memory usage and speed up processing. Data classes provide type annotations and reduce boilerplate code, improving readability and maintainability.
- Enhanced Algorithm Efficiency: Moving sorting and filtering operations to the database and retrieving only essential data minimizes data transfer and enhances response times, as the database leverages indexing and optimized query execution plans.

### Databases
- ORM (Object-Relational Mapping): Implementing an ORM like SQLAlchemy or Tortoise ORM (for asynchronous handling with FastAPI) standardizes database interactions, reducing vendor-specific SQL differences. ORMs streamline development by adhering to DRY principles, centralizing the data model, and making schema migrations easier.
- Improved Query Efficiency: Performing complex filtering and sorting at the database level takes advantage of indexing and database optimizations, reducing memory and processing overhead on the server side.
- ORM-Driven Security and Validation: ORMs often include built-in protections, like SQL injection safeguards and query validation, adding security with minimal extra code.
