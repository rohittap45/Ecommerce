# eCommerce Application

This is a full-stack eCommerce application for VeggieMart, featuring a Java Spring Boot backend and a React frontend.

## Project Structure

```
eCommerce-Application/
├── eCommersApp/      # Backend (Spring Boot)
│   ├── src/
│   ├── pom.xml
│   └── ...
├── frontend/         # Frontend (React)
│   ├── src/
│   ├── package.json
│   └── ...
└── ER_diagram.png    # Entity-Relationship Diagram
```

## Features

- User authentication with JWT
- Product catalog and management
- Shopping cart and order processing
- Payment and shipping modules
- Admin, customer, and shipper roles
- Review and rating system
- Exception handling and validation

## Tech Stack

- **Backend:** Java, Spring Boot, Maven, JPA/Hibernate
- **Frontend:** React, JavaScript, Axios, React Router
- **Database:** MySQL
- **Security:** JWT-based authentication

## Getting Started

### Prerequisites

- Java 17+
- Maven
- Node.js & npm

### Backend Setup

1. Navigate to the backend directory:
    ```sh
    cd eCommerce-Application/eCommersApp
    ```
2. Build and run the Spring Boot application:
    ```sh
    mvn clean install
    mvn spring-boot:run
    ```
3. The backend will start on [http://localhost:8080](http://localhost:8080).

### Frontend Setup

1. Navigate to the frontend directory:
    ```sh
    cd eCommerce-Application/frontend
    ```
2. Install dependencies:
    ```sh
    npm install
    ```
3. Start the React development server:
    ```sh
    npm start
    ```
4. The frontend will start on [http://localhost:3000](http://localhost:3000).

## Database Setup

- Configure your database connection in `eCommersApp/src/main/resources/application.properties`.

## ER Diagram

See [`ER_diagram.png`](eCommerce-Application/ER_diagram.png) for the database schema.


