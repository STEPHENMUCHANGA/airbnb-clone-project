## airbnb-clone-project

### An Application Design and Development Simulating Airbnb Booking Platform 

### Project Overview

#### This is a comprehensive real-world application aimed at designing and developing a robust booking platform similar to Airbnb.
#### It involves a full-stack development focusing on backend systems, database design, API development and application security. 
#### Upon completion, the project will showcase complex architectures, workflow, and teamwork collaboration dynamics in building a scalable web application.

### Project Objectives  
#### Master collaborative team workflow using GitHub
#### Depen backend architecture and database design principles
#### Impliment advanced security measures for API development
#### Gain proficiency in designing and managing CI/CD pipelines for efficient deployment
#### Strengthen the ability to document and plan complex software projects effectivley 
#### Develop a popular understanding of integrating technologies such as Django, MySQL and GraphQL in unified ecosystem

### Project Goals 
#### The project will ensure the final application has robust achieved user management, property management, booking system, payment processing, review system, and data optimization

### Tech Stack
#### Technologies to be integrated include Django, Django REST framework, PostgreSQL, GraphQL, Celery, Redis, Docker, and CI/CD

### Team Roles 
#### A typical software development team has a team comprising of:
1. Business Analyst (BA)- responsible for customer's business needs and translates customers business needs into requirements
2. Product Owner (PO)- holds responsibility for the product's vision and evolusion making the final product meet the customer requirements
3. Project Manager (PM)- makes sure a product or its part delivered on time and within budget, and manages and motivates the software development team
4. UX/UI Designer- transforms a product vision into user-friendly designs, and creates user journey for the best user experience and highest conversion rates
5. Software Architect- design a high level architecture, select appropriate tools and platforms to impliment the product vision, and sets up code quality standards and performs code reviews
6. Software Developer- engineers and stabilizes the product, solves any technical problems emerging during development cycle. Software developer does the actual job of writing application codes
7. Quality Assurance (QA) Engineer- makes an application perform according to requirements, and spots functional and non-functional defects
8. Test Automation Engineer- designs a test automation ecosystem, and writes and maintains test scripts for automated testing
9. DevOps Engineer- facilitates the cooperation between development and operations team, and builds continous integration and continous delivery (CI/CD) pipelines for faster delivery 

### Technology Stack Overview
#### The tech stacks outlines the technology applied in creating and running the application
#### These tech stacks include: Django, Django REST framework, PostgreSQL, GraphQL, Celery, Redis, Docker, and CI/CD
1. Django: A high-level Python web framework used for building the RESTful API
2. PostgreSQL: A powerful relational database used for data storage
3. GraphQL: Allows for flexible and efficient querying of data
4. Celery: For handling asynchronous tasks such as sending notifications or processing payments
5. Redis: Used for caching and session management
6. Docker: Containerization tool for consistent development and deployment environments
7. CI/CD Pipelines: Automated pipelines for testing and deploying code changes

### Database Design Overview 
#### The database design overview outlines how the database is stractured such as User management, Property management, Bookings system, Review system, Data optimization and Payments processing
1. User Management: Implement a secure system for user registration, authentication, and profile management
2. Property Management: Develop features for property listing creation, updates, and retrieval
3. Booking System: Create a booking mechanism for users to reserve properties and manage booking details
4. Payment Processing: Integrate a payment system to handle transactions and record payment details
5. Review System: Allow users to leave reviews and ratings for properties
6. Data Optimization: Ensure efficient data retrieval and storage through database optimizations

### Feature Breakdown
#### The features overview outlines the features of airbnb clone such as API documentation, Users, Property management, Booking system, Review system, Payment and Data optimization
1. API documentation - OpenAPI Standard: The backend APIs are documented using the OpenAPI standard to ensure clarity and ease of integration of application components
                     - Django REST Framework: Provides a comprehensive RESTful API for handling CRUD operations on user and property data
                     - GraphQL: Offers a flexible and efficient query mechanism for interacting with the backend application side
2. Users - the user endpoint register new users, authenticate, and manage user profiles to enable the bookings
3. Property management - this endpoint create, update, retrieve, and delete property listings to be accessed by the users and enable bookings
4. Booking system - this endpoint make, update, and manage bookings, including check-in and check-out details by the users
5. Payment - this endpoint handle payment transactions of users related to bookings
6. Review system - this endpoint post and manage reviews for properties as recommended by users
7. Data optimization endpoint - has (a) Indexing: Implement indexes for fast retrieval of frequently accessed data by users, (b) Caching: Use caching strategies to reduce database load and improve performance by users

