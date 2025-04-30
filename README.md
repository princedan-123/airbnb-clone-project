# airbnb-clone-project
## About the Project
The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.
## 👥Team Roles
- Backend Developer: Responsible for implementing API endpoints, database schemas, and business logic.
- Database Administrator: Manages database design, indexing, and optimizations.
- DevOps Engineer: Handles deployment, monitoring, and scaling of the backend services.
- QA Engineer: Ensures the backend functionalities are thoroughly tested and meet quality standards.
## 🛠Technology Stack
- Django: A high-level Python web framework used for building the RESTful API.
- Django REST Framework: Provides tools for creating and managing RESTful APIs.
- PostgreSQL: A powerful relational database used for data storage.
- GraphQL: Allows for flexible and efficient querying of data.
- Celery: For handling asynchronous tasks such as sending notifications or - processing payments.
- Redis: Used for caching and session management.
- Docker: Containerization tool for consistent development and deployment environments.
- CI/CD Pipelines: Automated pipelines for testing and deploying code changes.
## 📝Database Design
Database entities include the following.
- User: 
- Property:
- Bookings:
- Payments:
- Review:
## 🔍Feature Breakdown
- User Management: This feature allows users to sign-up, sign-in, manage their account
- Property Management: This feature allows the creation, update and removal of property listing
- Bookings: Make, update, and manage bookings, including check-in and check-out details.
- Payment: Handle payment transactions related to bookings.
- Reviews: This feature allows users to post and manage reviews for properties.
## 🔐 API Security
- During the authentication process users' sensitive credentials such as password will be hashed before it is stored in the database. This will prevent exposing sensitive user data in the database incase of a breach.
- CORS will be used to ensure that only request coming from authorize domain will be processed.
- input data e.g data from forms will be validated to prevent CSRF and SQL injection
These security measures are crucial to prevent
- Theft of user sensitive data which could be used to impersonate the user
- Security of transcation is essential to prevent online fraud or stealing of users payment card details
## 🔁CI/CD Pipeline
CI stands for Continuous Integration. It is a modern software engineering practice that involves the automatic testing of code each time an update is made.

CD stands for Continuous Delivery or Continuous Deployment.

Continuous Delivery means the code is automatically prepared for release into production after passing tests. A manual review is required before it is finally deployed to production.

Continuous Deployment, on the other hand, means that the code is automatically pushed to production after passing the testing phase, without a manual review.
Tools for CI/CD include **GitHub Actions**, **Travis CI**, **AWS CodePipeline**, etc.