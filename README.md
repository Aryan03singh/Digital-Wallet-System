# Digital-Wallet-System
Designed and implemented a RESTful API for an E-Wallet payment system supporting core functionalities such as user management, wallet balance operations, and transaction processing. The application is built using Java with Spring Boot, utilizes Hibernate and JDBC for database interaction, Maven for project management, and MySQL for data storage.
<img width="900" height="600" alt="image" src="https://github.com/user-attachments/assets/06cd107d-2fff-4e2d-95cf-fc42f65ed563" />
The Digital Wallet Application's REST API, developed by E PAY, offers customers the convenience and flexibility of being able to transfer money to and from their digital wallet and linked bank accounts. The API also allows for transactions with other registered customers on the E PAY platform and the ability to make payments directly to saved beneficiaries through their bank accounts.

In addition to these features, the API also enables customers to manage their bills and perform basic CRUD operations, similar to other digital wallet applications. Security is of utmost importance, and the API Webservice implements customer and admin authentication and validation.

The primary objective of the API is to provide customers with a streamlined and user-friendly digital wallet payment experience. The API is built on REST Architecture and can be consumed by any client that supports HTTP Protocol.

This solution is perfect for anyone looking for quick, easy, and secure online transactions and can help small businesses, freelancers, and individuals manage their transactions and bills easily and securely. It can also be integrated with any application that supports REST API, making it suitable for a wide range of use cases.

Tech Stack
JAVA
SPRING
SPRINGBOOT
HIBERNATE
MAVEN
J.D.B.C
MYSQL
POSTMAN
Dependencies
SPRING DATA JPA
SPRING BOOT DEVTOOLS
SPRING WEB
HIBERNATE
MYSQL DRIVER
VALIDATION
LOMBOK
SWAGGER UI
Features
Transfer money to and from digital wallet and linked bank accounts
Perform transactions with other registered customers on the E PAY platform
Make payments directly to saved beneficiaries through bank accounts
Manage bills and perform basic CRUD operations
Customer and admin authentication and validation
Streamlined and user-friendly digital wallet payment experience
Built on REST Architecture
Consumable by clients that support HTTP Protocol
Suitable for quick, easy and secure online transactions
Helps small businesses, freelancers and individuals manage their transactions and bills easily and securely
Can be integrated with any application that supports REST API
Suitable for a wide range of use cases.
User Functionalities
Authentication Management

Endpoint for Sign Up
Endpoint for Sign In
Endpoint for Sign Out
Financial Management

Endpoint for Updating Personal Information and Address
Endpoint for Adding Bank Account Information
Endpoint for Updating Bank Account Information
Endpoint for Viewing Bank Account Information
Endpoint for Topping Up Wallet from Bank Account Balance
Endpoint for Transferring Money from Wallet to Bank Account
Endpoint for Transferring Funds to other Customers
Endpoint for Transferring Funds to Beneficiaries
Endpoint for Making Bill Payments
Endpoint for Checking Wallet Balance
Administrator Functionalities
Authentication Management

Endpoint for Sign Up
Endpoint for Sign In
Endpoint for Sign Out
Admin Account Management

Endpoint for Deleting Admins from Database
Customer Management

Endpoint for Viewing Registered Customers
Endpoint for Viewing Customer Information
Endpoint for Viewing Customer Bank Accounts
Endpoint for Viewing Customer Beneficiaries
Endpoint for Viewing Customer Transactions
Setting & Installation
Install the Spring Tools Suite

https://spring.io/tools
Install MySQL Community Server

https://dev.mysql.com/downloads/mysql/
Clone the Project

git clone https://github.com/TejasMedade/E-Wallet-Payment-System
Open MySQL Server

Create a New Database in SQL: "e_wallet" 
Create a Admin For Your Database

INSERT INTO ADMIN VALUES('1001','admin_email','admin_first_name','admin_last_name','admin_mobile_number','admin_password');
Note for Admin & User

Admin Id : Min=1000, Max=1010 ; User Id : Enter Your Registered Mobile Number For Login, User Validation and Authentication. 
Run Locally
Go to the Project Directory

Open the Payment Wallet Application Folder with S.T.S
Go to src/main/resources > application.properties & change your username and password (MySQL server username & password)

spring.datasource.username="username"

spring.datasource.password="password"
To change the Server Port

server.port=8088
Go to com.masai package > Online_Shopping_System.java

Run as Spring Boot App !
Open the following URL for Swagger-UI

http://localhost:8088/swagger-ui/
ER Diagram
E-Wallet(1)

URL
http://localhost:8088
API REFERENCES
Customer API Reference
Screenshot 2022-11-25 at 02-28-34 Swagger UI

Wallet API Reference
Screenshot 2022-11-25 at 02-30-27 Swagger UI

Address API Reference
Screenshot 2022-11-25 at 02-27-29 Swagger UI

Bank Account API Reference
Screenshot 2022-11-25 at 02-27-55 Swagger UI

Beneficiary API Reference
Screenshot 2022-11-25 at 02-28-10 Swagger UI

Bill Payment API Reference
Screenshot 2022-11-25 at 02-28-22 Swagger UI

Customer Login Logout API Reference
Screenshot 2022-11-25 at 02-29-05 Swagger UI

Admin Login Logout API Reference
Screenshot 2022-11-25 at 02-28-53 Swagger UI

Transactions API Reference
Screenshot 2022-11-25 at 02-29-19 Swagger UI

Contributions
Contributions are always Welcome !

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are Greatly Appreciated.

If you have any ideas on how to improve this resume, please feel free to fork the repository and submit a pull request. Your contributions, no matter how big or small, are greatly appreciated and will help to make this repository even better.

In addition to contributing to the repository, you can also connect with me for further development and collaboration on this API. Together, we can continue to improve and evolve the API to meet the needs of the community.

We encourage you to give the repository a star and we thank you for your interest in this project.

Your support is greatly appreciated.
