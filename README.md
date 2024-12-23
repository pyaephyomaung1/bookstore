# bookstore
This is a bookstore project built with Spring Boot for the backend and React for the frontend. It allows users to browse books, view details, and interact with a simple e-commerce interface. The project is a demonstration of my skills in full-stack development, with a focus on building scalable and efficient web applications.

The project demonstrates key concepts such as:

    RESTful API development with Spring Boot
    Frontend development with React
    Integration of MySQL database for data management
    Use of DTOs and Entities to manage data

    Note: This project is for demonstration purposes and does not contain all books in the world, as it is a learning project.

Features

    View books by categories (e.g., New Arrivals, Best Sellers)
    Filter books based on category and price
    Book details page with book cover image, description, and pricing
    Pagination support for browsing large datasets
    Simple user interface with React and modern styling

Technologies Used

    Frontend: React, Next.js, TypeScript, CSS (Tailwind)
    Backend: Spring Boot, Spring Data JPA
    Database: MySQL
    Other: Docker (for environment setup), GitHub Actions (for CI/CD)

Run MySQL files in resources/data/...

    5 sql files to run manually after running Spring Application

    
Setup
Prerequisites

Before running this project locally, make sure you have:

    Java (for Spring Boot)
    Node.js (for React)
    MySQL (or use a Dockerized MySQL instance)

Clone the Repository

git clone https://github.com/yourusername/bookstore-project.git
cd bookstore-project

Backend Setup (Spring Boot)

    Navigate to the backend directory:

cd backend

Install dependencies and run the Spring Boot application:

    ./mvnw spring-boot:run

    This starts the Spring Boot backend on http://localhost:8080.

Frontend Setup (React)

    Navigate to the frontend directory:

cd frontend

Install dependencies and run the React app:

    npm install
    npm start

    This starts the React app on http://localhost:3000.

Database Setup

    Ensure you have MySQL running and create a database bookstore_db.
    Update application.properties (Spring Boot) to match your MySQL credentials.
    Run the Spring Boot application to set up the tables.

Usage

Once both the backend and frontend are running, open your browser and navigate to http://localhost:3000 to explore the bookstore interface. You can:

    Browse through the books
    View details of each book
    Interact with pagination and filtering features

Contributing

Feel free to fork the repository and submit a pull request if you'd like to contribute or improve the project.
License

This project is licensed under the MIT License - see the LICENSE file for details.
