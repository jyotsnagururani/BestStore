BestStore

BestStore is a web application built with Spring Boot, Java, MySQL, and Eclipse IDE for managing products and handling user authentication efficiently. It provides a backend API to manage products, users, and authentication workflows, making it a solid foundation for any e-commerce or inventory management system.


---

🚀 Features

✅ User Authentication (Login/Signup)

✅ Role-based access (Admin/User)

✅ CRUD operations for products

✅ Product listing and details

✅ MySQL database integration

✅ Built with Spring Boot for scalability



---

🏗️ Tech Stack

Backend

Java (JDK 17+)

Spring Boot

Spring Security (for authentication)

Spring Data JPA (Hibernate)

MySQL


Development Tools

Eclipse IDE

Maven (Build Tool)

Postman (for API testing)



---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/jyotsnagururani/BestStore.git
cd BestStore

2️⃣ Setup MySQL Database

Create a database in MySQL:


CREATE DATABASE beststore;

Update your application.properties file with MySQL credentials:


spring.datasource.url=jdbc:mysql://localhost:3306/beststore
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

3️⃣ Run the Backend Server

Using Maven:

mvn spring-boot:run

Or, directly run the application in Eclipse IDE by running the BestStoreApplication.java class.

Backend will start at: http://localhost:8080


---

📡 API Endpoints

🔑 Authentication

Method	Endpoint	Description

POST	/api/auth/signup	Register new user
POST	/api/auth/login	Login existing user


📦 Products

Method	Endpoint	Description

GET	/api/products	Get all products
GET	/api/products/{id}	Get product by ID
POST	/api/products	Add new product
PUT	/api/products/{id}	Update product
DELETE	/api/products/{id}	Delete product



---

📂 Project Structure

BestStore/
│── src/main/java/com/example/beststore/
│   ├── controller/     # REST Controllers
│   ├── model/          # Entity Classes
│   ├── repository/     # JPA Repositories
│   ├── service/        # Business Logic
│   └── BestStoreApplication.java  # Main App Entry
│
│── src/main/resources/
│   ├── application.properties  # DB Config
│
└── README.md


---

🤝 Contributing

Contributions are welcome!

1. Fork the repo


2. Create a feature branch (feature-xyz)


3. Commit your changes


4. Push to your branch


5. Create a Pull Request




---

📜 License

This project is licensed under the MIT License.


---

👩‍💻 Author

Developed by Jyotsna Gururani 🚀