### API Security Overview
#### This section provide the importance of securing backend APIs which include:
1. REST API: Detailed documentation available through the OpenAPI standard, including endpoints for users, properties, bookings, and payments
2. GraphQL API: Provides a flexible query language for retrieving and manipulating data
#### The major API to be used is REST API that will secure and safeguard endpoints of the application
1. Users

- GET /users/ - List all users
- POST /users/ - Create a new user
- GET /users/{user_id}/ - Retrieve a specific user
- PUT /users/{user_id}/ - Update a specific user
- DELETE /users/{user_id}/ - Delete a specific user
  
2. Properties

- GET /properties/ - List all properties
- POST /properties/ - Create a new property
- GET /properties/{property_id}/ - Retrieve a specific property
- PUT /properties/{property_id}/ - Update a specific property
- DELETE /properties/{property_id}/ - Delete a specific property

3. Bookings

- GET /bookings/ - List all bookings
- POST /bookings/ - Create a new booking
- GET /bookings/{booking_id}/ - Retrieve a specific booking
- PUT /bookings/{booking_id}/ - Update a specific booking
- DELETE /bookings/{booking_id}/ - Delete a specific booking

4. Payments

- POST /payments/ - Process a payment

5. Reviews

- GET /reviews/ - List all reviews
- POST /reviews/ - Create a new review
- GET /reviews/{review_id}/ - Retrieve a specific review
- PUT /reviews/{review_id}/ - Update a specific review
- DELETE /reviews/{review_id}/ - Delete a specific review

### CI/CD Pipeline Overview 
#### The CI/CD pipeline enhances code building, testing, and deployment process
- CI (continous Integration) - Automatically integrates code changes from multiple contributors into a shared repository several times a day where each integration triggers automated builds and tests
- CD (continous deployment/delivery) - Automatically delivers tested code to production (deployment) or a staging environment (delivery) after passing quality checks

#### Importance of CI/CD to software development process
1. Faster Development Cycles: Code changes are tested and deployed automatically, enabling quicker releases

2. Improved Code Quality: Automated testing ensures bugs are caught early in the development cycle

3. Reduced Manual Errors: Automation removes human error from repetitive tasks like testing and deployment

4. Better Collaboration: Teams can integrate and validate their code changes frequently, reducing conflicts

5. Scalability and Consistency: Standardised deployment processes ensure consistent results across environments

#### Typical CI/CD tool
1. Git, GitHub, and GitLab - for version control
2. GitHub Actions, Jenkins, GitLab CI/CD - for CI/CD automation
3. Docker - for containarization
4. Maven, npm, Webpack - for building tools
5. Terraform - for infrastructure as code
6. JUnit, Selenium, Pytest - for testing
7. Prometheus, Grafana - for monitoring
8. Kubernetes, Docker Swarm - for ochestration  

### Define Entities and Relationships in ER Diagram
### Requirements
#### The entity relationship (ER) diagram: ![Entity-Relationship Diagram drawio](https://github.com/user-attachments/assets/0e75f071-6a7c-4166-9430-d7b5e609c895) 
#### This enables the creation of an entity relationship (ER) diagram of the User, Payment, Booking, Property, Message, and Review entities in the database and their relationships as listed:
- User ↔ Property
Relationship: One-to-Many
Description: A single user (with role host) can create multiple properties.
Foreign Key: Property.host_id → User.user_id
- User ↔ Booking
Relationship: One-to-Many
Description: A user (typically a guest) can make many bookings.
Foreign Key: Booking.user_id → User.user_id
- Property ↔ Booking
Relationship: One-to-Many
Description: A property can have multiple bookings.
Foreign Key: Booking.property_id → Property.property_id
- Booking ↔ Payment
Relationship: One-to-One (or One-to-Many if allowing partial payments)
Description: Each booking has one payment record, assuming full payment at once.
Foreign Key: Payment.booking_id → Booking.booking_id
- User ↔ Review
Relationship: One-to-Many
Description: A user can write multiple reviews.
Foreign Key: Review.user_id → User.user_id
- Property ↔ Review
Relationship: One-to-Many
Description: A property can have multiple reviews written by different users.
Foreign Key: Review.property_id → Property.property_id
- User ↔ Message (Sender & Recipient)
Relationship: One-to-Many (twice)
Description: A user can send and receive multiple messages.
Foreign Keys:
  -Message.sender_id → User.user_id
  -Message.recipient_id → User.user_id
