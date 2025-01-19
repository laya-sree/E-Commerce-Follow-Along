# Ecommerce-follow-along

## eCommerce Website

Welcome to the eCommerce Website project! This is an online platform designed to provide a seamless shopping experience for customers. The website allows users to browse products, add them to their cart, and complete purchases. Admins can manage products, orders, and users from the admin dashboard.


## Table of Contents

### Technologies Used
### Features
### Installation
### Usage
### Folder Structure
### Contributing
### License
### Technologies Used
### Frontend: HTML, CSS, JavaScript, React (or other frontend frameworks)
### Backend: Node.js, Express.js (or other backend technologies)
### Database: MongoDB (or other database technologies like MySQL, PostgreSQL)
### Authentication: JWT (JSON Web Tokens), OAuth (if applicable)
### Payment Integration: Stripe, PayPal (or other payment gateways)
### Deployment: Heroku, AWS, or any other cloud hosting services
### Version Control: Git, GitHub
### Features
### User Registration/Login: Secure user registration and login using JWT.
### Product Listing: Users can view available products by categories, and sort/filter options.
### Shopping Cart: Add, update, and remove items from the shopping cart.
### Order Management: Users can place orders and track their order history.
### Search Functionality: Search for products based on names, categories, and prices.
### Admin Dashboard: Admin users can manage product listings, update prices, manage user data, and view orders.
### Payment Integration: Secure payment options using Stripe/PayPal.
### Responsive Design: Mobile-friendly design for a seamless experience on different devices.

## Milestone 1: Project Overview

In this session, we focused on the foundational elements of the Ecommerce-Follow-Along project. Key topics covered included:

### 1. Project Setup
- Initialized the GitHub repository.
- Set up the basic structure for the application.

### 2. Technology Stack
An overview of the technologies that will be utilized throughout the project:
- Node.js
- Express.js
- MongoDB
- React

### 3. Version Control
- Introduction to Git and GitHub for version control.
- Emphasis on best practices for committing code and managing branches.

### 4. Development Environment
- Configuration of local development environments to ensure consistency across team members.

This milestone sets the stage for further development and deeper exploration of e-commerce functionalities in upcoming sessions.

## Milestone 2: Project Setup and Login Page
In this milestone, we focused on setting up the initial front-end structure and implementing the login page for the application. Key achievements include:

### Front-End Framework:
- Set up the React framework with Vite for a fast and modern development experience.

### Folder Structure:
- Organized the src folder to include separate directories for components, pages, and assets to improve scalability and maintainability.

### Login Page Implementation:
- Developed a basic login page (Login.jsx) that includes a user interface for email and password input.
- Incorporated validation logic to ensure proper user input.

### Routing:
- Implemented React Router for navigation and created routes for the login and signup pages.

### Styling:
- Added basic styling using CSS (App.css) to ensure a clean and user-friendly design.

### Git Integration:
- Added the new files to version control and committed progress to the GitHub repository.

This milestone lays the groundwork for creating the front-end interface and interaction logic for the application.
## Milestone 3: Project Setup for Backend
In this milestone, the foundational backend structure for the e-commerce application was successfully established. Key achievements include:

### Backend Folder Structure:
- Organized the project into clearly defined folders (config, controller, db, middleware, model, and utility) to ensure scalability and maintainability.
### Database Integration:
- Set up a connection to MongoDB using Mongoose, enabling seamless interaction with the database.
### Environment Configuration
- Implemented a .env file to securely manage sensitive data such as database credentials, ensuring better security practices.
### Middleware Implementation
- Created essential middleware for authentication, error handling, and asynchronous error management to streamline request processing and ensure robust error handling.
### Utility Functions 
-Added reusable utility components like a custom error handler to improve consistency and simplify debugging.
### Git Integration
- Configured version control with Git and included a .gitignore file to exclude sensitive files and unnecessary folders like node_modules.

This milestone sets up a solid backend foundation for further development, including API implementation, user authentication, and business logic handling. It ensures that the project is structured, secure, and ready for future expansion.

## Milestone 4: Creating User Model and Controller

In this milestone, the focus was on implementing the user model and controller for managing user data and operations in the backend. Key achievements include:

### User Model:
- Created a User schema using Mongoose to define the structure for storing user information in the MongoDB database.
- Fields include essential user details such as name, email, password, and timestamps.
- Added validation for required fields and unique constraints for the email field.

### Password Hashing:
- Implemented password hashing using bcrypt to securely store user passwords in the database.

### User Controller:
- Developed a user controller to handle user-related backend operations such as registration and login.
- Added methods for creating new users and retrieving user details.

### API Endpoints:
- Set up API routes for user-related operations, including:
  - /api/users/register: Endpoint to register a new user.
  - /api/users/login: Endpoint to authenticate a user.

### Error Handling:
- Added error handling for scenarios such as duplicate email registration and invalid login credentials.

### Git Integration:
- Committed progress to version control, ensuring proper documentation of changes and updates.

This milestone provides the necessary backend infrastructure to manage user data, supporting future features like user authentication and authorization.

## Milestone 5: Creating the Signup Page
In this milestone, we focused on developing the signup page to enable users to create an account within the application. Key achievements include:

### Signup Page Implementation:
- Developed the Signup.jsx component with a user-friendly interface for account registration.
- Included form fields for user details such as name, email, and password.

### Form Validation:
- Added client-side validation logic to ensure proper input formatting and error messages for invalid entries.

### Integration with Routing:
- Configured navigation to and from the signup page using React Router for seamless user flow.

### Styling:
- Enhanced the design of the signup page to align with the application's overall styling for a consistent user experience.

### Code Organization:
- Refactored the code into reusable components where possible to promote cleaner and more maintainable code.

This milestone enhances the user experience by allowing new users to register, paving the way for further integration with back-end user authentication systems