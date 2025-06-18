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
#### The database design overview outlines how the database is stractured such as API, Users, Properties, Bookings, Reviews and Payments
1. API documentation - OpenAPI Standard: The backend APIs are documented using the OpenAPI standard to ensure clarity and ease of integration of application components
                     - Django REST Framework: Provides a comprehensive RESTful API for handling CRUD operations on user and property data
                     - GraphQL: Offers a flexible and efficient query mechanism for interacting with the backend application side
2. Users - the user endpoint register new users, authenticate, and manage user profiles to enable the bookings
3. Property management - this endpoint create, update, retrieve, and delete property listings to be accessed by the users and enable bookings
4. Booking system - this endpoint make, update, and manage bookings, including check-in and check-out details by the users
5. Payment - this endpoint handle payment transactions of users related to bookings
6. Review system - this endpoint post and manage reviews for properties as recommended by users
7. Data optimization endpoint - has (a) Indexing: Implement indexes for fast retrieval of frequently accessed data by users, (b) Caching: Use caching strategies to reduce database load and improve performance by users
