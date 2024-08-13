---

# E-commerce Platform

This project is a fully functional e-commerce platform built with React for the frontend, Spring Boot for the backend, and SQL with H2 for the database. It provides a comprehensive solution for online shopping, featuring user registration, product browsing, a shopping cart, and order management.

## Features

- **Product Management:** Browse and search for products with detailed descriptions and images.
- **Shopping Cart:** Add, remove, and manage products in a user-friendly shopping cart interface.
- **Order Processing:** Seamless order placement and order history management for users.
- **Admin Panel:** Admin functionalities for managing products, orders, and users.
- **Responsive Design:** Mobile-friendly design ensuring optimal user experience across devices.

## Technologies Used

- **Frontend:** React, HTML, CSS, JavaScript
- **Backend:** Spring Boot, RESTful APIs
- **Database:** H2 (for development/testing), SQL (for production)
- **Others:** JSON Web Tokens (JWT) for authentication, Axios for HTTP requests

## Prerequisites

- **Node.js:** Ensure you have Node.js installed to run the React frontend.
- **Java:** Ensure you have Java 8 or higher installed to run the Spring Boot backend.
- **Maven:** Ensure Maven is installed to manage the backend project dependencies.

## Installation

### Frontend (React)

1. **Navigate to the frontend directory:**
   ```bash
   cd frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the React development server:**
   ```bash
   npm start
   ```

   The React app will run on `http://localhost:3000`.

### Backend (Spring Boot)

1. **Navigate to the backend directory:**
   ```bash
   cd backend
   ```

2. **Build the Spring Boot application:**
   ```bash
   mvn clean install
   ```

3. **Run the application:**
   ```bash
   mvn spring-boot:run
   ```

   The backend server will run on `http://localhost:8080`.

## Configuration

- **Database Configuration:** The application uses H2 database for development. For production, you can configure a different SQL database by updating the `application.properties` file in the `src/main/resources` directory of the backend.

- **Frontend Configuration:** The API endpoint for the frontend can be configured in the React application's environment files.

## Usage

1. **Access the platform:** Open your browser and go to `http://localhost:5173`.
2. **Register/Login:** Create an account or log in to access the platform's features.
3. **Browse Products:** Explore available products and add them to your cart.
4. **Checkout:** Complete the purchase process and view your order history.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch:** `git checkout -b feature/YourFeature`
3. **Commit your changes:** `git commit -m 'Add a feature'`
4. **Push to the branch:** `git push origin feature/YourFeature`
5. **Open a pull request.**


## Contact

For questions or support, please contact arryamanmishra@gmail.com or create an issue in this repository.

![Screenshot 2024-08-13 192657](https://github.com/user-attachments/assets/860f90a2-bf69-47c9-a782-40e3c50d8178)
![Screenshot 2024-08-13 192648](https://github.com/user-attachments/assets/548c27a8-869e-4a9f-a7f0-9b8b83072b38)
![Screenshot 2024-08-13 192717](https://github.com/user-attachments/assets/5328e369-4ca6-4f66-aadd-1f0f8904936e)


---
