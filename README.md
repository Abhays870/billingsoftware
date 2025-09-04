Billing Software
A full-stack, real-world billing software application for retail clients, developed using a modern tech stack. This project provides a complete solution for managing products, categories, orders, and payments, with a focus on a user-friendly and responsive experience.

Screenshots
Dashboard	Order Creation	Payment & Receipt
Dashboard Screenshot		
Order Creation Screenshot		
![Payment and Receipt Screenshot](https://github.com/user-attachments/assets/68af7289-51f6-4eb3-a1d3-628fe61eca3b,		
                              https://github.com/user-attachments/assets/85ce4e6f-7873-4f02-ac4a-1d136d68c358) |
Key Features
Category & Product Management: CRUD (Create, Read, Update, Delete) operations for categories and products.

Order & Billing System: Intuitive interface for creating new orders, adding items, and generating receipts.

Real-time UI Updates: Dynamic updates to the cart and totals as items are added or removed.

Secure Payments: Seamless integration with Razorpay for secure online transactions.

File Upload & Management: Handles product image uploads and storage using AWS S3.

RESTful API: A robust backend built with Spring Boot, providing clean and efficient REST APIs.

User Authentication: Secure access control using Spring JWT (JSON Web Tokens).

Responsive Design: Optimized for a great user experience on various screen sizes.

Technologies Used
Frontend:

React.js
Bootstrap 5
Axios
Vite (for a fast development environment)
Backend:

Spring Boot
Java
Spring Data JPA
MySQL Database
Maven (Build tool)
Spring Security & JWT
Postman
Payment Gateway:

Razorpay
Cloud Services:

AWS S3 (for image storage)

Getting Started
Follow these steps to set up and run the project locally.

Prerequisites
Java JDK 17+
Node.js and npm (or yarn)
MySQL Server
Maven
AWS S3 account and credentials
Razorpay account and API keys
Backend Setup
Clone the repository:
git clone [your-repo-link]
cd your-project-folder
Configure your application.properties file:
Database connection details (spring.datasource.url, spring.datasource.username, spring.datasource.password).
AWS S3 credentials.
Razorpay API keys.
Build and run the Spring Boot application using Maven:
mvn spring-boot:run
Frontend Setup
Navigate to the client directory:
cd client
Install dependencies:
npm install
Start the React application:
npm run dev
The application should now be running on http://localhost:5173 (or the port specified in your Vite config).

Author
Vishal Singh - https://www.linkedin.com/in/vishal-singh-81988928b/ - https://github.com/vishalsingh-2004
Feel free to connect with me if you have any questions or feedback!
