#BOLTU-SHOP
This was my first project.

### Project Overview

[cite\_start]The "Boltu Shop" project is an online shopping platform developed using the C++ programming language[cite: 1560]. [cite\_start]It is designed to provide users with a secure and convenient shopping experience[cite: 1567]. [cite\_start]The platform accommodates three distinct user roles: customers, sellers, and administrators, each with a separate login menu to ensure data security and role-specific access[cite: 1561, 1562]. The system manages product, user, and sales data through text files.

-----

### Project Goal

[cite\_start]The primary goal of the Boltu Shop project is to create a robust, secure, and user-friendly online shopping platform[cite: 1570, 1579]. [cite\_start]It aims to address common concerns in e-commerce, such as the security of personal information and the reliability of online stores, by providing a stable platform capable of handling a large number of users and transactions[cite: 1569, 1572].

-----

### Methodology

[cite\_start]The project was developed using C++ and follows an object-oriented approach[cite: 1571]. [cite\_start]The system's architecture is divided into three main interfaces for customers, sellers, and admins[cite: 1573]. Key methodologies include:

  * **Data Management:** The platform uses flat files (`products.txt`, `users.txt`, `sales.txt`) for persistent data storage.
  * [cite\_start]**User Authentication:** Separate login functionalities exist for each user type to ensure secure access to their respective dashboards[cite: 1562].
  * **Modular Design:** The code is structured into classes such as `Product`, `Sale`, `ProductManager`, and `UserList` to manage different aspects of the shop's functionality.

-----

### Project Files

  * `Boltu_online_shop.cpp`: The main C++ source code file containing all the logic for the application.
  * `Boltu_online_shop.pdf`: The detailed project report, including an abstract, design diagrams, and descriptions.
  * `products.txt`: A text file that stores the list of available products, their prices, and quantities.
  * [cite\_start]`users.txt`: A text file that stores customer usernames and passwords[cite: 1629].
  * `sales.txt`: A text file that logs all purchase transactions made by customers.

-----

### Key Findings

[cite\_start]The project successfully created a comprehensive e-commerce platform that meets the needs of buyers, sellers, and administrators[cite: 2042, 2051]. [cite\_start]The platform is user-friendly, secure, and robust[cite: 2048, 2050]. [cite\_start]A unique feature is the admin panel, which allows administrators to manage user accounts and product listings, a feature not always present in similar platforms[cite: 2047, 1595].

-----

### Getting Started

To compile and run this project, you will need the following:

  * A C++ compiler, such as g++ (MinGW).
  * [cite\_start]A C++ Integrated Development Environment (IDE) like Code::Blocks is recommended[cite: 2035].
  * The Windows operating system is recommended due to the use of `<windows.h>`.

-----

### How to Run the Project

1.  **Compile the Code:**
    Open a terminal or command prompt and navigate to the project directory. Compile the source code using a C++ compiler.

    ```
    g++ Boltu_online_shop.cpp -o Boltu_online_shop.exe
    ```

2.  **Prepare Files:**
    Ensure the following text files are present in the same directory as the executable:

      * `products.txt`
      * `users.txt`
      * `sales.txt`

3.  **Run the Executable:**
    Execute the compiled program from the terminal.

    ```
    ./Boltu_online_shop.exe
    ```

4.  **Log in with Default Credentials:**

      * **Seller:**
          * [cite\_start]Username: `deloar` [cite: 1938]
          * [cite\_start]Password: `seller` [cite: 1838]
      * **Admin:**
          * [cite\_start]Username: `ADMIN` [cite: 1931]
          * [cite\_start]Password: `admin@123` [cite: 1932]
