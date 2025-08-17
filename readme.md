# 📚 Bookstore Management System

A simple and functional Bookstore Management System built with PHP and MySQL. This project allows users to browse books, register, log in, manage a cart, and place orders with cash on delivery.

## 🚀 Features

- 🧾 User Registration & Login
- 🔍 Book Search by Category or Name
- 🛒 Cart Management
- 📦 Order Placement (Cash on Delivery)
- 🔐 Session-based Authentication
- 📬 Contact Form
- 🔐 Password Recovery

## 🛠 Technologies Used

- PHP (Procedural)
- MySQL
- HTML/CSS
- JavaScript (minimal)
- Sessions for user state

## 📁 Project Structure
├── index.php  
├── login.php / register.php / logout.php  
├── cart.php / addtocart.php / order.php / order_process.php  
├── book_list.php / bookdetail.php / search.php  
├── contact.php / contact_process.php  
├── forget_password.php / forget_password_process.php  
├── includes  
├── header.php  
├── footer.php  
├──connection.php  
├── style.css


## 🧪 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/bookstore-management.git
   ```
2. **Import the Database**
- Create a MySQL database named bms
- Import the SQL file (if available) with tables like book, category, register, order, contact

3. **Configure Database Connection**
- Edit includes/connection.php with your DB credentials:
  $link = mysqli_connect("localhost", "root", "", "bms");

4. **Run Locally**
- Place the project in your local server directory (e.g., htdocs for XAMPP)
- Start Apache and MySQL
- Visit http://localhost/bookstore-management/index.php

## 📄 License
This project is open-source under the MIT License.

## 🙌 Acknowledgments
- Inspired by basic e-commerce systems
- Built for educational purposes
