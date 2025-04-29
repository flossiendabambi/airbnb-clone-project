# airbnb-clone-project


## Airbnb clone project will imitate the original airbnb web app.

### Team Roles
   
1. Back-end engineeer
   Develops the server side of the app and back-end logic.
2. Database Administrator
   Manages database design, indexing, and optimizations.
3. DevOps Engineer
   Handles deployment, monitoring, and scaling of the backend services.
4. QA Engineer
   Ensures the backend functionalities are thoroughly tested and meet quality standards.

   
### Technology Stack
1. Django: A high-level Python web framework used for building the RESTful API.
2. Django REST Framework: Provides tools for creating and managing RESTful APIs.
3. PostgreSQL: A powerful relational database used for data storage.
4. GraphQL: Allows for flexible and efficient querying of data.
5. Celery: For handling asynchronous tasks such as sending notifications or processing payments.
6. Redis: Used for caching and session management.
7. Docker: Containerization tool for consistent development and deployment environments.
8. CI/CD Pipelines: Automated pipelines for testing and deploying code changes.

### Database Design
1. Users
   Email address
   Phone number
   Properties
   Rating
   
2. Properties
   Price
   Images
   Aout
   
3. Bookings
   Date
   Number of guests
   
4. Reviews
   
5. Payments

### Feature Breakdown
1. API Documentation
   OpenAPI Standard: The backend APIs are documented using the OpenAPI standard to ensure clarity and ease of integration.
   Django REST Framework: Provides a comprehensive RESTful API for handling CRUD operations on user and property data.
   GraphQL: Offers a flexible and efficient query mechanism for interacting with the backend.
2. User Authentication
   Endpoints: /users/, /users/{user_id}/
   Features: Register new users, authenticate, and manage user profiles.
3. Property Management
   Endpoints: /properties/, /properties/{property_id}/
   Features: Create, update, retrieve, and delete property listings.
4. Booking System
   Endpoints: /bookings/, /bookings/{booking_id}/
   Features: Make, update, and manage bookings, including check-in and check-out details.
5. Payment Processing
   Endpoints: /payments/
   Features: Handle payment transactions related to bookings.
6. Review System
   Endpoints: /reviews/, /reviews/{review_id}/
   Features: Post and manage reviews for properties.
7. Database Optimizations
   Indexing: Implement indexes for fast retrieval of frequently accessed data.
   Caching: Use caching strategies to reduce database load and improve performance.

### API Security
1. Authentication
   To know who is accessing the API
   
2. Authorization
   To restrict what users can do

3. Input Validation and Sanitization
   Sanitize input to avoid SQL injection

4. Rate Limiting
   Prevent abuse and DDoS attacks by limiting:
   -Number of requests per IP per minute
   -Sensitive actions like login attempts
