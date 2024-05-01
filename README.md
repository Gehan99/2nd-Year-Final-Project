# Course Finding Web Application

Welcome to the Course Finding Web Application repository! This web application is designed to help students find suitable courses based on their preferences, including course details such as course content, institutes, and pricing.

## Description

This project is a web application developed using Spring Boot (Java) for the backend. It follows the MVC (Model-View-Controller) architecture pattern. The backend handles data management and business logic, while the frontend is not included in this repository.
## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
*Caption for Screenshot 1*

## Controllers

### UserController

- **GET /users**: Retrieve all users.
- **POST /users**: Create a new user.
- **PUT /users**: Update an existing user.
- **DELETE /users/{id}**: Delete a user by ID.

### JobController

- **GET /jobs**: Retrieve all job listings.
- **GET /jobs/{id}**: Retrieve a job listing by ID.
- **POST /jobs**: Create a new job listing.
- **PUT /jobs**: Update an existing job listing.
- **DELETE /jobs/{id}**: Delete a job listing by ID.

### InstituteController

- **GET /institutes**: Retrieve all institutes.
- **GET /institutes/{id}**: Retrieve an institute by ID.
- **POST /institutes**: Create a new institute.
- **PUT /institutes**: Update an existing institute.
- **DELETE /institutes/{id}**: Delete an institute by ID.
- **GET /institutes?name={name}**: Search institutes by name.
- **GET /institutes?no={no}**: Search institutes by registration number.

### CourseController

- **GET /courses**: Retrieve all courses.
- **GET /courses/{id}**: Retrieve a course by ID.
- **POST /courses**: Create a new course.
- **PUT /courses**: Update an existing course.
- **DELETE /courses/{id}**: Delete a course by ID.
- **GET /courses?name={name}**: Search courses by name.

## Data Layer

### Entities

- **User**: Represents a user profile.
- **Job**: Represents a job listing.
- **Institute**: Represents an educational institute.
- **Course**: Represents a course offered by an institute.

### Repositories

- **UserRepository**: Interface for accessing user data.
- **JobRepository**: Interface for accessing job data.
- **InstituteRepository**: Interface for accessing institute data.
- **CourseRepository**: Interface for accessing course data.

## Service Layer

### UserService

- Handles user-related business logic.

### JobService

- Handles job-related business logic.

### InstituteService

- Handles institute-related business logic.

### CourseService

- Handles course-related business logic.

## Installation

1. Clone this repository to your local machine.
2. Import the backend project into your preferred IDE.
3. Configure the database connection settings in the `application.properties` file.
4. Run the backend application.

## Usage

- Use the provided API endpoints to interact with the backend.
- You can test the endpoints using tools like Postman or by integrating them with your frontend application.
