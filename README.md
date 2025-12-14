# E-Commerce Project

A simple e-commerce web application built using **Spring Boot** for the backend and **React** for the frontend. This project includes basic functionalities for an e-commerce platform, such as product browsing, cart management, and dark/light mode options.

## Features

- **Home**: Displays a list of products with options to filter and sort.
- **Add Products**: Admin or authorized users can add products to the inventory, specifying different categories.
- **Categories**: Products are categorized for better browsing.
- **Cart**: Users can add items to the cart and view the products they have added.
- **Search Bar**: Allows users to search for specific products by name.
- **Dark/Light Mode**: Toggle between dark and light themes for the UI.
- **Product Categories**: Ability to add products under different categories, such as electronics, clothing, etc.
- **Product Details**: Each product has the following attributes:
  - **Name**: The name of the product.
  - **Short Description**: A brief description highlighting key features of the product.
  - **Category**: The category to which the product belongs (e.g., Electronics, Fashion, Home Appliances).
  - **Price**: The cost of the product.
  - **Stock Availability**: The number of available units in stock.
  - **Image**: An image of the product, displayed alongside the product details.

## Technologies Used

- **Backend**: 
  - Spring Boot (Java)
  - Spring MVC
  - Spring Data JPA
  - H2 Database 
  
- **Frontend**:
  - React.js
  - React Hooks
  - React Router for routing
  - CSS for styling
  - Theme toggling (Dark/Light Mode) using state management

## Setup and Installation

### 1. Clone the repository
```bash
git clone https://github.com/ManojRTech/ECommerce-project.git
cd ECommerce-project
2. Backend Setup (Spring Boot)
Ensure that you have Java 11 or later installed.

Open the ecom-proj folder in your IDE (e.g., IntelliJ IDEA).

Run the Spring Boot application:

bash
Copy code
./mvnw spring-boot:run
The backend will start on http://localhost:8080.

3. Frontend Setup (React)
Navigate to the frontend folder:

bash
Copy code
cd frontend
Install the required dependencies:

bash
Copy code
npm install
Start the React development server:

bash
Copy code
npm start
The frontend will be available at http://localhost:3000.

4. Connect Backend and Frontend
Make sure the API endpoints in the React app are correctly pointed to the backend (e.g., http://localhost:8080/api/products).

Usage
Visit the Home page to browse products.

Use the search bar to search for specific products.

You can toggle between dark and light mode by clicking the theme toggle button.

Add items to the cart by clicking on the "Add to Cart" button.

Admin can add new products to the system (this feature is available via a simple form).

Contributing
Feel free to fork the repository, submit pull requests, and contribute to the development of this project!
