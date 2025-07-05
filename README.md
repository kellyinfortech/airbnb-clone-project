# airbnb-clone-project

## Project Goals <br>
<b>User Management:</b> Implement a secure system for user registration, authentication, and profile management.<br>
<b>Property Management:</b> Develop features for property listing creation, updates, and retrieval.<br>
<b>Booking System:</b> Create a booking mechanism for users to reserve properties and manage booking details.<br>
<b>Payment Processing:</b> Integrate a payment system to handle transactions and record payment details.<br>
<b>Review System:</b> Allow users to leave reviews and ratings for properties.<br>
<b>Data Optimization:</b> Ensure efficient data retrieval and storage through database optimizations.<br>

<br>

# Team Roles <br> 
### Backend Developer: <br>
Responsible for implementing API endpoints, database schemas, and business logic. <br>
### Database Administrator: <br>
Manages database design, indexing, and optimizations.<br>
### DevOps Engineer: <br>
Handles deployment, monitoring, and scaling of the backend services.<br>
### QA Engineer: <br>
Ensures the backend functionalities are thoroughly tested and meet quality standards.<br>

# Technology Stack <br>
<b>Django:<b/> A high-level Python web framework used for building the RESTful API.<br>
<b>Django REST Framework:<b/> Provides tools for creating and managing RESTful APIs.<br>
<b>PostgreSQL:<b/> A powerful relational database used for data storage.<br>
<b>GraphQL:<b/> Allows for flexible and efficient querying of data.<br>
<b>Celery:<b/> For handling asynchronous tasks such as sending notifications or processing payments.<br>
<b>Redis:<b/> Used for caching and session management.<br>
<b>Docker:<b/> Containerization tool for consistent development and deployment environments.<br>
<b>CI/CD Pipelines:<b/> Automated pipelines for testing and deploying code changes.<br>

# Database Design <br>
<b>Users</b> <br>

GET /users/ - List all users<br>
POST /users/ - Create a new user<br>
GET /users/{user_id}/ - Retrieve a specific user<br>
PUT /users/{user_id}/ - Update a specific user<br>
DELETE /users/{user_id}/ - Delete a specific user<br>
<b>Properties </b> <br>

GET /properties/ - List all properties<br>
POST /properties/ - Create a new property<br>
GET /properties/{property_id}/ - Retrieve a specific property<br>
PUT /properties/{property_id}/ - Update a specific property<br>
DELETE /properties/{property_id}/ - Delete a specific property<br>
<b>Bookings </b> <br>

GET /bookings/ - List all bookings<br>
POST /bookings/ - Create a new booking<br>
GET /bookings/{booking_id}/ - Retrieve a specific booking<br>
PUT /bookings/{booking_id}/ - Update a specific booking<br>
DELETE /bookings/{booking_id}/ - Delete a specific booking<br>
<b>Payments </b> <br>

POST /payments/ - Process a payment<br>
<b>Reviews </b> <br>

GET /reviews/ - List all reviews<br>
POST /reviews/ - Create a new review<br>
GET /reviews/{review_id}/ - Retrieve a specific review<br>
PUT /reviews/{review_id}/ - Update a specific review<br>
DELETE /reviews/{review_id}/ - Delete a specific review<br>
