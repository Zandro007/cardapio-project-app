# Virtual Menu - README

## Description

Welcome to the Virtual Menu, a comprehensive system for restaurant menu management. This project utilizes React on the frontend for a user-friendly interface and Java on the backend to provide robust functionalities. The PostgreSQL database is employed to store and manage data related to menu items.

## System Requirements

Make sure you have the following tools installed on your machine before running the program:

- Node.js
- npm (Node Package Manager)
- Java SDK
- PostgreSQL

## Database Configuration

1. Create a PostgreSQL database with the desired name.
2. Update the database connection information in the `application.properties` file in the `backend/src/main/resources` directory.

## Backend Configuration

1. Navigate to the `backend` directory in the terminal.
2. Run `./mvnw spring-boot:run` to start the backend server.

## Frontend Configuration

1. Navigate to the `frontend` directory in the terminal.
2. Run `npm install` to install dependencies.
3. Update the backend connection URL in the `src/services/api.js` file.
4. Run `npm start` to start the frontend server.

## Usage

Access the system through the browser using the address provided by the frontend server. The system allows for intuitive viewing, adding, editing, and deleting of menu items.

## Contributions

Contributions are welcome! Feel free to open issues and submit pull requests.

## Author

This project was developed by [Eli Soares] - https://www.linkedin.com/in/elisandro-soares/.

---
