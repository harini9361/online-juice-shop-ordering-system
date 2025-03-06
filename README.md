# Juice Ordering System #

This **Juice Ordering System** is a web-based application that allows users to browse and order a variety of fresh juices online. The system enables customers to easily view available juice products, add them to their cart, and complete the ordering process. The application ensures a seamless, user-friendly experience with features like secure authentication, cart management, and order tracking. The system is designed using modern technologies such as **Java (Spring Boot)** for the backend, **MySQL** for database management, and **HTML, CSS, JavaScript** for the frontend.

## Features:
- **User Authentication**: Users can sign up and log in securely using Spring Security. Passwords are securely hashed and stored in the database.
- **Product Catalog**: Displays a variety of fresh juices available for purchase, with detailed information such as product name, price, and quantity available.
- **Shopping Cart**: Users can add, remove, and update items in their cart, and the total price is calculated in real-time.
- **Order Management**: After adding items to the cart, users can place an order, view order status, and track their orders.
- **Order History**: Users can view their past orders and order details.
- **Database Integration**: MySQL database is used to store user information, product details, cart information, and orders.
- **Responsive Design**: The frontend is designed to be responsive, ensuring a smooth experience on both desktop and mobile devices.

## Technologies Used:
- **Frontend**:
  - HTML
  - CSS
  - JavaScript
- **Backend**:
  - Java (Spring Boot)
  - Spring Security (for user authentication)
  - Spring Data JPA (for database interaction)
- **Database**:
  - MySQL
- **Tools**:
  - IntelliJ IDEA or Eclipse for Java development
  - MySQL Workbench for database management
  - Git for version control

## Setup and Installation:
1. Clone this repository to your local machine:
   ```bash
  https://github.com/harini9361/online-juice-shop-ordering-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd juice-ordering-system
   ```
3. Import the project into your preferred IDE (IntelliJ IDEA, Eclipse).
4. Make sure you have **MySQL** installed and running on your local machine.
5. Create a database named `juiceshop` in MySQL:
   ```sql
   CREATE DATABASE juiceshop;
   ```
6. Set up your `application.properties` file in the `src/main/resources` folder to include your MySQL database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/juiceshop
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
7. Run the application:
   ```bash
   mvn spring-boot:run
   ```
8. Access the application via `http://localhost:8080` in your web browser.

## Future Enhancements:
- **Payment Gateway Integration**: Adding support for online payments using UPI, credit/debit cards, or digital wallets.
- **Admin Panel**: An admin interface for managing products, users, and orders.
- **Real-time Order Tracking**: Implementing real-time order tracking for customers.
- **Product Reviews and Ratings**: Allowing users to rate and review the juices they've purchased.
- **AI-based Recommendation System**: Suggesting juices based on users' preferences and order history.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




