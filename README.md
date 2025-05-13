# airbnb-clone-project
<h2>AirBnB project overview</h2>
<p>The AirBnb Clone project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like AirBnb. It involes a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security.</p>
<p>The tech stack of the project is as follows:</p>
<ul>
  <li>Python</li>
  <li>Docker</li>
  <li>JavaScript</li>
  <li>MySQL</li>
  <li>GraphQL</li>
  <li>Jenkins</li>
  <li>Kubernetes</li>
</ul>

<h2>Team Roles</h2>
<ul>
  <li>Backend Developer: responsible for engineering and stabilizing the product. As well as solving all technical problems emerging during the evelopment lifecycle.</li>
  <li>Quality Engineer: ensures an application performs according to requirements. Additionally, spots functional and non-functional defects</li>
  <li>DevOps Engineer: facilitates cooperation between development and operations teams. Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.</li>
  <li>Database Administrator: Manages database design, indexing, and optimizations.</li>
  <li>Project Manager: makes sure a product or its part is delivered on time and within budget. Also manages and motivates the software development team.</li>
  <li>Business Analyst: understands customer's business processes and is able to translate customer business needs into requirements.</li>
  <li>UI/UX designer: transforms a product vision into user-friendly designs. As well as creates user journeys for the best user experience and highest conversion rates.</li>
</ul>

<h2>Technology Stack</h2>
<li>Django: a high-level Python web framework used for building the RESTful API.</li>
<li>PostgreSQL: a powerful relational database used for data storage.</li>
<li>GraphQL: allows for flexible and efficient querying of data.</li>
<li>Celery: for handling asynchronous tasks such as sending notifications or processing payments.</li>
<li>Redis: used for caching and session management.</li>
<li>Docker: conterization tool for consistent development and deployment environments.</li>
<li>CI/CD: automated pipelines for testing and deploying code changes.</li>

<h2>Database Design</h2>
<ul>
  <li>Users: GET /users/, POST /users/, POST /users/ -  A user can have multiple properties</li>
  <li>Properties: GET /properties/, POST /properties/, PUT /properties/{property_id}/ - Each property can be booked mutliple times(rooms)</li>
  <li>Bookings: GET /bookings/, POST /bookings/, GET /bookings/{booking_id}/ - Each booking is associated with one property</li>
  <li>Reviews: GET /reviews/, POST /reviews/, GET /reviews/{review_id}/ - Each review is attached to one property and a user can review multiple properties</li>
  <li>Payments: POST /payments/ - Each booking is associated to a payment.</li>
</ul>

<h2>Feature Breakdown</h2>
<ul>
  <li>User Management - is a secure system that handles user registration, authentication, and profile management. The feature enables the user to customize their profile and communication preferences for the system.</li>
  <li>Property Management - this portion of the feature encorporates the property listing creation, any updates, and retrieval of information. This determines whether a property is available or booked out for a specific range of days</li>
  <li>Booking System - this handles the booking mechanism for users to reserve properties and manage booking systems. The user can select a date range and properties for that range and area will be visibile to them.</li>
  <li>Payment processing - this refers to the integrated payment gateway system that handles and record payment details. This also includes the conclusion of the bookings as well as the confirmation message.</li>
  <li>Review System - allows users to leave reviews and ratings for properties they have engaged with. This also helps in giving property owners feedback on what is working well on their properties and what isn't.</li>
  <li>Data Optimization - ensure efficien data retrieval and storage through database optimizations. This is crucial for audit and legislative purposes so that the system is readily compliant with all laws.</li>
</ul>
